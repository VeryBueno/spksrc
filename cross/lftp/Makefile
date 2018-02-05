PKG_NAME = lftp
PKG_VERS = 4.8.3
PKG_EXT = tar.xz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://lftp.yar.ru/ftp/
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)
CONFIGURE_ARGS = --with-readline=$(WORK_DIR)/install$(INSTALL_PREFIX)

DEPENDS = cross/readline cross/ncurses cross/gnutls

HOMEPAGE = https://lftp.yar.ru/
COMMENT  = "LFTP is a sophisticated file transfer program supporting a number of network protocols (ftp, http, sftp, fish, torrent)."
LICENSE  = GPLv2/GPLv3

GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk

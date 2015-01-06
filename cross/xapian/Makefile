PKG_NAME = xapian-core
PKG_VERS = 1.2.19
PKG_EXT = tar.xz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://oligarchy.co.uk/xapian/$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/zlib cross/uuid

HOMEPAGE = 
COMMENT  =
LICENSE  =

GNU_CONFIGURE = 1

#CONFIGURE_TARGET = nope
#INSTALL_TARGET = nope
#PRE_INSTALL_TARGET = nope

#TEST:
#	@echo $(PKG_DIST_NAME)

include ../../mk/spksrc.cross-cc.mk

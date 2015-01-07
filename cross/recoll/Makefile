PKG_NAME = recoll
PKG_VERS = 1.20.1
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.lesbonscomptes.com/recoll
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/zlib cross/xapian cross/python

HOMEPAGE = http://www.lesbonscomptes.com/recoll/
COMMENT  = A full-text search tool.
LICENSE  =

GNU_CONFIGURE = 1
CONFIGURE_ARGS = --disable-qtgui --disable-x11mon --disable-python-module

#CONFIGURE_TARGET = nope
#INSTALL_TARGET = nope
#PRE_INSTALL_TARGET = nope

#TEST:
#	@echo $(PKG_DIST_NAME)

include ../../mk/spksrc.cross-cc.mk

jpp-smart-clean:
	rm -rf work-cedarview-5.1/$(PKG_DIR)
	rm -f work-cedarview-5.1/.recoll*	

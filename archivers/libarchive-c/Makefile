# $OpenBSD$

MODPY_EGG_VERSION =	2.7
COMMENT =	Python interface to libarchive
DISTNAME =	libarchive-c-${MODPY_EGG_VERSION}
PKGNAME =	py-${DISTNAME}
CATEGORIES =	archivers devel

MAINTAINER =	Brian Callahan <bcallah@openbsd.org>

# CC0
PERMIT_PACKAGE_CDROM =	Yes

FLAVORS =	python3
FLAVOR ?=

MODULES =	lang/python
MODPY_PI =	Yes
MODPY_SETUPTOOLS =	Yes

RUN_DEPENDS =	archivers/libarchive

.include <bsd.port.mk>

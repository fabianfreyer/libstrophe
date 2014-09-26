# Created by: Fabian Freyer <fabian.freyer@physik.tu-berlin.de>
# $FreeBSD$

PORTNAME=      libstrophe
PORTVERSION=   0.8.6
CATEGORIES=    net-im
MASTER_SITES=  GH

MAINTAINER=    nobody@example.org
COMMENT=       A simple, lightweight C library for writing XMPP clients

LICENSE=       GPLv3 MIT
LICENSE_COMB=  dual

BUILD_DEPENDS= pkgconf:${PORTSDIR}/devel/pkgconf
LIB_DEPENDS=   libcheck.so:${PORTSDIR}/devel/libcheck

USE_GITHUB=    yes
GH_ACCOUNT=    strophe
GH_PROJECT=    libstrophe
GH_COMMIT=     d693cc6

DIST_SUBDIR=   ${PORTNAME}

CONFIGURE_ARGS=--with-pkgconfigdir=${PREFIX}/libdata/pkgconfig
AUTOMAKE_ARGS= --add-missing
USE_AUTOTOOLS= libtoolize autoconf aclocal automake
GNU_CONFIGURE= yes

.include <bsd.port.mk>

# $NetBSD: Makefile,v 1.3 2018/08/08 20:41:06 nia Exp $

DISTNAME=	libretro-gambatte-20180709
CATEGORIES=	emulators
MASTER_SITES=	${MASTER_SITE_GITHUB:=libretro/}
GITHUB_PROJECT=	gambatte-libretro
GITHUB_TAG=	7722012ce85e56c324cb2080645347689ca379ae

MAINTAINER=	nia@NetBSD.org
HOMEPAGE=	https://docs.libretro.com/library/gambatte/
COMMENT=	Libretro core based on the Gambatte Game Boy Color emulator
LICENSE=	gnu-gpl-v2

EXTRACT_USING=	bsdtar
USE_LANGUAGES=	c c++03
MAKE_FILE=	Makefile.libretro
USE_TOOLS+=	gmake

INSTALLATION_DIRS+=	${PREFIX}/lib/libretro

do-install:
	${INSTALL_LIB} ${WRKSRC}/gambatte_libretro.so \
	    ${DESTDIR}${PREFIX}/lib/libretro/gambatte_libretro.so

.include "../../mk/bsd.pkg.mk"

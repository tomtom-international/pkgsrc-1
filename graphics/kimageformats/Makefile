# $NetBSD: Makefile,v 1.14 2018/07/20 03:34:15 ryoon Exp $

DISTNAME=	kimageformats-${KF5VER}
PKGREVISION=	1
CATEGORIES=	graphics

HOMEPAGE=	https://community.kde.org/Frameworks
COMMENT=	Image format plugins for Qt5
LICENSE=	gnu-lgpl-v2.1

.include "../../meta-pkgs/kde/kf5.mk"

USE_TOOLS+=	pkg-config

.include "../../archivers/karchive/buildlink3.mk"
.include "../../graphics/openexr/buildlink3.mk"
.include "../../x11/qt5-qtbase/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"

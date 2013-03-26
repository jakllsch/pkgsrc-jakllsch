# $NetBSD$
#

DISTNAME=	gtkdatabox-0.9.2.0
CATEGORIES=	x11
MASTER_SITES=	http://downloads.sourceforge.net/project/gtkdatabox/gtkdatabox/0.9.2.0/

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	http://sourceforge.net/projects/gtkdatabox/
COMMENT=	TODO: Short description of the package
#LICENSE=	# TODO: (see mk/license.mk)

GNU_CONFIGURE=	yes
USE_LIBTOOL=	yes
USE_TOOLS+=	pkg-config

PKGCONFIG_OVERRIDE+=	gtkdatabox.pc.in

.include "../../x11/gtk2/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"

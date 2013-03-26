# $NetBSD$
#

DISTNAME=	klavaro-1.9.6
CATEGORIES=	jakllsch
MASTER_SITES=	http://sourceforge.net/projects/klavaro/files/
EXTRACT_SUFX=	.tar.bz2

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	http://sourceforge.net/projects/klavaro/
COMMENT=	touch typing tutor
#LICENSE=	# TODO: (see mk/license.mk)

GNU_CONFIGURE=	yes
USE_TOOLS+=	perl pkg-config intltool gmake

.include "../../jakllsch/gtkdatabox/buildlink3.mk"
.include "../../x11/gtk2/buildlink3.mk"
.include "../../graphics/hicolor-icon-theme/buildlink3.mk"
.include "../../sysutils/desktop-file-utils/desktopdb.mk"
.include "../../www/curl/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"

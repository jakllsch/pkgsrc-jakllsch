DISTNAME=	jakllsch-meta-meta-0.0.0.2012.10.20.0
#PKGREVISION=	0
CATEGORIES=	meta-pkgs
MASTER_SITES=	
DISTFILES=	
MAINTAINER=	jakllsch@kollasch.net
COMMENT=	personal metapackage - metapackage
META_PACKAGE=	yes
LICENSE=	public-domain


DEPENDS+=	jakllsch-meta-misc:../jakllsch-meta-misc
DEPENDS+=	jakllsch-meta-gui-base:../jakllsch-meta-gui-base
DEPENDS+=	jakllsch-meta-fonts:../jakllsch-meta-fonts
DEPENDS+=	jakllsch-meta-gui:../jakllsch-meta-gui
DEPENDS+=	jakllsch-meta-netbsd-developer:../jakllsch-meta-netbsd-developer
DEPENDS+=	jakllsch-meta-pkgsrc-developer:../jakllsch-meta-pkgsrc-developer
.include "../../mk/bsd.prefs.mk"
.if ${X11_TYPE} == "modular"
DEPENDS+=	jakllsch-meta-xorg-modular:../jakllsch-meta-xorg-modular
.endif

.include "../../mk/bsd.pkg.mk"

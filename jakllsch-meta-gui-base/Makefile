DISTNAME=	jakllsch-meta-gui-base-0.0.0.2012.02.02.0
#PKGREVISION=	0
CATEGORIES=	meta-pkgs
MASTER_SITES=	
DISTFILES=	
MAINTAINER=	jakllsch@kollasch.net
COMMENT=	personal metapackage - base GUI
META_PACKAGE=	yes
LICENSE=	public-domain

.include "../../mk/bsd.prefs.mk"
.if ${X11_TYPE} == "modular"
DEPENDS+=	jakllsch-meta-xorg-modular:../../jakllsch/jakllsch-meta-xorg-modular
.endif

.if ${X11_TYPE} == "modular"
DEPENDS+=	xterm:../../x11/xterm
.endif
DEPENDS+=	rxvt-unicode:../../x11/rxvt-unicode
DEPENDS+=	openbox:../../wm/openbox
DEPENDS+=	gio-fam:../../sysutils/gio-fam
DEPENDS+=	jakllsch-meta-fonts:../../jakllsch/jakllsch-meta-fonts
DEPENDS+=	xcalib:../../x11/xcalib
DEPENDS+=	xicc:../../x11/xicc
DEPENDS+=	hsetroot:../../x11/hsetroot
DEPENDS+=	xcompmgr:../../x11/xcompmgr

.include "../../mk/bsd.pkg.mk"

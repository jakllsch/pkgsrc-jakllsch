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
DEPENDS+=	jakllsch-meta-xorg-modular-[0-9]*:../../jakllsch/jakllsch-meta-xorg-modular
.endif

.if ${X11_TYPE} == "modular"
DEPENDS+=	xterm-[0-9]*:../../x11/xterm
.endif
DEPENDS+=	rxvt-unicode-[0-9]*:../../x11/rxvt-unicode
DEPENDS+=	openbox-[0-9]*:../../wm/openbox
DEPENDS+=	gio-fam-[0-9]*:../../sysutils/gio-fam
DEPENDS+=	jakllsch-meta-fonts-[0-9]*:../../jakllsch/jakllsch-meta-fonts
DEPENDS+=	xcalib-[0-9]*:../../x11/xcalib
DEPENDS+=	xicc-[0-9]*:../../x11/xicc
DEPENDS+=	hsetroot-[0-9]*:../../x11/hsetroot
DEPENDS+=	xcompmgr-[0-9]*:../../x11/xcompmgr

.include "../../mk/bsd.pkg.mk"

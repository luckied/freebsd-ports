# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD$

PORTNAME=	trytond28_stock_supply
PORTVERSION=	2.8.4
PORTREVISION=	2
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads-cdn.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_stock_supply-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Stock Supply Module)

DEPRECATED=	Outdated, uses EOLed python27
EXPIRATION_DATE=	2020-02-03

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_stock>=2.8.2:finance/trytond28_stock \
		trytond28_purchase>=2.8.0:finance/trytond28_purchase

CONFLICTS=	trytond_stock_supply-2.[46].*

USES=		python:2.7
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>

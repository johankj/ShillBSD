# $FreeBSD$
#
# Author: Harti Brandt <harti@freebsd.org>

MOD=	netgraph
SRCS=	snmp_netgraph.c
XSYM=	begemotNg
MAN=	snmp_netgraph.3

BMIBS=	BEGEMOT-NETGRAPH.txt
DEFS=	${MOD}_tree.def
INCS=	snmp_${MOD}.h

DPADD=	${LIBNETGRAPH}
LDADD=	-lnetgraph

.include <bsd.snmpmod.mk>

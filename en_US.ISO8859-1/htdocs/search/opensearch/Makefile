# $FreeBSD: head/en_US.ISO8859-1/htdocs/search/opensearch/Makefile 46874 2015-06-27 02:36:16Z peter $

.if exists(../Makefile.conf)
.include "../Makefile.conf"
.endif
.if exists(../Makefile.inc)
.include "../Makefile.inc"
.endif

DOCS+= 		opensearch.xml
INDEXLINK=	opensearch.html

DATA=
DATA+=	opensearch.js

DATA+=	man.xml
DATA+=	man-freebsd-release-ports.xml
DATA+=	ports.xml
DATA+=	message-id.xml

# external sites
DATA+=	markmail.xml
DATA+=	rambler.xml
DATA+=	portoverview.xml

.include "${DOC_PREFIX}/share/mk/web.site.mk"

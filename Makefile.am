## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src po

cstldocdir = ${prefix}/doc/cstl
cstldoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


INTLTOOL_FILES = intltool-extract.in \
	intltool-merge.in \
	intltool-update.in

EXTRA_DIST = $(cstldoc_DATA) \
	$(INTLTOOL_FILES)\
	libcstl-0.1.pc.in

DISTCLEANFILES = intltool-extract \
	intltool-merge \
	intltool-update \
	po/.intltool-merge-cache


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(cstldocdir)

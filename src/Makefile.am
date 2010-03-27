## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" 

AM_CFLAGS =\
	 -Wall\
	 -g

lib_LTLIBRARIES = libcstl.la


libcstl_la_SOURCES = \
	lib.c

libcstl_la_LDFLAGS = 

libcstl_la_LIBADD = 

include_HEADERS = \
	cstl.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libcstl-0.1.pc

EXTRA_DIST = \
	libcstl-0.1.pc.in

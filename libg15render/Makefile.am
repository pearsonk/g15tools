## Process this file with automake to produce Makefile.in

SUBDIRS = src

EXTRA_DIST = debian Doxyfile libg15render.3 fonts

MAINTAINERCLEANFILES = \
    configure \
    Makefile.in \
    config.h.in \
    aclocal.m4 \
    config/*

man3_MANS = $(top_srcdir)/libg15render.3
docdir = $(prefix)/share/doc/$(PACKAGE)-$(VERSION)
doc_DATA = AUTHORS ChangeLog COPYING NEWS README
fontdir = $(prefix)/share/g15tools/fonts/G15
#font_DATA = fonts/
font_DATA = fonts/default-00.fnt \
						fonts/default-01.fnt \
						fonts/default-02.fnt \
						fonts/default-03.fnt \
						fonts/default-04.fnt \
						fonts/default-05.fnt \
						fonts/default-06.fnt \
						fonts/default-07.fnt \
						fonts/default-08.fnt \
						fonts/default-09.fnt \
						fonts/default-10.fnt \
						fonts/default-11.fnt \
						fonts/default-12.fnt \
						fonts/default-13.fnt \
						fonts/default-14.fnt \
						fonts/default-15.fnt \
						fonts/default-16.fnt \
						fonts/default-17.fnt \
						fonts/default-18.fnt \
						fonts/default-19.fnt \
						fonts/default-20.fnt \
						fonts/default-21.fnt \
						fonts/default-22.fnt \
						fonts/default-23.fnt \
						fonts/default-24.fnt \
						fonts/default-25.fnt \
						fonts/default-26.fnt \
						fonts/default-27.fnt \
						fonts/default-28.fnt \
						fonts/default-29.fnt \
						fonts/default-30.fnt \
						fonts/default-31.fnt \
						fonts/default-32.fnt \
						fonts/default-33.fnt \
						fonts/default-34.fnt \
						fonts/default-35.fnt \
						fonts/default-36.fnt \
						fonts/default-37.fnt \
						fonts/default-38.fnt \
						fonts/default-39.fnt

dist-hook:
	rm -rf `find $(distdir)/debian -name .svn`


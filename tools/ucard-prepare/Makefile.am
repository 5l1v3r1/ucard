# $Id$

AM_CFLAGS = @LIBFREEFARE_CFLAGS@
AM_CPPFLAGS = -I $(top_srcdir)/libucard

bin_PROGRAMS = ucard-prepare

ucard_prepare_SOURCES = ucard-prepare.c
ucard_prepare_LDADD = $(top_builddir)/libucard/libucard.la

# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.0 from Makefile.am

# Copyright (C) 1994, 1995, 1996 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy, distribute and modify it.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..
prefix = /usr
exec_prefix = 

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

pkgdatadir = $(datadir)/shadow
pkglibdir = $(libdir)/shadow
pkgincludedir = $(includedir)/shadow

top_builddir = ..

INSTALL = /usr/bin/ginstall -c
INSTALL_PROGRAM = ${INSTALL}
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = @INSTALL_SCRIPT@
transform = s,x,x,

AUTOMAKE_OPTIONS = 1.0 foreign

noinst_LIBRARIES = misc

libdir = ${prefix}/lib

INCLUDES = -I$(top_srcdir)/lib

misc_SOURCES = addgrps.c age.c basename.c chkname.c chowndir.c chowntty.c \
 console.c copydir.c entry.c env.c failure.c fields.c hushed.c \
 isexpired.c limits.c list.c log.c login_access.c login_desrpc.c \
 login_krb.c loginprompt.c mail.c motd.c obscure.c pwd2spwd.c rlogin.c \
 salt.c setugid.c setup.c setupenv.c shell.c strtoday.c suauth.c \
 sub.c sulog.c ttytype.c tz.c ulimit.c utmp.c valid.c xmalloc.c
mkinstalldirs = $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = ../config.h
LIBRARIES = $(noinst_LIBRARIES)

noinst_LIBFILES = libmisc.a

CC = gcc
LEX = @LEX@
YACC = @YACC@

DEFS = -DHAVE_CONFIG_H -I. -I$(srcdir) -I..
CPPFLAGS = 
CFLAGS = -O2 -Wall
LDFLAGS = -s
LIBS = 

COMPILE = $(CC) -c $(DEFS) $(INCLUDES) $(CPPFLAGS) $(CFLAGS)
LINK = $(CC) $(LDFLAGS) -o $@
misc_LIBADD =
misc_OBJECTS = addgrps.o age.o basename.o chkname.o chowndir.o \
chowntty.o console.o copydir.o entry.o env.o failure.o fields.o \
hushed.o isexpired.o limits.o list.o log.o login_access.o \
login_desrpc.o login_krb.o loginprompt.o mail.o motd.o obscure.o \
pwd2spwd.o rlogin.o salt.o setugid.o setup.o setupenv.o shell.o \
strtoday.o suauth.o sub.o sulog.o ttytype.o tz.o ulimit.o utmp.o \
valid.o xmalloc.o
EXTRA_misc_SOURCES =
LIBFILES =  libmisc.a
AR = ar
RANLIB = ranlib
DIST_COMMON = Makefile.am Makefile.in


PACKAGE = shadow
VERSION = 961025

DISTFILES = $(DIST_COMMON) $(SOURCES) $(BUILT_SOURCES) $(HEADERS) \
	$(TEXINFOS) $(INFOS) $(MANS) $(EXTRA_DIST) $(DATA)
DEP_DISTFILES = $(DIST_COMMON) $(SOURCES) $(BUILT_SOURCES) $(HEADERS) \
	$(TEXINFOS) $(INFO_DEPS) $(MANS) $(EXTRA_DIST) $(DATA)

TAR = tar
SOURCES = $(misc_SOURCES)
OBJECTS = $(misc_OBJECTS)

default: all



mostlyclean-noinstLIBRARIES:

clean-noinstLIBRARIES:
	rm -f $(noinst_LIBFILES)

distclean-noinstLIBRARIES:

maintainer-clean-noinstLIBRARIES:

.c.o:
	$(COMPILE) $<

mostlyclean-compile:
	rm -f *.o core

clean-compile:

distclean-compile:
	rm -f *.tab.c

maintainer-clean-compile:
$(misc_OBJECTS): ../config.h

libmisc.a: $(misc_OBJECTS) $(misc_LIBADD)
	rm -f libmisc.a
	$(AR) cru libmisc.a $(misc_OBJECTS) $(misc_LIBADD)
	$(RANLIB) libmisc.a

ID: $(HEADERS) $(SOURCES)
	here=`pwd` && cd $(srcdir) && mkid -f$$here/ID $(SOURCES) $(HEADERS)

tags: TAGS

TAGS: $(HEADERS) $(SOURCES) $(TAGS_DEPENDENCIES)
	here=`pwd` && cd $(srcdir) && etags $(ETAGS_ARGS) $(SOURCES) $(HEADERS) -o $$here/TAGS

mostlyclean-tags:

clean-tags:

distclean-tags:
	rm -f TAGS ID

maintainer-clean-tags:

subdir = libmisc
distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)
distdir: $(DEP_DISTFILES)
	@for file in `cd $(srcdir) && echo $(DISTFILES)`; do \
	  test -f $(distdir)/$$file \
	  || ln $(srcdir)/$$file $(distdir)/$$file 2> /dev/null \
	  || cp -p $(srcdir)/$$file $(distdir)/$$file; \
	done
addgrps.o: addgrps.c ../lib/defines.h ../lib/rcsid.h
age.o: age.c ../lib/prototypes.h ../lib/faillog.h ../lib/defines.h \
 ../lib/rcsid.h
basename.o: basename.c ../lib/rcsid.h ../lib/defines.h
chkname.o: chkname.c ../lib/rcsid.h ../lib/defines.h
chowndir.o: chowndir.c ../lib/rcsid.h ../lib/defines.h
chowntty.o: chowntty.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h ../lib/getdef.h
console.o: console.c ../lib/defines.h ../lib/getdef.h ../lib/rcsid.h
copydir.o: copydir.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h
entry.o: entry.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
env.o: env.c ../lib/rcsid.h ../lib/defines.h
failure.o: failure.c ../lib/rcsid.h ../lib/defines.h ../lib/faillog.h \
 ../lib/getdef.h
fields.o: fields.c ../lib/rcsid.h
hushed.o: hushed.c ../lib/rcsid.h ../lib/defines.h
isexpired.o: isexpired.c ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h ../lib/rcsid.h
limits.o: limits.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h ../lib/getdef.h
list.o: list.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
log.o: log.c ../lib/rcsid.h ../lib/defines.h
login_access.o: login_access.c ../lib/rcsid.h
login_desrpc.o: login_desrpc.c
login_krb.o: login_krb.c
loginprompt.o: loginprompt.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h ../lib/getdef.h
mail.o: mail.c ../lib/defines.h ../lib/getdef.h ../lib/rcsid.h
motd.o: motd.c ../lib/rcsid.h ../lib/defines.h
obscure.o: obscure.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h ../lib/getdef.h
pwd2spwd.o: pwd2spwd.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h
rlogin.o: rlogin.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
salt.o: salt.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h ../lib/md5.h ../lib/getdef.h
setugid.o: setugid.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h ../lib/getdef.h
setup.o: setup.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
setupenv.o: setupenv.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h ../lib/getdef.h
shell.o: shell.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
strtoday.o: strtoday.c ../lib/rcsid.h ../lib/defines.h
suauth.o: suauth.c ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
sub.o: sub.c ../lib/rcsid.h ../lib/defines.h
sulog.o: sulog.c ../lib/rcsid.h ../lib/defines.h ../lib/getdef.h
ttytype.o: ttytype.c ../lib/rcsid.h ../lib/prototypes.h \
 ../lib/faillog.h ../lib/defines.h
tz.o: tz.c ../lib/rcsid.h ../lib/getdef.h
ulimit.o: ulimit.c ../lib/rcsid.h
utmp.o: utmp.c ../lib/defines.h ../lib/rcsid.h
valid.o: valid.c ../lib/rcsid.h ../lib/prototypes.h ../lib/faillog.h \
 ../lib/defines.h
xmalloc.o: xmalloc.c ../lib/rcsid.h ../lib/defines.h

info:

dvi:

check: all

installcheck:

install-exec: 

install-data: 

install: install-exec install-data all
	@:

uninstall: 

all: $(LIBFILES) Makefile

install-strip:
	$(MAKE) INSTALL_PROGRAM='$(INSTALL_PROGRAM) -s' install
installdirs:


mostlyclean-generic:
	test -z "$(MOSTLYCLEANFILES)" || rm -f $(MOSTLYCLEANFILES)

clean-generic:
	test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	rm -f Makefile $(DISTCLEANFILES)
	rm -f config.cache config.log $(CONFIG_HEADER) stamp-h

maintainer-clean-generic:
	test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
	test -z "$(BUILT_SOURCES)" || rm -f $(BUILT_SOURCES)
mostlyclean:  mostlyclean-noinstLIBRARIES mostlyclean-compile \
		mostlyclean-tags mostlyclean-generic

clean:  clean-noinstLIBRARIES clean-compile clean-tags clean-generic \
		mostlyclean 

distclean:  distclean-noinstLIBRARIES distclean-compile distclean-tags \
		distclean-generic clean 
	rm -f config.status

maintainer-clean:  maintainer-clean-noinstLIBRARIES \
		maintainer-clean-compile maintainer-clean-tags \
		maintainer-clean-generic distclean 
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

.PHONY: default mostlyclean-noinstLIBRARIES distclean-noinstLIBRARIES \
clean-noinstLIBRARIES maintainer-clean-noinstLIBRARIES \
mostlyclean-compile distclean-compile clean-compile \
maintainer-clean-compile tags mostlyclean-tags distclean-tags \
clean-tags maintainer-clean-tags distdir info dvi check installcheck \
install-exec install-data install uninstall all installdirs \
mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean

.SUFFIXES:
.SUFFIXES: .c .o

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:

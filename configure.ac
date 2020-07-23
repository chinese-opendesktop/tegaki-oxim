#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

# $Id: configure.ac,v 1.84 2009/03/19 06:31:19 wind Exp $

AC_PREREQ(2.59)
AC_INIT([tegaki-oxim], 0.2, [yc.yan@ossii.com.tw])
AM_INIT_AUTOMAKE($PACKAGE_NAME, $PACKAGE_VERSION)

AC_PREFIX_DEFAULT([/usr])  # 預設安裝路徑
AC_CONFIG_SRCDIR([COPYING])
#AC_CONFIG_HEADER([config.h])


# i18N
AM_GNU_GETTEXT([external])
PACKAGE_GETTEXT=gettext
VERSION_GETTEXT=0.1
AC_SUBST(PACKAGE_GETTEXT)
AC_SUBST(VERSION_GETTEXT)


# Checks for library
AC_CHECK_LIB(intl, gettext)

#-----------------------------------------------------------------------
# 
#-----------------------------------------------------------------------
AC_OUTPUT(Makefile \
	  po/Makefile.in \
	  po/Makevars \
	  bin/main
	 )


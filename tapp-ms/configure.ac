AC_INIT([tapp], [0.0.3])

RELVER=`cat VERSION`
if test x$PACKAGE_VERSION != x$RELVER ; then
    AC_MSG_ERROR([the version number in configure.ac ($PACKAGE_VERSION) does not match the version in VERSION ($RELVER)])
fi

AC_CONFIG_AUX_DIR([config])
AM_INIT_AUTOMAKE([foreign])
AC_CONFIG_MACRO_DIRS([m4])
AC_CONFIG_SRCDIR([configure.ac])
AC_CONFIG_HEADERS([config.h])
AC_PROG_CC
AC_PROG_CXX

AC_CONFIG_FILES([
	Makefile])
AC_OUTPUT

#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([libcol], [0.01], [bipinmathew@gmail.com])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AM_MAINTAINER_MODE([enable])

AC_CONFIG_SRCDIR([col.h])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
AC_PROG_RANLIB
AM_PROG_AR

# Checks for libraries.
AC_CHECK_LIB(cunit,CU_console_run_tests)

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_REALLOC


AC_CONFIG_FILES([Makefile
                 test/Makefile])
AC_OUTPUT

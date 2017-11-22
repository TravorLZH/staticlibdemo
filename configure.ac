#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([staticlibdemo], [1.0], [travor_lzh@outlook.com])
AM_INIT_AUTOMAKE([subdir-objects])
# Checks for programs.
AC_CONFIG_SRCDIR([src/hello.c])
AC_CONFIG_SRCDIR([src/uselib.c])
# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADER([stdio.h])
AC_CONFIG_HEADER([include/config.h])
# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_CONFIG_FILES([Makefile])
AC_CHECK_LIB([c],[printf])
AC_OUTPUT
echo "SUCCESS"

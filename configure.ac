# configure.ac
#
# Use autoscan for help with manually updating

AC_PREREQ([2.69])

# Initialise autoconf with some basic info: program name, version number, maintainer.
AC_INIT([Phase Diagram Game], [0.1.0], [paulalexander23@live.co.uk])
AC_CONFIG_SRCDIR([src/phase_diagram_game.cpp])
AC_CONFIG_HEADERS([config.h])

# Initialise automake
AM_INIT_AUTOMAKE

# Tell autoconf about the dependances to look for (cpp).
# We can use other m4 macros to specify further dependances.
AC_PROG_CXX
AC_PROG_MAKE_SET

# Tell autoconf to use Makefile.in to generate a Makefile.
AC_CONFIG_FILES([Makefile
                 src/Makefile])

# Tell autoconf to produce the implement the requested output.
AC_OUTPUT

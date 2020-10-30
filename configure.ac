define(_CLIENT_VERSION_MAJOR,0)
define(_CLIENT_VERSION_MINOR,1)
define(_CLIENT_VERSION_REVISION,0)
define(_CLIENT_VERSION_BUILD,0)
define(_CLIENT_VERSION_RC,0)

AC_INIT([endpoint],m4_join([.], _CLIENT_VERSION_MAJOR, _CLIENT_VERSION_MINOR, _CLIENT_VERSION_REVISION, m4_if(_CLIENT_VERSION_BUILD, [0], [], _CLIENT_VERSION_BUILD))m4_if(_CLIENT_VERSION_RC, [0], [], [rc]_CLIENT_VERSION_RC),[https://github.com/hawkmauk/endpoint/issues],[runcrypto],[https://runcrypto.com])
AC_CONFIG_SRCDIR([src])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_MACRO_DIR([build-aux/m4])
AC_CONFIG_FILES([Makefile])

AC_CANONICAL_HOST
AC_PROG_CXX

AM_INIT_AUTOMAKE(subdir-objects foreign)

AC_OUTPUT

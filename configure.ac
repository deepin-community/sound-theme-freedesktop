
AC_PREREQ([2.60])
AC_INIT([sound-theme-freedesktop],
        [0.8],
        [http://bugzilla.freedesktop.org/enter_bug.cgi?product=sound-theme-freedesktop])

AC_CONFIG_SRCDIR([index.theme.in])

AM_INIT_AUTOMAKE([1.9 no-dist-gzip dist-bzip2])

AC_SUBST(VERSION)

IT_PROG_INTLTOOL([0.40.0])
GETTEXT_PACKAGE=sound-theme-freedesktop
AC_SUBST(GETTEXT_PACKAGE)
AC_DEFINE_UNQUOTED(GETTEXT_PACKAGE, "$GETTEXT_PACKAGE")
AM_GLIB_GNU_GETTEXT

AC_PROG_LN_S

AC_CONFIG_FILES([
Makefile
stereo/Makefile
po/Makefile.in
])

AC_OUTPUT

dnl Process this file with autoconf to produce a configure script.
AC_PREREQ(2.67)
AC_INIT([sjconf-libvirt], [0.1.2])
AM_INIT_AUTOMAKE([-Wall foreign])

SJ_PROG_SJCONF
AC_PATH_PROG(TXT2TAGS, txt2tags)

AC_CONFIG_FILES([
    Makefile
    doc/Makefile
    confs/Makefile
    plugins/libvirt.py
    templates/Makefile
    templates/libvirt/Makefile
])

AC_OUTPUT

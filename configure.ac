AC_INIT(Makefile.am)
AM_INIT_AUTOMAKE(hildon-theme-layout-5, 0.15.0)
AM_CONFIG_HEADER(config.h)

AC_PROG_INSTALL

# Check the tools installation
PKG_CHECK_MODULES(TOOLS, hildon-theme-tools >= 0.2.0)

AC_OUTPUT([Makefile                             \
           rc/Makefile                          \
           pkgconfig/hildon-theme-layout-5.pc   \
           pkgconfig/Makefile                   \
           data/Makefile                        \
           data/bundle.ini])

themedir = $(datadir)/icons/netbook/32x32/icons
theme_DATA = offline.png online.png
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(abs_top_srcdir)/icon-name-mapping -x $(abs_top_srcdir)/legacy-icon-mapping.xml -c icons )
MAINTAINERCLEANFILES = Makefile.in

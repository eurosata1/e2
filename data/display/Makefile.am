installdir = $(pkgdatadir)/display

if HAVE_COLORLCD
dist_install_DATA = skin_display96.xml
else
dist_install_DATA = skin_display.xml
endif

if HAVE_COLORLCD220
SUBDIRS = display220
endif

if HAVE_COLORLCD400
SUBDIRS = display400
endif

if HAVE_BWLCD140
SUBDIRS = vfd140
endif

if HAVE_BWLCD255
SUBDIRS = vfd255
endif

skin_display.xml: $(srcdir)/skin_display_default.xml
	test -f $(srcdir)/skin_display_$(BOXTYPE).xml && cp $(srcdir)/skin_display_$(BOXTYPE).xml skin_display.xml || cp $(srcdir)/skin_display_default.xml skin_display.xml

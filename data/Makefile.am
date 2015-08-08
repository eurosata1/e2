SUBDIRS = countries fonts extensions keymaps skin_default

dist_pkgdata_DATA = \
	encoding.conf \
	keymap.xml \
	menu.xml \
	prev.png \
	black.mvi \
	hd-testcard.mvi \
	rcpositions.xml \
	setup.xml \
	skin_default.xml \
	skin_subtitles.xml \
	startwizard.xml \
	skin.xml \
	userinterfacepositionerwizard.xml \
	freesat.t1 \
	freesat.t2 \
	timezone.xml \
	unicable.xml \
	videowizard.xml

if HAVE_TEXTLCD
dist_pkgdata_DATA += skin_text.xml
else
SUBDIRS += display
endif

THEME_NAME=	BlackCAFE
THEME_IN_FILES=index.theme.in

themedir = $(datadir)/themes/$(THEME_NAME)

theme_DATA = \
	COPYING \
	index.theme \
	README

SUFFIXES = .theme.in .theme
.theme.in.theme:
	$(AM_V_GEN) $(MSGFMT) --desktop --template $< -d $(top_srcdir)/po -o $@

SUBDIRS =		\
	gtk-2.0		\
	gtk-3.0		\
	ctk-3.0		\
	metacity-1	\
	cinnamon    \
	unity       \
	apps

DISTCLEANFILES = index.theme
EXTRA_DIST = index.theme.in

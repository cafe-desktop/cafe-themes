THEME_NAME=GreenLagoon-border

themedir = $(datadir)/themes/$(THEME_NAME)

theme_DATA = \
	COPYING

SUFFIXES = .theme.in .theme
.theme.in.theme:
	$(AM_V_GEN) $(MSGFMT) --desktop --template $< -d $(top_srcdir)/po -o $@

SUBDIRS = \
	metacity-1


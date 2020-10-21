 BRANDING = \
	branding.desc \
	languages.png \
	logo.svg \
	show.qml \
	squid.png

BRANDINGDIR = /usr/share/calamares/branding/artix

RM = rm -f

install:
	install -dm755 $(DESTDIR)$(BRANDINGDIR)
	install -m644 $(BRANDING) $(DESTDIR)$(BRANDINGDIR)

uninstall:
	for f in $(BRANDING); do $(RM) $(DESTDIR)$(BRANDINGDIR)/$$f; done

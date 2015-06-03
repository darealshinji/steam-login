PREFIX ?= /usr


all:

clean:

distclean:

install:
	install -m755 -D steam-de $(DESTDIR)$(PREFIX)/bin/steam-de
	install -m644 -D steam-de.default $(DESTDIR)/etc/default/steam-de
	install -m644 -D custom_steam-bigpicture_badge.png $(DESTDIR)$(PREFIX)/share/unity-greeter/custom_steam-bigpicture_badge.png
	install -m644 -D steam-bigpicture.desktop $(DESTDIR)$(PREFIX)/share/xsessions/steam-bigpicture.desktop

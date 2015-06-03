PREFIX ?= /usr


all:

clean:

distclean:

install:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	mkdir -p $(DESTDIR)$(PREFIX)/share/unity-greeter
	mkdir -p $(DESTDIR)$(PREFIX)/share/xsessions
	install -m755 steam-de $(DESTDIR)$(PREFIX)/bin
	install -m644 steam-de.default $(DESTDIR)/etc/steam-de
	install -m644 custom_steam-bigpicture_badge.png $(DESTDIR)$(PREFIX)/share/unity-greeter
	install -m644 steam-bigpicture.desktop $(DESTDIR)$(PREFIX)/share/xsessions


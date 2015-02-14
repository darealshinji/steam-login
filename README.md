steam-session-openbox
=====================

Launch Steam Big Picture from your login screen.

This is a fork of thor27's steam-login for GDM/LightDM, using OpenBox instead of xfwm4 as window manager.


KNOWN ISSUES
------------

Steam, sometimes, may "hide" itself, mostly when something went wrong with a game or Steam itself. If this happens just press ALT+TAB to get back do Steam Big Picture.


INSTALL
-------

On Ubuntu or Debian you can run `./build-debian-package.sh` to build a binary package.

There's an untested Arch Linux PKGBUILD script stored in `packaging/arch`.

On other distributions you can use the provided Makefile in `steam-session`.
Run `make install PREFIX=/usr/local` as root or sudo.


CONTRIBUTING
------------

Fork and send pull requests.


Debian
====================
This directory contains files used to package indiod/indio-qt
for Debian-based Linux systems. If you compile indiod/indio-qt yourself, there are some useful files here.

## indio: URI support ##


indio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install indio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your indio-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

indio-qt.protocol (KDE)


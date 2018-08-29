
Debian
====================
This directory contains files used to package cbpd/cbp-qt
for Debian-based Linux systems. If you compile cbpd/cbp-qt yourself, there are some useful files here.

## cbp: URI support ##


cbp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cbp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cbpqt binary to `/usr/bin`
and the `../../share/pixmaps/cbp128.png` to `/usr/share/pixmaps`

cbp-qt.protocol (KDE)


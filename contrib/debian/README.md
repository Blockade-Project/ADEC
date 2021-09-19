
Debian
====================
This directory contains files used to package blockaded/blockade-qt
for Debian-based Linux systems. If you compile blockaded/blockade-qt yourself, there are some useful files here.

## pivx: URI support ##


blockade-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blockade-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blockade-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

blockade-qt.protocol (KDE)


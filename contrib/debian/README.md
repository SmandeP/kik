
Debian
====================
This directory contains files used to package chronosd/chronos-qt
for Debian-based Linux systems. If you compile chronosd/chronos-qt yourself, there are some useful files here.

## chronos: URI support ##


chronos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chronos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chronosqt binary to `/usr/bin`
and the `../../share/pixmaps/chronos128.png` to `/usr/share/pixmaps`

chronos-qt.protocol (KDE)



Debian
====================
This directory contains files used to package katanad/katana-qt
for Debian-based Linux systems. If you compile katanad/katana-qt yourself, there are some useful files here.

## katana: URI support ##


katana-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install katana-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your katana-qt binary to `/usr/bin`
and the `../../share/pixmaps/katana128.png` to `/usr/share/pixmaps`

katana-qt.protocol (KDE)


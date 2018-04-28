
Debian
====================
This directory contains files used to package corvusd/corvus-qt
for Debian-based Linux systems. If you compile corvusd/corvus-qt yourself, there are some useful files here.

## corvus: URI support ##


corvus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install corvus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your corvus-qt binary to `/usr/bin`
and the `../../share/pixmaps/corvus128.png` to `/usr/share/pixmaps`

corvus-qt.protocol (KDE)


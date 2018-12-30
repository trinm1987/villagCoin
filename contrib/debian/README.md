
Debian
====================
This directory contains files used to package dashd/village-qt
for Debian-based Linux systems. If you compile dashd/village-qt yourself, there are some useful files here.

## village: URI support ##


village-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install village-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your village-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

village-qt.protocol (KDE)


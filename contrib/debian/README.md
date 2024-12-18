
Debian
====================
This directory contains files used to package rigvidd/rigvid-qt
for Debian-based Linux systems. If you compile rigvidd/rigvid-qt yourself, there are some useful files here.

## pivx: URI support ##


rigvid-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rigvid-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rigvid-qt binary to `/usr/bin`
and the `../../share/pixmaps/rigvid128.png` to `/usr/share/pixmaps`

rigvid-qt.protocol (KDE)


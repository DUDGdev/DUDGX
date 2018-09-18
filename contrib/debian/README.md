
Debian
====================
This directory contains files used to package dudgxd/Dudgx-qt
for Debian-based Linux systems. If you compile dudgxd/Dudgx-qt yourself, there are some useful files here.

## Dudgx: URI support ##


Dudgx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Dudgx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dudgxqt binary to `/usr/bin`
and the `../../share/pixmaps/dudgx128.png` to `/usr/share/pixmaps`

Dudgx-qt.protocol (KDE)


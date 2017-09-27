
Debian
====================
This directory contains files used to package arepacoind/arepacoin-qt
for Debian-based Linux systems. If you compile arepacoind/arepacoin-qt yourself, there are some useful files here.

## arepacoin: URI support ##


arepacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install arepacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your arepacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/arepacoin128.png` to `/usr/share/pixmaps`

arepacoin-qt.protocol (KDE)


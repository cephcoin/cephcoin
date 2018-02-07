
Debian
====================
This directory contains files used to package cephcoind/cephcoin-qt
for Debian-based Linux systems. If you compile cephcoind/cephcoin-qt yourself, there are some useful files here.

## cephcoin: URI support ##


cephcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cephcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cephcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/cephcoin128.png` to `/usr/share/pixmaps`

cephcoin-qt.protocol (KDE)


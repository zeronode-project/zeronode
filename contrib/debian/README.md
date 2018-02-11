
Debian
====================
This directory contains files used to package zeronoded/zeronode-qt
for Debian-based Linux systems. If you compile zeronoded/zeronode-qt yourself, there are some useful files here.

## zeronode: URI support ##


zeronode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zeronode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zeronodeqt binary to `/usr/bin`
and the `../../share/pixmaps/colx128.png` to `/usr/share/pixmaps`

zeronode-qt.protocol (KDE)

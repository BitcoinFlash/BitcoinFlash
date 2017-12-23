
Debian
====================
This directory contains files used to package bitcoinflashd/bitcoinflash-qt
for Debian-based Linux systems. If you compile bitcoinflashd/bitcoinflash-qt yourself, there are some useful files here.

## dash: URI support ##


bitcoinflash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinflash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinflash-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

bitcoinflash-qt.protocol (KDE)


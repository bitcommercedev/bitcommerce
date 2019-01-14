
Debian
====================
This directory contains files used to package bitcommerced/bitcommerce-qt
for Debian-based Linux systems. If you compile bitcommerced/bitcommerce-qt yourself, there are some useful files here.

## bitcommerce: URI support ##


bitcommerce-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcommerce-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcommerceqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcommerce128.png` to `/usr/share/pixmaps`

bitcommerce-qt.protocol (KDE)


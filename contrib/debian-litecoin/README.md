
Debian
====================
This directory contains files used to package marscoind/marscoin-qt
for Debian-based Linux systems. If you compile marscoind/marscoin-qt yourself, there are some useful files here.

## litecoin: URI support ##


marscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install marscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your marscoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

marscoin-qt.protocol (KDE)


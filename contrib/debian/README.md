
Debian
====================
This directory contains files used to package ariacoind/ariacoin-qt
for Debian-based Linux systems. If you compile ariacoind/ariacoin-qt yourself, there are some useful files here.

## ariacoin: URI support ##


ariacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ariacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ariacoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ariacoin128.png` to `/usr/share/pixmaps`

ariacoin-qt.protocol (KDE)


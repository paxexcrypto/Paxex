
Debian
====================
This directory contains files used to package paxexd/paxex-qt
for Debian-based Linux systems. If you compile paxexd/paxex-qt yourself, there are some useful files here.

## paxex: URI support ##


paxex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install paxex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your paxexqt binary to `/usr/bin`
and the `../../share/pixmaps/paxex128.png` to `/usr/share/pixmaps`

paxex-qt.protocol (KDE)


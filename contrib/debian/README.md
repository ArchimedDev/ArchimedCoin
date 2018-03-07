
Debian
====================
This directory contains files used to package archimedd/archimed-qt
for Debian-based Linux systems. If you compile archimedd/archimed-qt yourself, there are some useful files here.

## archimed: URI support ##


archimed-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install archimed-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your archimed-qt binary to `/usr/bin`
and the `../../share/pixmaps/archimed128.png` to `/usr/share/pixmaps`

archimed-qt.protocol (KDE)



Debian
====================
This directory contains files used to package qtumlited/qtumlite-qt
for Debian-based Linux systems. If you compile qtumlited/qtumlite-qt yourself, there are some useful files here.

## qtumlite: URI support ##


qtumlite-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qtumlite-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qtumlite-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

qtumlite-qt.protocol (KDE)


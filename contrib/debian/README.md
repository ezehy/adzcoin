
Debian
====================
This directory contains files used to package adzcoind/adzcoin-qt
for Debian-based Linux systems. If you compile adzcoind/adzcoin-qt yourself, there are some useful files here.

## adzcoin: URI support ##


adzcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install adzcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your adzcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/adzcoin128.png` to `/usr/share/pixmaps`

adzcoin-qt.protocol (KDE)


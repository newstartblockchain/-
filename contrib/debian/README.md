
Debian
====================
This directory contains files used to package smilecoind/smilecoin-qt
for Debian-based Linux systems. If you compile smilecoind/smilecoin-qt yourself, there are some useful files here.

## smilecoin: URI support ##


smilecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smilecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smilecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/smilecoin128.png` to `/usr/share/pixmaps`

smilecoin-qt.protocol (KDE)



Debian
====================
This directory contains files used to package surfnoded/surfnode-qt
for Debian-based Linux systems. If you compile surfnoded/surfnode-qt yourself, there are some useful files here.

## surfnode: URI support ##


surfnode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install surfnode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your surfnodeqt binary to `/usr/bin`
and the `../../share/pixmaps/surfnode128.png` to `/usr/share/pixmaps`

surfnode-qt.protocol (KDE)



Debian
====================
This directory contains files used to package synergyworkd/synergywork-qt
for Debian-based Linux systems. If you compile synergyworkd/synergywork-qt yourself, there are some useful files here.

## synergywork: URI support ##


synergywork-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install synergywork-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your synergyworkqt binary to `/usr/bin`
and the `../../share/pixmaps/synergywork128.png` to `/usr/share/pixmaps`

synergywork-qt.protocol (KDE)


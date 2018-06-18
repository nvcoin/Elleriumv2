
Debian
====================
This directory contains files used to package nvd/nv-qt
for Debian-based Linux systems. If you compile nvd/nv-qt yourself, there are some useful files here.

## nv: URI support ##


nv-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nv-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nvqt binary to `/usr/bin`
and the `../../share/pixmaps/nv128.png` to `/usr/share/pixmaps`

nv-qt.protocol (KDE)


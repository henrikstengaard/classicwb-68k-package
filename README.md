# ClassicWB 68K Package

ClassicWB 68K is a feature rich Workbench enhancement by Bloodwych targeted A600 / A500+ with memory expansion using 4/8 colour screenmode using PAL / NTSC / Non-Interlaced 640x256 display.

## Description

ClassicWB 68K Package contains ClassicWB 68K v28 created by Bloodwych from EAB. 

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB 68K can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB 68K package can be installed on any Amiga with Workbench 3.1 and about 35MB free space on a harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-68k-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB 68K package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB 68K package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB 68K files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.

## Screenshots

Screenshots of ClassicWB 68K from http://classicwb.abime.net/classicweb/68kpics.htm.

![ClassicWB 68K 1](screenshots/classicwb_68k_1.png?raw=true)

![ClassicWB 68K 2](screenshots/classicwb_68k_2.png?raw=true)

![ClassicWB 68K 3](screenshots/classicwb_68k_3.png?raw=true)

![ClassicWB 68K 4](screenshots/classicwb_68k_4.png?raw=true)

![ClassicWB 68K 5](screenshots/classicwb_68k_5.png?raw=true)

![ClassicWB 68K 6](screenshots/classicwb_68k_6.png?raw=true)

![ClassicWB 68K 7](screenshots/classicwb_68k_7.png?raw=true)

![ClassicWB 68K 8](screenshots/classicwb_68k_8.png?raw=true)
![Nimuh](https://github.com/Turulomio/nimuh/blob/master/data/nimuh.png)

About this Fork
===============
This a fork of  https://sourceforge.net/projects/nimuh/.

This work is licensed under a Creative Commons Attribution-Noncommercial-Share Alike 2.5 Spain License. 

It was developed originally by the people in AUTHORS. It's last versión was 1.02 and was developed en 2008-02-23.

This fork was made to solve problems compiling in Linux and to recover this good game. If you like it, you can help improving this game.

Installation in Linux
=====================
If you use Gentoo, you can use this [ebuild](https://github.com/Turulomio/myportage/blob/master/games-puzzle/nimuh).

If you use other Linux distribution you must write on the code main directory and write:

`mkdir build`

`cd build`

`cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..`

`make`

`make install`

Execute the game with:
 
`nimuh`

Installation in Windows
=======================
Download and execute the CMake Win32 Installer. Make sure to set the PATH variable during installation

Download and install mingw-w64. The default options work

Add the mingw-w64 programs to the system PATH variable (eg. append this string C:\Program Files (x86)\mingw-w64\i686-4.9.2-posix-dwarf-rt_v4-rev2\mingw32\bin)

Execute the same commands that in Linux installation

Code documentation
==================
We have generated a [Doxygen code documentation](http://turulomio.users.sourceforge.net/doxygen/nimuh/index.html).

Changelog
=========
1.0.4
-----
- Added desktop file for UNIX installation in CMakeList.txt

1.0.3
-----
- Sourceforge project forket in GitHub
- Changed autotools to CMake

1.0.2
-----
- Solve problem with joystick
- Solve error in the third level (english version)

1.0.0
-----
- Stable version


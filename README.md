getpkg
======

Alternative to ABS, uses svn to pull Arch Linux PKGBUILD and associated files.

Usage
======

Simply place this file somewhere and source it in your login shell's init script such as ~/.bashrc or ~/.zshrc like so:
 
 source /path/to/getpkg

Be sure to define a work directory which is where building will occur.  I recommend using an area mounted to tmpfs if you have enough RAM.  If none is defined, the current directory is used.

cTemplate CMake
===============

The purpose of this repository is to provide CMake build scripts for the
[ctemplate library](https://code.google.com/p/ctemplate/).

These scripts have been tested on Visual Studio 2012 and Linux. Multithreading
is disabled in both cases.

Usage
-----

These cmake scripts need to know where the source code of the 'ctemplate'
library is. This is controlled by setting the 'CTEMPLATE_SOURCE_ROOT' variable.

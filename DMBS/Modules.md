DMBS - Dean's Makefile Build System
===================================


Modules Overview
---------------

The following modules are currently included:

 - [ATPROGRAM](ATPROGRAM.md) - Device Programming
 - [AVRDUDE](AVRDUDE.md) - Device Programming
 - [CORE](CORE.md) - DMBS Core Functionality
 - [CPPCHECK](CPPCHECK.md) - Static Code Analysis
 - [DFU](DFU.md) - Device Programming
 - [DOXYGEN](DOXYGEN.md) - Automated Source Code Documentation
 - [GCC](GCC.md) - Compiling/Assembling/Linking with GCC
 - [HID](HID.md) - Device Programming

To use a module, you will need to add the following boilerplate to your
makefile:

    # Include DMBS build script makefiles
    DMBS_PATH   ?= ../DMBS

Which is then used to indicate the location of your DMBS installation, relative
to the current directory.

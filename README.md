# `true` for Windows

*NIX has the most peaceful command ever made: `true`

`true` does not anything, but will always succeed.


## Getting `true`

If you are on *nix, you don't need `true`: you already have it.

If you are on Windows, you have two options:

1. Manually build it:  
    1.1. install VirtualBox  
    1.2. setup a Linux virtual machine.  
    1.3. install [mxe](http://mxe.cc/)  
    1.4. compile `true.exe`  
        - for 32-bit Windows:  
        `/where MXE is installed/usr/bin/i686-w64-mingw32.static-gcc -s -o true.exe true.c`  
        - for 64-bit Windows:  
        `/where MXE is installed/usr/bin/x86_64-w64-mingw32.static-gcc -s -o true.exe true.c`  
2. Download it:  
    2.1. Go [here](https://github.com/mlocati/true-for-windows/releases)
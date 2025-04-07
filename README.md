# dynamixel-source

A clean set of sources for cross-platform.

## Building sources

There are three environments where the dynamixel motors are being used:

* debian (linux64)
* windoze (win64)
* ubuntu-odroid (linux32)

The windoze is rather easy using Visual Studio and works well. Linux is a bit more complicated but more processural than anything else.

Navigate to the folder for the given platform:

_linux64_

For the ARM platform this error will be received: "gcc: error: unrecognized command-line option `-m64`". 

This error occurs when the GCC compiler does not recognize the `-m64` option, which is typically used for 64-bit compilation. If you are compiling on a 64-bit ARM architecture (aarch64), you should remove this option from your compile commands, as it is not applicable in that context.

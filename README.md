# vcp

vcp copies files and directories in a curses interface, with text only
output available. its options and output are similar to BSD's cp while
adding some new features.

# Features

* files copied and left to copy
* data written and total data size
* data being written every second
* two status bars, one showing current file status, the other total status (except with 1 file, both show current)

When output is sent to the console the percentage is displayed and:

* a status bar
* size copied and speed

The config file (vcp.conf.sample) supports a few options,

* color
* screen state
* default flags
* read bufer size

vcp checks the following files in order:

1. /etc/vcp.conf
2. ~/.vcp

options are overwritten as they are read.

# Installation

For installation instructions see [INSTALL.md](./INSTALL.md).

# License

See [LICENSE](./LICENSE).

## Original
Fork from Daniel Sisko (sisko@bsdmail.com)'s http://members.iinet.net.au/~lynx/vcp

## <p align="center">dmenu</p>
personal dmenu build - is an efficient dynamic menu for X.

## Requirements

In order to build dmenu you need the Xlib header files.

## Patches

- [Border](https://tools.suckless.org/dmenu/patches/border/)
- [Center](https://tools.suckless.org/dmenu/patches/center/)
- [Line Height](https://tools.suckless.org/dmenu/patches/line-height/)

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

  ```
    make clean install
    ```

## Running dmenu

See the man page for details.

## Credits

- [Suckless](https://tools.suckless.org/dmenu/)



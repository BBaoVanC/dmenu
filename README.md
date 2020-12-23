# bbaovanc's dmenu fork

## Table of Contents

- [bbaovanc's dmenu fork](#bbaovancs-dmenu-fork)
  - [Table of Contents](#table-of-contents)
  - [Dependencies](#dependencies)
  - [Changes](#changes)
  - [Installation](#installation)

## Dependencies

- [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra)

## Changes

- [Nord theme](https://nordtheme.com)
- Use the bold version of the system monospace font
- Enabled color emoji support (will crash without libxft-bgra)

## Installation

1. Run `make`
2. Run `sudo make install`

By default, `dmenu` will be installed to `/usr/local/bin` and manpages to `/usr/local/share/man/man1`

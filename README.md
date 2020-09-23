# dwm

## Installation

```sh
make clean install
```

Create a `.desktop` file at `/usr/share/xsessions`.
```sh
[Desktop Entry]
Name=dwm
Comment=suckless dwm
Exec=/home/michael/scripts/startdwm
Type=Application
```

## Patches
**Official**
- [center](https://dwm.suckless.org/patches/center/)
- [fakefullscreen](https://dwm.suckless.org/patches/fakefullscreen/)
- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/)
- [pertag](https://dwm.suckless.org/patches/pertag/)
- [movestack](https://dwm.suckless.org/patches/movestack/)
- [Xresources](https://dwm.suckless.org/patches/xresources/)
- [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/)

**Additional**
- Fix border transparency bug for transparent terminal windows [(attribution)](https://github.com/szatanjl/dwm/commit/1529909466206016f2101457bbf37c67195714c8)


## Attribution
Some parts of the source code, mostly the vanitygaps patches for the custom layouts, 
have been copied from [Luke Smith's dwm](https://github.com/LukeSmithxyz/dwm). 
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

**Tip for Chromium**
In order to display the dwm borders on Chromium/Chrome windows, right click on the "title bar" at the top of Chromium and toggle `Use system title bar and borders`.

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

## Keybindings
Not all keybindings are listed here, only the ones that aren't obvious.

**Basic**
- Toggle bar <kbd>super + b</kbd>

**Navigation**
- Increase number of master windows <kbd>super + i</kbd>
- Decrease number of master windows <kbd>super + d</kbd>
- Move focus to next screen <kbd>super + ,</kbd>
- Move focus to previous screen <kbd>super + .</kbd>
- Move active window to next screen <kbd>super + shift + ,</kbd>
- Move active window to previous screen <kbd>super + shift + .</kbd>


**Gaps**
- Toggle gaps <kbd>alt + super + 0</kbd>
- Reset gaps to default <kbd>alt + super + shift + 0</kbd>
- Increase gaps <kbd>alt + super + h</kbd>
- Decrease gaps <kbd>alt + super + l</kbd>

## Attribution
Some parts of the source code, mostly the vanitygaps patches for the custom layouts, 
have been copied from [Luke Smith's dwm](https://github.com/LukeSmithxyz/dwm).
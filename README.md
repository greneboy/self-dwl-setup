# self-dwl-setup
My own `dwl` (`dwm` fork for wayland) setup! It's pretty barebones just the way I like it :D

# Installing

## Dependencies
- `gcc`, `cmake`, `make` and, `ninja` as a compiler.
- `libinput`, `wayland`, `wlroots`, `xkbcommon`, `wayland-protocols`, `pkg-config`, `libxcb`, `libxcb-wm` and, `Xwayland` as the component.

## `dwl`
Go to the `dwl` folder and;
```sh
$ make
# make clean install
```
> For more info: https://codeberg.org/dwl/dwl
## `wmenu`
Also another fork for wayland from `dmenu`. It's written mostly in C++ and so go to the `wmenu` folder and;
```sh
$ meson build
$ ninja -C build
# ninja -C build install
```
> For more info: https://codeberg.org/adnano/wmenu



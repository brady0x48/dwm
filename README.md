# dwm
Personal build of `dwm`, the dynamic tiling window manager from suckless

This keeps track of my custom patches and configurations

## Patches
* [fibonacci](https://dwm.suckless.org/patches/fibonacci/)

## Requirements
* Xorg
* libX11
* libXft
* make
* a C compiler

## Installation
```bash
git clone https://github.com/brady0x48/dwm.git
cd dwm
sudo make clean install
```

### Running
Add `exec dwm` to your `.xinitrc`
```bash
exec dwm
```
> Or use a display manager like a loser

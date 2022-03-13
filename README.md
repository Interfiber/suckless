# suckless
Builds of st, and dmenu

## NOTE
If you want color emojis use the script located [here](https://github.com/Interfiber/dotfiles/blob/main/libxft-bgra-install-void) to install a patched version of libxft

## Build dmenu(void linux)
```bash
cd dmenu
sudo xbps-install -Sy libXinerama-devel libXinerama libXft libXft-devel
sudo make install
```
## Building st(void linux)
```bash
cd st
sudo xbps-install -Sy libXinerama-devel libXinerama libXft libXft-devel
sudo make install
```

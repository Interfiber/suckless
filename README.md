# suckless
Builds of st, and dmenu

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

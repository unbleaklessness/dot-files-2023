# Features

- Uses `NetworkManager` and `nm-applet` to manage network connections.
- Uses `dex` for autostarting `.desktop` files.
- Uses `pactl` to control playback volume with media keys (volume up,
  volume down, mute, mute microphone).
- Uses `xss-lock` to lock the screen before suspend or hibernate.
- Uses `rofi` as a program launcher (a replacement of `dmenu`).
- Uses `blueman` to manage bluetooth devices.

# Applications used

- `flameshot`. Screenshot app.
- `arandr`. For managing multiple displays.
- `guake`.

# To do

## 1

Add installation of `xss-lock`, because it is not installed by
default on Pop OS:
```bash
sudo apt install xss-lock
```

## 2

Download `i3lock-color` executable and place it in `.local/bin/i3lock`.
[i3lock-color](https://github.com/Raymo111/i3lock-color) repository.

## 3 

Add NeoVim configuration. Either place all NeoVim configuration files directly
into this repository, or use a separate repository for NeoVim configs and
include it into this repository as a submodule. 


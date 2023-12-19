# Customize Debian 12

Steps to get Debian 12 to my liking after a clean install of the OS.

Desktop environment: Gnome

## .bash_aliases

Copy the .bash_aliases file to the home directory

```bash
cp .bash_aliases ~/.bash_aliases
```

## Openrazer

Linux drivers for Razer peripherals.

Useful links to install openrazer:

- https://openrazer.github.io/#download

- https://github.com/openrazer/openrazer

- https://software.opensuse.org/download.html?project=hardware%3Arazer&package=openrazer-meta

- https://packages.debian.org/search?keywords=openrazer

Should try to install all the packages via apt.

## Other software

A list of common useful stuff:

- Flameshot (for screenshots): `sudo apt install flameshot`

- [Discord](https://discord.com/download)

- [Rust](https://www.rust-lang.org/tools/install)

- [Go lang](https://go.dev/doc/install)

## Gnome Tweaks

**Mouse Acceleration**

Set mouse acceleration profile to flat (no acceleration):

- Keyboard & Mouse -> Acceleration Profile: Flat

**Center new windows**

- Windows -> Center New Windows (turn on)

## Gnome settings

**Shortcuts**

Settings -> Keyboard -> Keyboard Shortcuts

- Hide all normal windows: super+D

- Launch terminal: ctrl+alt+T (command: `gnome-terminal`)

- Flameshot: ctrl+prtsc (command: `flameshot gui`)

**Hot corner**

Settings -> Multitasking -> Hot Corner: disable

## Gnome extensions

- [Tray Icons](https://github.com/MartinPL/Tray-Icons-Reloaded)

## Wallpapers

On google drive \:)

## Other stuff

blueman icons: /usr/share/icons/hicolor/scalable/status

other icons: /usr/share/icons/Adwaita/16x16/status

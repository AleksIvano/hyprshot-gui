# hyprshot-gui

## Depends

- zenity
- hyprshot
- tesseract
- tesseract-data-eng (download other language packs if you intend to use it for a different languages)

## Install

- Arch Linux (AUR)

Soon

- Manual

```bash
git clone https://github.com/AleksIvano/hyprshot-gui.git && cd hyprshot-gui 
sudo cp ./hyprshot-gui /usr/local/bin/
sudo cp ./hyprshot-gui.desktop /usr/local/share/applications/
```

## Usage

Run `hyprshot-gui.desktop` from menu entry, or run `hyprshot-gui` on terminal.
Select mode, then press OK.

![screenshot](https://github.com/ThatOneCalculator/hyprshot-gui/assets/44733677/aea8f7dc-2af9-4109-9e83-52b09d8fd7c3)

## Floating window in Hyprland config

```
windowrule=float, zenity
```

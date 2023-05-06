# Hyprland Configuration Files by Titus

![Screenshot](https://github.com/RumiAxolotl/hyprland-config/raw/main/screenshot.png)

## Installation

Ensure base-devel is installed before proceeding

### Yay

**Important**: Execute the following commands as a regular user, NOT as root!

```
git clone https://aur.archlinux.org/yay.git
cd yay-bin
makepkg -si
```

### Required Packages

``` bash
yay -S hyprland polkit-gnome ffmpeg neovim viewnior rofi      \
pavucontrol thunar starship wl-clipboard wf-recorder swaybg   \
grimblast-git ffmpegthumbnailer tumbler playerctl             \
noise-suppression-for-voice thunar-archive-plugin kitty       \
waybar-hyprland wlogout swaylock-effects sddm-git pamixer     \
nwg-look-bin dunst   \
brightnessctl hyprpicker-git
```

## Important Notes

- It is recommended to use `archinstall` with Sway as the desktop environment for the base installation.
- `SDDM-GIT` is required to avoid shutdown bugs and delays.
- Configure SDDM for autologin (for security, use `swaylock` at the beginning of the script).
- Replace `xdg-desktop-portal-wlr` with **[xdg-desktop-portal-hyprland-git](https://wiki.hyprland.org/hyprland-wiki/pages/Useful-Utilities/Hyprland-desktop-portal/)**.


## My config base on ChrisTitus! So please take a look at his repository

- ChrisTiTus's Hyprland: **[hyprland-titus](https://github.com/ChrisTitusTech/hyprland-titus)**.
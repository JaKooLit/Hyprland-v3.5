03-June-2024
- Archived in favor of https://github.com/JaKooLit/Arch-Hyprland

# ATTENTION. Arch Hyprland Install Script has been moved to a newer and updated Script. [`CLICK`](https://github.com/JaKooLit/Arch-Hyprland) here for the link.


## Still in BETA stage

### A modified script of my Hyprland-v3 [`Link`](https://github.com/JaKooLit/Hyprland-v3)

![alt text](https://github.com/JaKooLit/Hyprland-v3.1/blob/main/screenshots/Sample-Tokyo-waybar.png "Default")

### ✨ This is only a single theme, single style waybar. No Dark or Light modes.

### ✨ What's new compared to my V3

- As stated above, This is only a single theme, single style waybar. No Dark or Light modes.

-  Can modify the packages easily on the install-hyprland-script
-  Dropped the Mc Mojave theme (apple like) in favor with Tokyo-night-theme
-  using dunst instead of mako
-  Added Tokyo SDDM Theme 
-  Use a wofi-power menu instead of wlogout
-  Added the following: 
    - a. mission center (windows like task manager) - right click on cpu waybar module
    - b. nvtop - right click on temperature waybar module
- gBar initial support

### ✨ to run
> clone this repo by using git. Change directory, make executable and run the script
```bash
git clone https://github.com/JaKooLit/Hyprland-v3.1.git
cd Hyprland-v3.1
chmod +x install-hyprland-v3.1.sh
./install-hyprland-v3.1.sh
```
### ✨ for ZSH and OH-MY-ZSH installation
> do this once installed and script completed; do the following to change the default shell zsh
```bash
chsh -s $(which zsh)
zsh
source ~/.zshrc
```
- reboot or logout
- by default gnzh theme is installed. You can find more themes from this [`OH-MY-ZSH-THEMES`](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)
- to change the theme, edit ~/.zshrc ZSH_THEME="desired theme"

### ✨ Notes
- super h for launching a small help file
- super e to view / edit settings, monitor, keybinds, Environment Variables, etc

### ✨ Roadmap:
- [ ] Install zsh and oh-my-zsh without necessary steps above
- [X] ~~gbar in favor of waybar~~ - however, gBar still fairly new. I suggest waybar to install instead
- [ ] ags in favor of waybar
- [X] ~~Use kitty in favor of foot~~ - Dropped the idea of kitty. Kitty using twice memory compared to foot.

### ✨ Credits
gBar - [`Link`](https://github.com/scorpion-26/gBar)

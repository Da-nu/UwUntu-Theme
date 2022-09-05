# UwUntu-Mint-Theme
- now supports multiple desktop environments
- adds some UwUntu stuff into your desktop environment (preferably cinnamnon)
- it downloads a git clone from https://github.com/Duxi4/UwUntu-Art , https://github.com/vinceliuice/vimix-gtk-themes , and https://github.com/darkomarko42/Marwaita-Icons
# Requirements
- must have git & git-extras packages installed
# Getting dependencies on Mint Ubuntu/Debian
- sudo apt install git git-extras
# Getting dependencies on Arch Linux
- pacman -S cinnamon git
- https://aur.archlinux.org/packages/git-extras
# Install script
- installs vimix and marwaita themes
- does git clone on https://github.com/Duxi4/UwUntu-Art in /tmp/UwUntu-Art
- does git clone on https://github.com/vinceliuice/vimix-gtk-themes in /tmp/vimix-gtk-themes
- does git clone on https://github.com/darkomarko42/Marwaita-Icons in /tmp/Marwaita-Icons
- runs "install.sh -a" in vimix-gtk-themes
- copies over marwaita and marwaita-dark icon themes
- copies wallpapers folder into $HOME/Pictures/UwUntu-Wallpapers
- adds an entry in cinnamon backgrounds thing
# Apply Theme Script
- Aplies a mix of vimix and marwaita themes just like uwuntu
- Applies Wall16.jpg from $HOME/Pictures/UwUntu-Wallpapers as current wallpaper
# Todo
- make installing dependecies easier 
# Thanks to
- Duxi4 (https://github.com/Duxi4) | making UwUntu art repo
- vinceliuice (https://github.com/vinceliuice) | making vimix gtk theme
- darkomarko42 (https://github.com/darkomarko42) | making marwaita icons

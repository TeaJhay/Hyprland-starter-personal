# ML4W Hyprland Starter 1.0.1-Teajhay

**This is a private fork of the original repo from <b>[mylinuxforwork](https://github.com/mylinuxforwork/hyprland-starter)</b>**

The ML4W Hyprland Starter package is the perfect starting point for your Hyprland customization experiments.

To make your start with Hyprland as simple as possible, you can find here an easy to use installation and configuration script.

![image](https://github.com/mylinuxforwork/hyprland-starter/assets/145253254/0e6b3bcd-7b60-4d11-a7c4-7fc3ad708adf)

Watch on YouTube: https://youtu.be/jc-vFSXpZF4

## Requirements

Ths script supports the following distributions:
* Arch Linux (+ Arch Linux based distros e.g., EndeavourOS, Manjaro, ...)
* Fedora Linux
* Nobara Linux
* more to come soon...

## Documentation (Wiki)

You can find the complete documentation of the ML4W Dotfiles in the Wiki. <b>[Open the Wiki here](https://github.com/mylinuxforwork/hyprland-starter/wiki)</b>

## Installation

You can install the Hyprland Starter on real hardware (bare metal) or test it first in a Virtual Machine based on QEMU/KVM with activated 3D acceleration.

Just copy the following command into your terminal and execute.

```
bash <(curl -s https://raw.githubusercontent.com/Teajhay/hyprland-starter-personal/main/setup.sh)
```

> Hyprland does not officially support NVIDIA hardware. But many users have reported a successful installation. Please read: https://wiki.hyprland.org/Nvidia/

## Packages

The script will install the following packages and the corresponding configurations:

- Window Manager: hyprland 
- Status Bar: waybar 
- Launcher: rofi-wayland 
- Browser: brave<sub>2</sub>
- Terminal: alacritty 
- Notification Service: dunst 
- File Manager: Thunar
- xdg-desktop-portal-hyprland 
- qt5-wayland 
- qt6-wayland 
- Lock screen: hyprlock
- themes: ngw-look<sub>1</sub>
- gvfs-smb<sub>1</sub>
- gnome-themes-extra<sub>1</sub>
- man-db<sub>1</sub>
- links<sub>1</sub>
- vesktop<sub>1</sub>
- brave-bin<sub>1</sub>

You can find all shipped configurations here: https://github.com/Teajhay/hyprland-starter-personal/tree/main/dotfiles

<sub>1 - these packages differ from the original repo and are installed for my perosnal liking</sub>

<sub>2 - originally firefox, firefox is still installed as a backup browser but brave is default</sub>
## Key Bindings

The following custom key bindings are enabled (can be customized in ~/.config/hypr/hyprland.conf)

- <kbd>SUPER</kbd> + <kbd>RETURN</kbd> to start terminal alacritty
- <kbd>SUPER</kbd> + <kbd>Q</kbd> to quit an application
- <kbd>SUPER</kbd> + <kbd>B</kbd> to start browser
- <kbd>SUPER</kbd> + <kbd>M</kbd> to exit Hyprland
- <kbd>SUPER</kbd> + <kbd>E</kbd> to start filemanager
- <kbd>SUPER</kbd></kbd> + <kbd>SPACE</kbd> to start launcher rofi
- <kbd>SUPER</kbd> + <kbd>T</kbd> to toggle floating
- <kbd>SUPER</kbd> + <kbd>F</kbd> to toggle fullscreen
- <kbd>SUPER</kbd> + <kbd>1-9</kbd> to switch workspaces
- more key bindings in ~/.config/hypr/conf/binds.conf

or after the installation with right mouse click on Apps in the status bar.

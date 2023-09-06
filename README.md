# HyprLand
<b> Minimal HyprLand Setup W/ ArchLinux </b>

* Discover the easiest way to set up your ArchLinux system for a minimalistic HyprLand experience.
*   After Booting into HyprLand, Open terminal and install Aur Helper called Paru

<b> ArchInstall </b>

With ArchInstall Script Install Archlinux on bare metal.

<b> Install Paru (Aur Helper)</b>

```
* git clone https://aur.archlinux.org/paru-bin.git
```
* cd paru-bin

* makepkg -Si


<b>Install Dependencies / Packages </b>

```
paru -S imv wlogout brightnessctl wl-clipboard kooha waybar-hyprland swaylock-effects wofi pavucontrol pamixer file-roller htop ttf-font-awesome ttf-jetbrains-mono-nerd noto-fonts-emoji hyprpaper linux-headers alsa-utils
```




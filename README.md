# HyprLand
<b> Minimal HyprLand Setup W/ ArchLinux </b>

 Discover the easiest way to set up your ArchLinux system for a minimalistic HyprLand experience.


<b> ArchInstall </b>
* Using ArchInstall Script Install Archlinux on bare metal.
* After Booting into HyprLand, Open terminal and install Aur Helper called Paru


<b> Install Paru (Aur Helper)</b>

```
git clone https://aur.archlinux.org/paru-bin.git
```
* cd paru-bin

* makepkg -si


<b>Install Dependencies / Packages </b>

```
paru -S imv wlogout brightnessctl wl-clipboard waybar-hyprland swaylock-effects wofi pavucontrol pamixer file-roller htop ttf-font-awesome ttf-jetbrains-mono-nerd noto-fonts-emoji hyprpaper linux-headers alsa-utils less wlroots vlc gnu-free-fonts thunar noto-fonts ttf-bitstream-vera ttf-croscore ttf-dejavu ttf-droid ttf-ibm-plex ttf-liberation udiskie
```




## UKUI

UKUI is a desktop environment for Linux distributions and other UNIX-like operating systems. It provides a simpler and more enjoyable experience for browsing, searching and managing your computer.

![ukui3.0](https://www.ukui.org/images/feature_li1.png)

## Homepage
[UKUI Homepage](https://www.ukui.org)

## Install

### Ubuntu
```
sudo apt install ukui-desktop-environment
```

Or you can get the latest version by:
```
$ sudo add-apt-repository ppa:ubuntukylin-members/ukui3.0
$ sudo apt upgrade
```

### Debian buster (UKUI 2.0)
```
sudo apt install ukui-session-manager ukui-menu ukui-control-center ukui-settings-daemon ukui-window-switch ukui-media ukui-power-manager peony ukui-themes ukui-greeter kylin-display-switch
sudo pip3 install requests
gsettings set org.mate.interface gtk-theme 'ukui-black'
gsettings set org.mate.interface icon-theme 'ukui-icon-theme'
```

### Debian unstable (UKUI 3.0)
```
sudo apt install ukui-session-manager ukui-menu ukui-control-center ukui-settings-daemon ukui-window-switch ukui-media ukui-power-manager peony ukui-themes ukui-greeter kylin-display-switch ukui-sidebar qt5-ukui-platformtheme kylin-nm
gsettings set org.mate.interface gtk-theme 'ukui-black'
gsettings set org.ukui.style icon-theme-name 'ukui-icon-theme-default'
```

### Arch
```
sudo pacman -S ukui xorg-server
sudo systemctl enable lightdm
```

### Fedora
In progress...

### openEuler
In progress...

## Upgrade
```
sudo apt update
sudo apt upgrade
```

## Issues
[UKUI issue](www.github.com/ukui/ukui-desktop-environment/issues)

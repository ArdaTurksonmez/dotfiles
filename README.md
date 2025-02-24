# dotfiles

**requirements: xorg/X11, rofi, alacritty, flameshot, sxhkd, picom, xclip, ttf-iosevka-nerd, ttf-jetbrains-mono-nerd, deadbeef, feh, zsh, ly**

Arch:
```
sudo pacman -S xorg xorg-xinit rofi alacritty flameshot sxhkd feh picom xclip zsh ly ttf-iosevka-nerd ttf-jetbrains-mono-nerd
yay/paru -S deadbeef
```

**Warning:**
* Do not run this script under root privileges!
* Moving this directory after installation may cause some things to break

**Install:**

```
$ git clone https://github.com/ArdaTurksonmez/dotfiles
$ cd dotfiles
$ sudo chmod +x install 
$ ./install
```

After rebooting make sure to go change the launch option from shell to xinitrc

Two controls to keep in mind prior to launching the window manager are:
* Terminal - (ModKey (Windows Key) + Shift + Enter/Return)
* Application Launcher - (Modkey (Windows Key) + P)

The rest of the controls can be found in the config.def.h of the dwm folder


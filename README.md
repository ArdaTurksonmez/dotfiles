# dotfiles

**requirements: xorg/X11, rofi, alacritty, flameshot, sxhkd, ttf-iosevka-nerd, ttf-jetbrains-mono, deadbeef, feh, zsh, ly**

Arch:
```
sudo pacman -S xorg xorg-xinit rofi alacritty flameshot sxhkd feh zsh ly
yay/paru -S all-repository-fonts deadbeef
```

**Warning:**
do not run this script under root privileges!
run this script in the home directory of the chosen user.

**Install:**

```
$ git clone https://github.com/ArdaTurksonmez/dotfiles.git
$ cd dotfiles
$ sudo chmod +x install 
$ ./install
```

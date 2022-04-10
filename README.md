# **Arch-Darwin**
An Arch linux splash screen for plymouth
<img src="./arch-darwin.gif" alt="arch-darwin">

# Installation from AUR
- Install and setup [Plymouth](https://wiki.archlinux.org/title/plymouth)
- Install [plymouth-theme-arch-darwin](https://aur.archlinux.org/packages/plymouth-theme-arch-darwin) package from the [AUR](https://aur.archlinux.org)
```
$ yay -S plymouth-theme-arch-darwin
```
(assuming you have yay as your AUR helper)

# Manual Installtion
```
$ git clone https://github.com/armoredvortex/plymouth-theme-arch-darwin
$ sudo mv ./plymouth-theme-arch-darwin /usr/share/plymouth/themes/arch-darwin
```
# Setup
```
# The theme should be listed here
$ sudo plymouth-set-default-theme -l

# Change plymouth theme
$ sudo plymouth-set-default-theme -R arch-darwin
```

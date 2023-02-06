# dotfiles
![Screenshot](/screenshot.png)

### Table of Contents
- [General info](#general-info)
- [Dependencys](#dependencys)
- [Usage](#usage)
  - [Awesome](#awesome)
  - [Polybar](#polybar)
- [Polybar Modules](#polybar-modules)

## General Info
My config files for Awesomewm and Polybar

## Dependencys
- awesome
- polybar
- termite(aur)
- nitrogen
- pulseaudio
- dmenu

## Usage
first of all install dependencys.

arch base : 
```
sudo pacman -S awesome polybar nitrogen pulseaudio
```

#### Awesome
copy `awesome/ru.lua` file to `$HOME/.config/awesome`. if folder not exist make one.

#### Polybar
copy `polybar` folder to `$HOME/.config/polybar`. if folder not exist make one.

## Polybar Modules
for add/remove module to your bar, edit `polybar/modules.ini` file

to add new module first write your module in `polybar/modules` folder, add path of your module in `polybar/include-modules.ini`. finally add name of your module in `polybar/modules.ini`.

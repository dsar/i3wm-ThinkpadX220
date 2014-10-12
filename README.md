i3wm-ThinkpadX220
=================

My i3wm configuration for Thinkpad X220 (laptop)

~/.xinit file
================
Add the following lines in the end of your **.xinit** file

```sh
# this let you toggle between different keyboard layouts
setxkbmap -option grp:alt_shift_toggle gb,el

# set background image
feh --bg-scale ~/.config/background.jpg

# execute i3 window manager
exec i3
```


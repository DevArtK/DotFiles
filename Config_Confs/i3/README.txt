[i3]
# I3 Config Location:
	~/.config/i3/conf
# I3Exit
  ~/.config/i3/i3exit

# I3 Status Config Location
	~/.config/i3status/config

# I3 Gaps (Radius)
  - git clone https://github.com/terroo/i3-radius
  - cd i3-radius && sh build.sh

[Dunst]
# Dunst Config Location :
  ~/.config/dunst/dunstrc


[Poly Bar]
Default polybar config : /usr/share/doc/polybar/config
# PolyBar Config Location:
	~/.config/polybar/config

# Polybar Launch Script
  ~/.config/polybar/launch.sh

# Polybar Scripts Directory
  ~/.config/polybar/scripts

Inside i3's config
exec_always --no-startup-id $HOME/.config/polybar/launch.sh


# Polybar Scripts :
https://github.com/polybar/polybar-scripts


# Wallpaper Finder with specific colors
https://labs.tineye.com/multicolr/#colors=222D33,382e71;weights=97,3;tags=wallpaper;

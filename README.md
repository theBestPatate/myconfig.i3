# Installation

Git clone this repo in your ~/.config/i3
```bash
git clone https://github.com/theBestPatate/myconfig.i3.git ~/.config/i3
```

Install the following depencies
# Dependencies

> Xorg and I3 
# Optional
> I3 Gaps
> Polybar

I don't use any bar but I will leave this here just in case.

You might need this if you have a multiple monitor config 
 
```bash
if type "xrandr"; then
  for m in $(xrandr --query | grep " connected" | cut -d" " -f1); do
    MONITOR=$m polybar --reload toph &
  done
else
  polybar --reload toph &
fi
```
You can save it here: ~/.config/polybar/launch_polybar.sh 

> rofi

> `feh` command to setup your wallpaper

> Picom (If you want transparent windows,rounded corners,blur...)

Theres's multiple forks of the original projects with different capabilities
Refer to [https://www.reddit.com/r/i3wm/comments/gus1aa/which_fork_of_picom_is_best/](this reddit thread) for more details

# Fonts

[https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/UbuntuMono.zip](UbuntoMono Nerd font)


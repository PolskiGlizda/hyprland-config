# Hyprland config

Basic Hyprland config focused on simplicity and easy of use.

![screenshot](https://github.com/PolskiGlizda/hyprland-config/blob/master/2023-11-26_040818.png)

## Requirements

 - [Waybar](https://github.com/Alexays/Waybar)
 - [Kitty](https://github.com/kovidgoyal/kitty)
 - [PCManFM](https://github.com/lxde/pcmanfm)
 - [Polkit KDE Authentication Agent](https://invent.kde.org/hexchain/polkit-kde-agent-1)
 - [Wofi](https://hg.sr.ht/~scoopta/wofi)
## Instalation

1. Install all requirements 
2. Run:
``` bash
# backup old config
    mv ~/.config/hypr{,.bac}
# download new config
    git clone https://github.com/PolskiGlizda/hyprland-config ~/.config/hypr
```
3. Open `~/.config/hypr/hyprland.conf` using a text editor
4. Set your monitors parameters
``` conf
    monitor=name,resolution@frequency,position,scale
```
NOTE: if you want to setup multiple monitors just add multiple lines like one presented above

## Key binds

$mainMod = SUPER

| bind | description |
| ---- | ----------- |
| $mainMod + Return | Launch terminal emulator(kitty by default) |
| $mainMod + C | Kill active window |
| $mainMod + M | Exit Hyprland |
| $mainMod + E | Launch file manager(PCManFM by default) |
| $mainMod + R | Launch menu program(wofi) |
| $mainMod + V | Make active window floating |
| $mainMod + P | Activate pseudotiling |
| $mainMod + J | Toggle Split |
| $mainMod + T | Launcg browser(Firefox by default) |
| $mainMod + ARROWS | Move focus |
| $mainMod + [0-9] | Switch workspaces |
| $mainMod + SHIFT + [0-9] | Move active window to another workspace |
| $mainMod + SCROLL | Scroll through existing worspaces |
| $mainMod + LMB | Move windows by dragging |
| $mainMod + RMB | Resize windows by dragging |
| PrtSc | Take a screenshot |
| Volume up (function key) | Increase volume on default sink by 5% |
| Volume down (function key) | Decrease volume on default sink by 5% |
| Audio mute | Toggle mute on default sink |
| Brightness up (function key) | Increase brightness by 10% |
| Brightness down (function key) | Decrease brughtness by 10% |
| Audio play (function key) | Toggle player play/pause |
| Audio next (function key) | Skip to next track |
| Audio previous (function key) | Skip to previous track |
| Calculator (function key) | Launch calcuator(speedcrunch by default) |

## For learning how to configure
If you'd like to expand this config or personalize it I highly recommend [hyprland wiki](https://wiki.hyprland.org/)

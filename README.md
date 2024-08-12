# DunstThree 
DunstThree is a script that sends notifications through dunst ; meant to be used with dunst + any window manager like i3, hyprland or sway.

![](volhigh.png)

![](vollow.png)

![](brightness.png)

## Manual Installation 
1. Copy this repo into your ~/.config/dunstthree

2. Map script to your i3 config example :
```
 # Volume
bindsym XF86AudioMute exec ~/.config/i3/dunstthree/dunstthree.sh mute 
bindsym XF86AudioRaiseVolume exec ~/.config/i3/dunstthree/dunstthree.sh vup 
bindsym XF86AudioLowerVolume exec ~/.config/i3/dunstthree/dunstthree.sh vdown 
# Brightness 
bindsym XF86MonBrightnessUp exec --no-startup-id ~/.config/i3/dunstthree/dunstthree.sh bup
bindsym XF86MonBrightnessDown exec --no-startup-id  ~/.config/i3/dunstthree/dunstthree.sh bdown

```

## Dependencies
dunst \
amixer \
xbacklight \

Make sure your dunst is updated and dunstify comand works.

			
##
<a href="https://www.buymeacoffee.com/acidburn" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## Monero <img src="https://www.getmonero.org/press-kit/symbols/monero-symbol-1280.png" width="60" height="60">
43Sxiso2FHsYhP7HTqZgsXa3m3uHtxHQdMeHxECqRefyazZfpGVCLVsf1gU68jxJBo1G171AC181q1BqAUaG1m554MLsspG

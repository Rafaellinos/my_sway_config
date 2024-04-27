# Sway

- Make sure u are in wayland

```
yay sway swaybg polkit wezterm
```

## Start

- Use wofi to launch programs
- modify ~/.config/sway/config file
- change $mod to Mod1 (alt)

## basic commands


## menu

```bash
yay wofi
```

- add: `set $menu wofi --show run`
- press Mod + d to open

## Top bar

```bash
yay  
```

```config
bar {
   swaybar_command waybar 
}
```

## Terminal

- change set `$term` for wezterm


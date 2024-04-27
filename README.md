# Sway

- Make sure u are in wayland

## First steps

Install git and dependencies needed

```bash
sudo pacman -S --needed git base-devel
```

Install yay (To install software from both oficial repository and Arch User Repository AUR)

```bash
git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```

Install sway, necessary dependencies plus wezterm (terminal).

```
yay sway swaybg polkit wezterm
```

## Start

- Use wofi to launch programs
- modify ~/.config/sway/config file
- change $mod to Mod1 (alt)

## basic commands


- Mod1 = alt
- reload sway = mod + shift + c
- close current window = mod + shift + q (kill)
- move between workspaces = mod+shift+<workspace number>

## menu

```bash
yay wofi
```

- modify the sway/config file = `set $menu wofi --show run`
- press Mod + d to open

## Top bar

```bash
yay waybar ttf-font-awesome 
```

```config
bar {
   swaybar_command waybar 
}
```

```bash
mkdir ~/.config/waybar && cp /etc/xdg/waybar/* ~/.config/waybar/
```

## Terminal

- change set `$term` for wezterm

## Visual configuration



## Sources

- https://www.youtube.com/watch?v=QAmTUkzpIiM

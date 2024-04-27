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

## menu

```bash
yay wofi
```

- modify the sway/config file = `set $menu wofi --show run`
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


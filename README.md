# Hypr-Dots

A minimal producitve enviroment

## Installation

1. Gewünschte Konfigurationen von xdg_config nach "$HOME/.config/" verschieben.

Wenn alle gewünscht sind kann auch Stow genutzt werden, um symbolische links automatisch zu erstellen:

```
cd xdg_config

stow . -t $HOME/.config/
```

### Font

Alacritty ist auf IosevkaNerdFont eingestellt, diese können sie selber installieren, oder die .ttf auf dem font-Ordner nach $HOME/.local/share/fonts/ kopieren


### Tools

- wofi
- wlogout
- alacritty
- waybar

```
pacman -S wofi alacritty waybar

yay -S wlogout
```

## Configuration

### SDDM

### Hyprland

#### Color Themes

#### Wallpaper

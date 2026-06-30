# Hyprlock themes

> Variant 1
![Overview](https://github.com/Normoxd/Hyprlock-themes/blob/main/overview/v1.png?raw=true)

> Variant 2
![Overview](https://github.com/Normoxd/Hyprlock-themes/blob/main/overview/v2.png?raw=true)

# ⚙️ Installation

1. Clone the repo
``` 
git clone https://github.com/Normoxd/Hyprlock-themes
cd Hyprlock-themes
```
2. Install the provided fonts
```
cd fonts
mv AdwaitaSans-Regular.ttf ~/.local/share/fonts
mv LondrinaOutline-Regular.ttf ~/.local/share/fonts
mv "Product Sans Bold.ttf" ~/.local/share/fonts
mv "Product Sans Regular.ttf" ~/.local/share/fonts
cd ..
```

3. Move the themes to the hyprland config folder
```
mv hyprlock-themes ~/.config/hypr
```

4. Backup the old hyprlock config (Optional)
```
cd ~/.config/hypr
mv hyprlock.conf hyprlock.conf.backup
```

5. Replace the hyprlock config with any theme variant you like

> Variant 1
```
cp ~/.config/hypr/hyprlock-themes/hyprlock-v1.conf ~/.config/hypr
mv ~/.config/hypr/hyprlock-v1.conf ~/.config/hypr/hyprlock.conf
```

> Variant 2
```
cp ~/.config/hypr/hyprlock-themes/hyprlock-v2.conf ~/.config/hypr
mv ~/.config/hypr/hyprlock-v2.conf ~/.config/hypr/hyprlock.conf
```

6. Copy over your profile picture as `~/.config/hypr/user.png`

<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/repo-banners/cybr-yazi-banner.png" height=200px/>

# Showcase
<img src="https://raw.githubusercontent.com/cybrcore/cybrcore/refs/heads/main/assets/showcase/cybr-yazi.png"/>
<p align="center">
  <em>yazi ↗ (top-left: image folder; bottom-left: music folder; right: directory and file preview)</em>
</p>

# Steps
## 0. Before you start
- Make sure [Geist Mono Nerd Font](https://www.nerdfonts.com/font-downloads) is installed, you can do that from terminal with:
```bash
curl -L https://github.com/ryanoasis/nerd-fonts/releases/latest/download/GeistMono.zip -o GeistMono.zip
mkdir -p ~/.local/share/fonts
unzip GeistMono.zip -d ~/.local/share/fonts/GeistMono
fc-cache -fv
```
- Make sure kitty is installed: `sudo pacman -S kitty` and [cybrcore theme](https://github.com/cybrcore/cybr-kitty) is applied
- Make sure yazi is installed: `sudo pacman -S yazi`
- See [Installation Guide](https://github.com/cybrcore/cybrdots/blob/main/INSTALL.md) if you're coming from [cybr-hyprland](https://github.com/cybrcore/cybr-hyprland) and haven't set up prerequisites yet
- [yazi Github](https://github.com/sxyazi/yazi)

## 1. Create theme file
```sh
$EDITOR ~/.config/yazi/theme.toml
```
## 2. Insert [cybrcore theme](theme.toml)
## 3. Restart yazi
```sh
killall yazi && yazi
```

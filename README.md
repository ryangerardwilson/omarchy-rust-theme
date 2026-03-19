# rust

A local Omarchy theme that adds a warm rust family to the existing blue and
mono variants, with a parchment light mode and copper accents.

This repository follows Omarchy's extra-theme layout:

- Theme files live at the repository root.
- Wallpapers live in `backgrounds/`.
- The repo name uses the `omarchy-<theme>-theme` pattern so
  `omarchy-theme-install` resolves the theme name correctly.

## Install

```bash
omarchy-theme-install https://github.com/ryangerardwilson/omarchy-rust-theme.git
```

If you clone it manually:

```bash
git clone https://github.com/ryangerardwilson/omarchy-rust-theme.git ~/.config/omarchy/themes/rust
omarchy-theme-set rust
```

## Included Overrides

- `colors.toml` for Omarchy-generated theme files
- `alacritty.toml`, `btop.theme`, `hyprland.conf`, `mako.ini`, and `tmux.conf`
  for the rust light-mode UI treatment
- `rust.tmTheme`, `neovim.lua`, `light.mode`, `zathurarc`, and `swayimgrc`
  for editor and app alignment
- `icons.theme` and `vscode.json` for app-specific theme selection
- `wallpaper.txt`, `wallpaper.svg`, `preview.png`, and `backgrounds/0-rust.png`

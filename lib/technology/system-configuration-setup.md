---
id: system_configuration_setup
aliases: [202507082365]
tags: []
type: reference
topic: personal
created: 2025-07-08
uid: 202507082365
---

# System Configuration Setup

## Overview

Personal development environment configuration managed through git-synced dotfiles with symlinks.

**Repository**: https://github.com/Askirom/Askr.System_Configuration.git

## Quick Setup (New Machine)

```bash
# Clone repository
git clone https://github.com/Askirom/Askr.System_Configuration.git ~/dotfiles
cd ~/dotfiles
```

# Run automated setup

```bash
./install.sh
```

## Manual Setup Process

### 1. Create Dotfiles Repository Structure

```bash
mkdir ~/dotfiles/{neovim,wezterm,zellij,homebrew,scripts}
cd ~/dotfiles
git init
```

### 2. Move Configs to Repository

```bash
# Copy configurations
cp -r ~/.config/nvim/* ~/dotfiles/neovim/
cp ~/.wezterm.lua ~/dotfiles/wezterm/wezterm.lua
cp -r ~/.config/zellij/* ~/dotfiles/zellij/

# Generate Brewfile
brew bundle dump --file=~/dotfiles/homebrew/Brewfile
```

### 3. Create Symlinks

```bash
# Backup originals
mv ~/.config/nvim ~/.config/nvim.backup
mv ~/.wezterm.lua ~/.wezterm.lua.backup
mv ~/.config/zellij ~/.config/zellij.backup

# Create symlinks
ln -s ~/dotfiles/neovim ~/.config/nvim
ln -s ~/dotfiles/wezterm/wezterm.lua ~/.wezterm.lua
ln -s ~/dotfiles/zellij ~/.config/zellij
```

### 4. Test Configuration

```bash
# Test each application loads properly
nvim test.md                    # Check Neovim config
wezterm show-config             # Verify WezTerm
zellij setup --check           # Validate Zellij
```

## How Symlinks Work

- Edit configs normally (e.g., `~/.config/nvim/init.lua`)
- Changes automatically appear in git repository
- Commit from `~/dotfiles/` directory
- Applications read from symlinked locations transparently

## Configuration Locations

- **Neovim**: `~/.config/nvim/` → `~/dotfiles/neovim/`
- **WezTerm**: `~/.wezterm.lua` → `~/dotfiles/wezterm/wezterm.lua`
- **Zellij**: `~/.config/zellij/` → `~/dotfiles/zellij/`
- **Homebrew**: Apps list in `~/dotfiles/homebrew/Brewfile`

## Troubleshooting

### Symlink Issues

```bash
# Check if symlink exists and points correctly
ls -la ~/.config/nvim
ls -la ~/.wezterm.lua
ls -la ~/.config/zellij

# Should show: [link] -> [dotfiles path]
```

### Config Not Loading

```bash
# Remove broken symlink and recreate
rm ~/.config/nvim
ln -s ~/dotfiles/neovim ~/.config/nvim
```

### Restore from Backup

```bash
# If something breaks, restore original
rm ~/.config/nvim
mv ~/.config/nvim.backup ~/.config/nvim
```

### Update Repository

```bash
cd ~/dotfiles
git add .
git commit -m "Update configurations"]
git push
```

## Repository Contents

```
~/dotfiles/
├── neovim/           # Complete Neovim configuration
├── wezterm/          # WezTerm config file
├── zellij/           # Zellij configuration
├── homebrew/         # Brewfile with app list
├── scripts/          # Custom utilities
├── install.sh        # Automated setup script
└── README.md         # Basic repository info
```

## Additional Setup (Manual)

After running setup, manually configure:

- GitHub SSH keys
- Git user credentials: `git config --global user.name "Your Name"`
- Application-specific preferences not in dotfiles

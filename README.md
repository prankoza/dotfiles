# dotfiles

My personal configuration files for Void Linux with dwm.

## Contents

- **alacritty** — terminal emulator config
- **nvim** — text editor config (comming soon)
- **dwm** — window manager (coming soon)
- **dwmblocks** — status bar (coming soon)

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/prankoza/dotfiles.git ~/dotfiles
cd ~/dotfiles
```

### 2. Symlink configs

```bash
mkdir -p ~/.config/alacritty
ln -sf ~/dotfiles/alacritty/alacritty.toml ~/.config/alacritty/alacritty.toml
```

### 3. Install packages

- **Void linux** - sudo xbps-install -S alacritty
- **Debian** - sudo apt install alacritty
- **Arch Linux Based** - sudo pacman -S alacritty
- **Gentoo Linux** - sudo emerge -a alacritty

### 4. Enjoy!

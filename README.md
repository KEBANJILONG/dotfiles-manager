# 🛠️ Dotfiles Manager

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux-lightgrey.svg)

**Sync your shell configs, aliases, and dev settings across machines**

</div>

## 🚀 Quick Start

```bash
# Install
curl -fsSL https://raw.githubusercontent.com/KEBANJILONG/dotfiles-manager/main/install.sh | bash

# Sync to new machine
dotfiles sync
```

## ✨ Features

- **Cross-machine sync** - One config, all your devices
- **Safe backups** - Automatic backup before any changes
- **Selective sync** - Choose what to sync per machine
- **Version control** - Track changes with Git

## 📋 Managed Files

- `.bashrc` / `.zshrc` - Shell configuration
- `.gitconfig` - Git settings
- `.vimrc` / `init.vim` - Editor config
- `.ssh/config` - SSH settings
- Custom aliases and functions

## 🔧 Commands

```bash
dotfiles sync          # Sync configs to this machine
dotfiles backup        # Create backup
dotfiles restore       # Restore from backup
dotfiles add <file>    # Add file to management
dotfiles list          # List managed files
```

## 📄 License

MIT

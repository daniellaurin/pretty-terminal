# Server Terminal Setup

This repository contains my personal shell configuration for a productive terminal environment (not POSIX compliyant)

## Overview

This setup provides a modern, feature-rich terminal experience with Fish shell, Tmux, and various productivity tools.

![Terminal Preview](https://your-image-link-here.png)

## Installation

Simply run the installation script:

```bash
git clone
./install.sh
```

## Components

| Component                                                                | Description                                  | Purpose                             |
| ------------------------------------------------------------------------ | -------------------------------------------- | ----------------------------------- |
| [Fish Shell](https://fishshell.com/)                                     | User-friendly shell with syntax highlighting | Primary shell                       |
| [Fisher](https://github.com/jorgebucaran/fisher)                         | Plugin manager for Fish                      | Manage Fish plugins                 |
| [Tide](https://github.com/IlanCosman/tide)                               | Modern Fish prompt                           | Customizable prompt with git status |
| [Fish Logo](https://github.com/laughedelic/fish_logo)                    | ASCII art fish logo                          | Custom greeting                     |
| [Colored Man Pages](https://github.com/patrickf1/colored_man_pages.fish) | Colorized man pages                          | Improved readability                |
| [Neovim](https://neovim.io/)                                             | Modern Vim-based text editor                 | Text editing                        |
| [Ranger](https://github.com/ranger/ranger)                               | File manager with VI key bindings            | File browsing                       |
| [Bat](https://github.com/sharkdp/bat)                                    | Cat clone with syntax highlighting           | File viewing                        |
| [Neofetch](https://github.com/dylanaraps/neofetch)                       | System information tool                      | System info display                 |
| [Tmux](https://github.com/gpakosz/.tmux)                                 | Terminal multiplexer                         | Session management                  |

## Features

- Fish shell with Vi key bindings
- Custom greeting with colorful fish logo
- Syntax highlighting for commands and files
- Enhanced productivity with Tmux session management
- Modern development tools (Neovim, Ranger, Bat)
- System information display with Neofetch

## Configuration Details

The setup includes:

- Fish shell with Vi key bindings for efficient navigation
- Custom aliases for improved workflows
- Tmux configuration from the popular gpakosz/.tmux repository
- Various Fish plugins for enhanced functionality

## Customization

You can customize this setup by modifying:

- `~/.config/fish/config.fish` for Fish shell settings
- `~/.tmux.conf.local` for Tmux customization

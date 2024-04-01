# github.com/carquipe/dotfiles

dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

## Install

This'll install Homebrew and chezmoi. After installation `chezmoi` will be initialized.

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/carquipe/dotfiles/master/install.sh)"
```

## Manual install

Prerequisite: Homebrew & chezmoi

```shell
# Setup
chezmoi init https://github.com/carquipe/dotfiles.git

# Configure ~/.config/chezmoi/chezmoi.toml
chezmoi init
```

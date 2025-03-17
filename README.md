# LunarVim Setup

## Install Neovim

```bash
sudo apt update
sudo apt install -y neovim
```

Ensure the neovim version `nvim --version` is >=0.8.

## Add config

```bash
mkdir ~/.config && cd ~/.config
git@github.com:shaunbarney/LunarVimConfig.git lvim
```

## Install LunarVim

```bash
LV_BRANCH='release-1.3/neovim-0.9' bash <(curl -s https://raw.githubusercontent.com/LunarVim/LunarVim/release-1.3/neovim-0.9/utils/installer/install.sh)
```

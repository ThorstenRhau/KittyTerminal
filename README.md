# KittyTerminal

<!--toc:start-->

- [KittyTerminal](#kittyterminal)
  - [Installing on macOS with homebrew](#installing-on-macos-with-homebrew)
  - [Clone repository](#clone-repository)
  - [Aliases](#aliases)
  <!--toc:end-->

This repo is intended for my personal use, it is public for easier cloning.

## Installing on macOS with homebrew

```zsh
brew install kitty
```

## Clone repository

```zsh
git clone https://github.com/ThorstenRhau/KittyTerminal.git ~/.config/kitty
```

## Aliases

Clone https://github.com/folke/tokyonight.nvim.git.
Below is a excerpt of my fish configuration

```fish
if test -d "$HOME/git/tokyonight.nvim"
  alias night_kitty='ln -sf $HOME/git/tokyonight.nvim/extras/kitty/tokyonight_night.conf $HOME/.config/kitty/current-theme.conf'
  alias day_kitty='ln -sf $HOME/git/tokyonight.nvim/extras/kitty/tokyonight_day.conf $HOME/.config/kitty/current-theme.conf'
end
```

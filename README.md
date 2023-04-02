# KittyTerminal

<!--toc:start-->

- [KittyTerminal](#kittyterminal)
  - [Installing on macOS with homebrew](#installing-on-macos-with-homebrew)
  - [Clone repository](#clone-repository)
  - [Aliases to in to .zshrc](#aliases-to-in-to-zshrc)
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

## Aliases to in to .zshrc

For the _night_ and _day_ aliases to work you need to clone https://github.com/EdenEast/nightfox.nvim and add something like the text below to your shells rc-file. The example below is for the fish-shell.

```fish
if test -d "$HOME/git/nightfox.nvim"
  alias night='ln -sf $HOME/git/nightfox.nvim/extra/nightfox/nightfox_kitty.conf $HOME/.config/kitty/current-theme.conf'
  alias day='ln -sf $HOME/git/nightfox.nvim/extra/dayfox/nightfox_kitty.conf $HOME/.config/kitty/current-theme.conf'
end
```

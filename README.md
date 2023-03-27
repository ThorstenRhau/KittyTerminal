# KittyTerminal

<!--toc:start-->

- [KittyTerminal](#kittyterminal)
  - [Installing on macOS with homebrew](#installing-on-macos-with-homebrew)
  - [Clone repository](#clone-repository)
  - [Aliases to in to .zshrc](#aliases-to-in-to-zshrc)
  <!--toc:end-->

This repo is intended for my personal use, it is public for easier cloning.

## Installing on macOS with homebrew

<pre>
brew install kitty
</pre>

## Clone repository

<pre>
git clone https://github.com/ThorstenRhau/KittyTerminal.git ~/.config/kitty
</pre>

## Aliases to in to .zshrc

For the _night_ and _day_ aliases to work you need to clone https://github.com/savq/melange-nvim

<pre>
alias kitty_theme='kitty +kitten themes'
alias night='ln -sf $HOME/git/melange-nvim/term/kitty/melange_dark.conf $HOME/.config/kitty/theme.conf'
alias day='ln -sf $HOME/git/melange-nvim/term/kitty/melange_light.conf $HOME/.config/kitty/theme.conf'
</pre>

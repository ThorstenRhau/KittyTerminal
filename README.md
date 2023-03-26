# KittyTerminal

<!--toc:start-->

- [KittyTerminal](#kittyterminal)
  - [Installing on macOS with homebrew](#installing-on-macos-with-homebrew)
  - [Clone repository](#clone-repository)
  - [Set theme switch alias in .zshrc](#set-theme-switch-alias-in-zshrc)
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

## Set theme switch alias in .zshrc

<pre>
alias night='ln -sf ~/git/tokyonight.nvim/extras/kitty/tokyonight_storm.conf ~/.config/kitty/theme.conf'
alias day='ln -sf ~/git/tokyonight.nvim/extras/kitty/tokyonight_day.conf ~/.config/kitty/theme.conf'
</pre>

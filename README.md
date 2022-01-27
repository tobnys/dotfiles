Powerlevel10k
https://github.com/romkatv/powerlevel10k#oh-my-zsh

Set ```ZSH_THEME="powerlevel10k/powerlevel10k"``` in ```~/.zshrc```



#!/bin/bash

BASEDIR="$(cd "$(dirname "${BASH_SOURCE[0]}")" && pwd)"

# vim
ln -s ${BASEDIR}/vimrc ~/.vimrc
ln -s ${BASEDIR}/vim/ ~/.vim

# zsh
ln -s ${BASEDIR}/zshrc ~/.zshrc

# git
ln -s ${BASEDIR}/gitconfig ~/.gitconfig
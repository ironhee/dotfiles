# dotfiles
ironhee dotfiles

## Requirements

- https://github.com/zdharma/zinit

## Install

```
cd ~
sh -c "$(curl -fsSL https://raw.githubusercontent.com/zdharma/zinit/master/doc/install.sh)"
git clone git@github.com:ironhee/dotfiles.git
mv .zshrc .zshrc.bak
ln -s dotfiles/.zshrc ~/.zshrc
```

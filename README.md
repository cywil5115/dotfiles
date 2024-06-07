# My dotfiles

## Setup process

I use chezmoi to manage my configurations. For now it's fairly easy setup but maybe I'll try add some automatization scripts to make it **better**

Install chezmoi:

MacOS:
```bash
brew install chezmoi
```
Fedora:
```bash
dnf install chezmoi
```
Debian based:
```bash
apt install chezmoi
```
Arch:
```bash
pacman -S chezmoi
```
## Init Chezmoi

Start Initialization
```bash
chezmoi init git@github.com:cywil5115/dotfiles.git
```
(Optional) change shell to zsh:
```bash
chsh -s $(which zsh)
```

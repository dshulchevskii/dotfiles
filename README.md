# Dotfiles

My dot files repository inspirated by https://www.atlassian.com/git/tutorials/dotfiles

## Instalations

```bash
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
echo ".cfg" >> .gitignore
git clone --bare https://github.com/dshulchevskii/dotfiles.git $HOME/.cfg
config config --local status.showUntrackedFiles no
```

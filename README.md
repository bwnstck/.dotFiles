# .dotFiles

https://www.atlassian.com/git/tutorials/dotfiles
https://github.com/cburyta/yadr
https://github.com/Peltoche/lsd

```BASH
git init --bare $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
config config --local status.showUntrackedFiles no
echo "alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'" >> $HOME/.bashrc
```

# .gitconfig - gitalias
This repo includes my global gitconfig, espacially shortcuts (alias) of git. 
You can directly copy on your .gitconfig file or you can just run folowing command on your terminal.

git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.br branch
git config --global alias.hist "log --color --graph --pretty=format:'%C(bold blue)%h%Creset -%C(yellow)%d%Creset %s %C(magenta)(%cr) %C(cyan)<%an>%Creset' --abbrev-commit"

Hope it helps to improve better code. Enjoy!

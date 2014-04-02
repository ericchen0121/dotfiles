via http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/
1. dotfiles directory in ~/dotfiles holds dotfiles. The ~ directory has symlinks to the dotfiles in here
2. ~/dotfiles/makesymlinks.sh is a shell script that makes this ~/dotfiles available on github and portable to any mac
3. CURRENT STATUS: 
  1. except current ~/ home directory still has original dotfiles and no symlinks
  2. .make.sh script created. 

Terminal Commands
===
ls -a         Show all files including dotfiles
ls -all       Show all files including dotfiles
ls -ld .??*     Show only dotfiles
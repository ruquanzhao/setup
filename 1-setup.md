# install homebrew

/bin/bash -c "$(curl -fsSL https://gitee.com/ineo6/homebrew-install/raw/master/install.sh)"


# install itools


# install on-my-zsh


# install iterm2 

brew install --cask iterm2


# alias
alias c='pbcopy'

# history 快捷方式
alias hs='history'
alias hg='history | grep'
alias cdc='cd ~/code'

# ls 颜色区分（macOS BSD ls：目录=粗蓝，链接=粗洋红，可执行=粗绿）
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -G'
alias ll='ls -G -lh'
alias la='ls -G -A'

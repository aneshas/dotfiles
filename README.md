# vim/neovim/tmux dotfiles

### Install python3 and pip3
`brew install python3`

### Install vim8 with python3 and timers support
`brew install vim`

### Install nvim [optional]
`brew install neovim`

`pip3 install neovim`

### Install ctags 
`brew install ctags`

### Install nerd fonts
`brew tap homebrew/cask-fonts`

`brew install --cask font-agave-nerd-font`

Set iTerm text profile, height 130 Font 15-17

### Compile ycm
`brew install cmake`

`./install.py --go-completer`

### Install tmux
`brew install tmux`

- Run `tic -x dotfiles/terminfo`
- Install tmux resurrect
    
### Create sym links (vimrc, tmux)
eg. `~/.config/nvim/init.vim` for neovim or `~/.vimrc` for vim

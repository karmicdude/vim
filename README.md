# VIM dotfiles

## Installation

```bash
# Clone repo
git clone https://github.com/karmicdude/vim.git ~/.vim
#git clone git@github.com:karmicdude/vim.git ~/.vim

# Delete default global vimrc config (as root or sudo)
sudo rm -rf /etc/vim*

# Create symlink
sudo ln -s ~/.vim /etc/vim

# For Arch Linux
sudo ln -s ~/.vim/vimrc /etc/vimrc 

# Install Vundle
git clone https://github.com/VundleVim/Vundle.vim.git /etc/vim/bundle/Vundle.vim
vim +PluginInstall +qall

```

# Dependencies

- Syntastic bash: `shellcheck`
- Copy to system keyboard: `xclip`

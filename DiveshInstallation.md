refer to https://www.youtube.com/watch?v=pksX5m8D1B4  for usage   
### 1 change to home directory  
cd ~  
### 2 clone this or original git  
clone http://github.com/thenovices/dotfiles  
### 3 link to .vim  
ln -s dotfiles/.vim* .  
### 4 clone vundle (Vim plugin manager) as follows (gitclone form to)  
git clone https://github.com/gmarik/vundle .vim/bundle/vundle  
### 5 install using vundle
vim +VundleInstall +qall  
  
  
the steps might change refer to vundle repo for more detail
vim +PluginList gives the list of plugins  
the list of plugins is stored in ~ .vim/vimrc/Plugins.vim Edit it to choose pluginss to install

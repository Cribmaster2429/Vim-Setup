## PREQUISITES
wget
curl

## Setting up vim to work with python in linux
sudo apt-get update
sudo apt-get install vim

mkdir -p ~/.vim/syntax
cd ~/.vim/syntax
wget https://raw.githubusercontent.com/hdima/python-syntax/master/syntax/python.vim

## Steps to setting up vimrc
Create .vimrc file in home directory/partition and copy the code
Save the changes

## Installing plugins with vim-plug
Copy the below code in terminal:
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
  https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

## While in normal mode, insert the below commands:
:PlugInstall -> To install the plugins
:PlugUpdate -> To update plugins
:PlugUpdate NERDTree -> To update specific plugin, in this case, NERDTree
:PlugSnapshot ~/vim-plug.list -> To generate a script for restoring all files

# useful-bash 
useful bash scripts i wrote

## vimspector.sh 
this script generates a vimspector file for a rust project
vimspector is a plugin for vim & neovim for debugging
this has to be run in the root directory of your project

## wr-comp.sh
wr-comp.sh compares to given files passed as arguments and generates a new file containing
lines of both files but no double lines for example if you have a file containing 
1 
2 
3 
4 
4 
and a file containing 
1 
3 
4 
5 
4 
6 
the file generated would contain
1 
2 
3 
4 
5 
6 

## install-basic-vim-config.sh
this script installs my [basic vim config](https://github.com/coolian1337/basic-vim-config)
into your home directory without making your home directory a github repo

## pacman-get-package-list-noversion.sh  
This script gets all packges installed with pacman and puts them into packages.txt and removes their versions

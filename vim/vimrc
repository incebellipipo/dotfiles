set nocompatible              " be iMproved, required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
Plugin 'VundleVim/Vundle.vim'
Plugin 'scrooloose/nerdtree'
Plugin 'itchyny/lightline.vim'
Plugin 'sickill/vim-monokai'
Plugin 'posva/vim-vue'
call vundle#end()            " required
filetype plugin indent on    " required

if &term =~ '256color'
      " disable Background Color Erase (BCE) so that color schemes
      " render properly when inside 256-color tmux and GNU screen.
      " see also http://snk.tuxfamily.org/log/vim-256color-bce.html
    set t_ut=
endif

" color up 
color monokai
" color impact

set t_Co=256
set hlsearch
" set cursorline
set number
set ff=unix

set tabstop=2
set shiftwidth=2
set expandtab

set laststatus=2

filetype on
au BufNewFile,BufRead *.launch set filetype=xml
au BufNewFile,BufRead *.xacro set filetype=xml
au BufNewFile,BufRead *.sdf set filetype=xml
au BufNewFile,BufRead Dockerfile.* set filetype=dockerfile
au BufNewFile,BufRead *.bhv set filetype=scala
au BufNewFile,BufRead *.moos set filetype=scala




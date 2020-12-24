# config-custom-neovim

```
" Source
source $HOME/.config/nvim/vim-plug/plugins.vim
source $HOME/.config/nvim/plug-config/coc.vim

" SET
:set cursorline
:set number
:set nocursorcolumn
:set tabstop=4
:set shiftwidth=4
" :set mouse=a
:syntax enable 
:set clipboard=unnamed
:syntax = enabled
:set showcmd
:set ruler
:set encoding=utf-8
:set showmatch
" :set sw=2
:set relativenumber
:set laststatus=2
:set noshowmode

" Color Column
" 242 
hi Cursorline cterm=None ctermbg=8

" Let
let mapleader=" "
" let NERDTreeQuitOnOpen=1
let NERDTreeShowHidden=1

" Map
:map <C-n> :NERDTree
:map <Leader>s <Plug>(easymotion-s2)
:map <Leader>w :w<CR>
:map <Leader>q :q<CR>
```

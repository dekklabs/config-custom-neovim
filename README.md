# config-custom-neovim

```
source $HOME/.config/nvim/vim-plug/plugins.vim

" Set
set cursorline
set nocursorcolumn
set number
" set relativenumber
set tabstop=4
set shiftwidth=4
set lcs+=space:·

" Color Column
" 242
hi CursorLine cterm=NONE ctermbg=8

" MAP
:map <C-n> :NERDTree

" Source
source $HOME/.config/nvim/plug-config/coc.vim
```

[![VsCode](https://skillicons.dev/icons?i=androidstudio)]()


**extensions**

[IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)


**./ideavimrc**

```js
Plug 'preservim/nerdtree'

set scrolloff=5
set visualbell
set noerrorbells
set showmode
set showcmd
set hlsearch
set relativenumber
set number

"" set leader on space
let mapleader = " "

" Do incremental searching.
set incsearch

" Don't use Ex mode, use Q for formatting.
map Q gq
map <C-t> :NERDTree<CR>
nmap <leader>l  <C-W>l
nmap <leader>h  <C-W>h
nmap <leader>j  <C-W>j
nmap <leader>k  <C-W>k

nmap <leader>tp :bprevious<CR>
nmap <leader>tn :bnext<CR>

nmap <S-l> $
nmap <S-h> ^

imap jk <Esc>
nnoremap > >>
nnoremap < <<
```
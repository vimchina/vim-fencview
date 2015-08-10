# vim-fencview
mirror of vim script: [fencview.vim](http://www.vim.org/scripts/script.php?script_id=1708)

## install

`git clone https://github.com/vimchina/vim-fencview.git ~/.vim/bundle/`

## usage

Please read file 'fencview.vim' for detail in plugin dir.

`FencAutoDetect` : auto detect encoding and prompt to select an encoding

## options

`let g:fencview_autodetect = 1`: auto detect file encoding when opening a file (default: 0)

`let g:fencview_auto_patterns='*.txt,*.md,*.org,*.htm{l\=}'`: set file pattern (default: '*.txt,*.htm{l\=}')

## dependent

1. "+iconv" feature is needed
2. ['tellenc'](https://github.com/adah1972/tellenc), a app to detect file encoding which will give you better performance and better accurcy

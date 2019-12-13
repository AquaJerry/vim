# My Vim

This is my custom Vim repo. For official one, see https://github.com/vim/vim.


## Acknowledgements

- Bram Moolenaar, main author of Vim


## Features

This Vim is based on huge version without GUI of official one.
It provides a simple user interface for me to focus on code itself.

Syntax highlighting is preserved.


## Differences from official Vim

Following is by overrided runtime/defaults.vim.

- no line `'number'`
- no `'ruler'`
- no `'showcmd'`
- clear `+statusline` rows
- clear `+vertsplit` columns

Following is by customized src/feature.h.

- no `+viminfo` feature, which might save some garbages produced long long ago if I forget to clear them.

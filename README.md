# My vimfiles.

## Plugins (as submodules)
- [NERDTree](https://github.com/preservim/nerdtree)
- [lightline](https://github.com/itchyny/lightline)
- [Vim Surround](https://github.com/tpope/vim-surround)
- [Vim Repeat](https://github.com/tpope/vim-repeat)
- [Vim Commentary](https://github.com/tpope/vim-commentary)
- [Vim Indent Guides](https://github.com/preservim/vim-indent-guides)
- [systemverilog](https://github.com/nachumk/systemverilog)
- [gruvbox](https://github.com/morhetz/gruvbox)
- [emmet-vim](https://github.com/mattn/emmet-vim)
- [supertab](https://github.com/ervandew/supertab)
- [vim-snipmate](https://github.com/garbas/vim-snipmate) (and dependencies):
    - [vim-addon-mw-util](https://github.com/MarcWeber/vim-addon-mw-utils)
    - [tlib_vim](https://github.com/tomtom/tlib_vim)
- [vim-snippets](https://github.com/honza/vim-snippets)

## To download:

`git clone https://github.com/dvcirilo/vimfiles.git ~/.vim`

## To install the bundled plugins
` git submodule update --init --recursive`

## To remove a submodule ([source](https://gist.github.com/myusuf3/7f645819ded92bda6677))
```
# Remove the submodule entry from .git/config
git submodule deinit -f path/to/submodule

# Remove the submodule directory from the superproject's .git/modules directory
rm -rf .git/modules/path/to/submodule

# Remove the entry in .gitmodules and remove the submodule directory located at path/to/submodule
git rm -f path/to/submodule
```

# To source the vimrc:

`echo "source ~/.vim/vimrc" > ~/.vimrc`

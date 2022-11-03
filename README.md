# My vimfiles.

## Plugins (as submodules)
- [NERDTree](https://github.com/scrooloose/nerdtree)
- [NERD Commenter](https://github.com/scrooloose/nerdcommenter)
- [Vim Surround](https://github.com/tpope/vim-surround)
- [Vim Endwise](https://github.com/tpope/vim-endwise)
- [Supertab](https://github.com/ervandew/supertab)
- [Vim Autoclose](https://github.com/Townk/vim-autoclose)
- [Arduino Syntax File](https://github.com/AwesomeController/Arduino-syntax-file)
- [Vim RagTag](https://github.com/tpope/vim-ragtag)
- [Vim Snipmate](https://github.com/garbas/vim-snipmate)
- [Tlib_vim](https://github.com/tomtom/tlib_vim)
- [vim addon mw utils](https://github.com/MarcWeber/vim-addon-mw-utils)
- [systemverilog](https://github.com/nachumk/systemverilog)
- [vim-bracketed-paste](https://github.com/ConradIrwin/vim-bracketed-paste)
- [vim-snippets](https://github.com/honza/vim-snippets)
- [lightline](https://github.com/itchyny/lightline)
- [vim-easy-align](https://github.com/junegunn/vim-easy-align)
- [goyo](https://github.com/junegunn/goyo)

## To download:

`git clone https://github.com/dvcirilo/vimfiles.git ~/.vim`

## To install the bundled plugins ([source](https://stackoverflow.com/questions/10168449/git-update-submodules-recursively))
```
git submodule update --init --recursive
git submodule foreach --recursive git fetch
git submodule foreach git merge origin master
```
## Or...
```
git submodule update --remote --merge
```

## To remove a submodule ([source](https://gist.github.com/myusuf3/7f645819ded92bda6677))

- Delete the relevant section from the .gitmodules file.
- Stage the .gitmodules changes git add .gitmodules
- Delete the relevant section from .git/config.
- Run git rm --cached path_to_submodule (no trailing slash).
- Run rm -rf .git/modules/path_to_submodule (no trailing slash).
- Commit git commit -m "Removed submodule "
- Delete the now untracked submodule files rm -rf path_to_submodule

# To source the vimrc:

`echo "source ~/.vim/vimrc" > ~/.vimrc`

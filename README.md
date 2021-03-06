# My vimfiles.

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

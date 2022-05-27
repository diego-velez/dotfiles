# Configuration files

1. [Repository Creation](#repository-creation)
2. [Icons and Mouse Cursors](#icons-and-mouse-cursors)
3. [Themes](#themes)

## Repository Creation
Use this [guide](https://www.atlassian.com/git/tutorials/dotfiles) to initialize a git repository on a new system.

### tl;dr
1. `git init --bare $HOME/.files`
2. Write `alias config='git --git-dir=$HOME/.files/ --work-tree=$HOME'` in `.bashrc`
    - Change the git-dir to the directory where you ran the 1st step
3. `config config --local status.showUntrackedFiles no`

## Icons and Mouse Cursors
System-wide icons direectory: `/usr/share/icons`

## Themes
System-wide themes directory: `/usr/share/themes`

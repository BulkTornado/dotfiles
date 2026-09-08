# dotfiles

My personal Linux dotfiles, managed with GNU Stow.

## Requirements

- Git
- Bash
- Vim
- GNU Stow

## Installation

Clone the repository into `$HOME`:

```bash
git clone https://github.com/BulkTornado/dotfiles ~/dotfiles
cd ~/dotfiles
```

> It is possible to clone the repo anywhere on disk and stow it to home dir. 
> Just remember to modify the `stow` command to have the flag `-t $HOME` 

__Stow the common packages__

```bash
stow bash common git vim
```

Then stow either `fedora-kde` or `linux-mint` or `termux` as required.



# aredshift's dotfiles

## Description
These are my dotfiles! Check out this site to understand what that means: https://dotfiles.github.io/

Currently a WIP, still experimenting.

## Installation

So you like my dotfiles, eh?

First off, I'm trying out [chezmoi](https://www.chezmoi.io/) as my dotfiles management tool.

You can currently install them by following these instructions:

1. [Install chezmoi](https://www.chezmoi.io/install/)
1. HTTPS: `chezmoi init https://github.com/aredshift/dotfiles.git`  
or  
SSH: `chezmoi init git@github.com/aredshift/dotfiles.git`  
1. `chezmoi apply` 

## TODO
- [x] Initialize chezmoi & dotfiles repo
- [x] Install antigen & oh-my-zsh and track with chezmoi
- [x] Add Doom emacs
- [ ] Automate installation of Doom emacs (requires install post-clone via `~/doomemacs/bin/doom install`, unlike spacemacs)
- [ ] [Configure .gitconfig template for work/personal](https://www.chezmoi.io/user-guide/manage-machine-to-machine-differences/)
- [ ] Create CI/CD workflow for testing on multiple platforms:
    - [ ] MacOS
    - [ ] Debian
    - [ ] Arch
    - [ ] Ubuntu
    - [ ] Fedora
- [ ] Enable 1Pass/Bitwarden for storing sensitive data across machines
- [ ] [Try encrypting some stuff](https://www.chezmoi.io/user-guide/encryption/gpg/)
- [ ] [Make some fun scripts](https://www.chezmoi.io/user-guide/use-scripts-to-perform-actions/)


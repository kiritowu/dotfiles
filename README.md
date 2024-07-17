# Dotfiles

This repository consist of my frequently used dotfiles, managed using [GNU stow](https://www.gnu.org/software/stow/)

## Prerequisites

1. Git
2. Stow
    Install stow based on your OS's package manager:

    - Fedora

    ```bash
    sudo dnf install stow
    ```

## Getting Started

1. Clone this repository recursively at your home directory.

    ```bash
    cd ~
    git clone --recurse-submodules git@github.com:kiritowu/dotfiles.git
    cd ~/dotfiles
    ```

2. Run stow.

    ```bash
    stow .
    ```

## How it Works?

[GNU stow](https://www.gnu.org/software/stow/) is a symlink farm manager
that creates symbolic-link between files in `dotfiles` with `~` directory.

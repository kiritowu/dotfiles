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

1. Clone this repository at your home directory.

    ```bash
    git clone git@github.com:kiritowu/dotfiles.git
    ```

2. Change directory to `dotfiles`.

    ```bash
    cd dotfiles
    ```

3. Run stow.

    ```bash
    stow .
    ```

## How it Works?

[GNU stow](https://www.gnu.org/software/stow/) is a symlink farm manager
that creates symbolic-link between files in `dotfiles` with `~` directory.

grml-etc-core
=============

## Changes in this repository

Additional changes in the repository https://github.com/twaldecker/grml-etc-core:

 * Merged the standard fedora vimrc configuration file
 * Added a Makefile

Steps to install the grml-etc-core in Fedora:

    git clone https://github.com/twaldecker/grml-etc-core.git
    cd grml-etc-core
    sudo make install

## Original README continues here

This repository contains the core /etc files for the Grml system.

While generally these files are distributed as a Debian package, named
"grml-etc-core", they are also useful on other systems.

To use the most important files for your user, use the following commands:

    # IMPORTANT: please note that you might override existing
    # configuration files in the current working directory!
    wget -O .screenrc     http://git.grml.org/f/grml-etc-core/etc/grml/screenrc_generic
    wget -O .vimrc        http://git.grml.org/f/grml-etc-core/etc/vim/vimrc
    wget -O .zshrc        http://git.grml.org/f/grml-etc-core/etc/zsh/zshrc


Or, on operating systems without wget:

    # IMPORTANT: please note that you might override existing
    # configuration files in the current working directory!
    curl -o .screenrc     http://git.grml.org/f/grml-etc-core/etc/grml/screenrc_generic
    curl -o .vimrc        http://git.grml.org/f/grml-etc-core/etc/vim/vimrc
    curl -o .zshrc        http://git.grml.org/f/grml-etc-core/etc/zsh/zshrc


Further information is available from http://grml.org/console/


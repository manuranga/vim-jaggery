vim-jaggery
===========

Syntax coloring for jaggery in vim. This will enable basic syntax coloring for `.jag` files.


Install
=======

## Basic Install

Copy `ftdetect` and `ftplugin` into ~/.vim

## Install via pathogen

Clone this repository in to bundle directory

    cd ~/.vim/bundle && git clone https://github.com/manuranga/vim-jaggery.git
    
Make sure that the `filetype` is turned off immediately after and then re-enabled. (This is a workaround for a bug)

    execute pathogen#infect()
    filetype off
    syntax on
    filetype plugin indent on

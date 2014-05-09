vim-jaggery
===========

Syntax coloring for jaggery in vim. This will enable basic syntax coloring for `.jag` files.


Install
=======

## Basic Install

1. clone this repository
2. Copy `ftdetect` and `ftplugin` into ~/.vim
3. addd follwing to ~/.vimrc

    `syntax plugin on`


## Install via pathogen

1. Clone this repository in to bundle directory

    `cd ~/.vim/bundle && git clone https://github.com/manuranga/vim-jaggery.git`
    
2. Make sure that the `filetype` is turned off immediately after pathogen infect and then re-enabled. (This is a workaround for a bug)

```
    execute pathogen#infect()
    filetype off
    syntax on
    filetype plugin indent on
```


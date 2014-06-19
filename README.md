dragvisuals.vim
===============

Vundle friendly hosted version of Damian Conway's dragvisuals.vim plugin

## Usage

Add the following to your .vimrc

for [Vundle](https://github.com/gmarik/Vundle.vim) add the following to you plugin list:

    Plugin 'psydefect/dragvisuals.vim'
    
Add the rest somewhere else
    
    vmap  <expr>  <LEFT>   DVB_Drag('left')
    vmap  <expr>  <RIGHT>  DVB_Drag('right')
    vmap  <expr>  <DOWN>   DVB_Drag('down')
    vmap  <expr>  <UP>     DVB_Drag('up')
    vmap  <expr>  D        DVB_Duplicate()


This [vim](http://vim.org) plugin was originally created by [Damian Conway](http://en.wikipedia.org/wiki/Damian_Conway).

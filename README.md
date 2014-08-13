# Swvim

This is a fork of [https://github.com/SweeD/swvim SwVim]
Swvim is a little vim package. It's lightweight and optimized for rails development in terminal vim.

## Requirements

Windows/Linux and Mac supported!

* git into Search Path


## Setup

Be sure that you don't have any .vim.old .vimrc.old .gvimrc.old in your
home directory.

Then do

    git clone git@github.com:mafolz/swvim.git ~/.swvim
    cd ~/.swvim
    ./install.sh
    or ./install.bat

Now open vim and type :PluginInstall
If everything was correct configured, the installation will be successfully be done in 
vim itself.

And now you're ready to go!

## Roadmap

* find a plugin which replace ack.vim to support windows too.

## Customization

You can add your own configurations in ~/.vimrc.local to customize the config to your needs.

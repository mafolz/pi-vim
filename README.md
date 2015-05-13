# PI-Vim
Platform Independent Vim Distribution.

This is a fork of [https://github.com/SweeD/swvim SwVim] but was changed a lot to run on all
common OS and minimize the external dependencies to the environment.

Swvim is a little vim package. It's lightweight and optimized for rails development in terminal vim.
Take a look at SwVim if you are not happy with PI-Vim ;) 

## Requirements

Windows/Linux and Mac supported!

The only hard required tool are git.
So you need the git executable in your search path.

Check this into Mac/Linux/Unix int your terminal or in Windows via Powershell or cmd.

### Windows Reqirement

We ned junction to make a hardlink from a folder.
So download [https://technet.microsoft.com/de-de/sysinternals/bb896768.aspx Junction] and make it accessible to your search path.

## Setup

Be sure that you don't have any .vim.old .vimrc.old .gvimrc.old in your
home directory.

Then do

    git clone git@github.com:mafolz/swvim.git ~/.swvim
    cd ~/.swvim
    ./install.sh
    or ./install.bat

### Install new Plugins 

Open vim and type :PluginInstall
If everything was correct configured, the installation will be successfully be done in
vim itself.

And now you're ready to go!

### Update Plugins from PI-Vim

Open vim and type :PluginUpdate.
If the update are completed, you can watch the changelogs with u.

Enjoy your updates.

## Roadmap

* find a plugin which replace ack.vim or find a buildin replacement for grep to support windows too.
* Describe the used plugins and they correct usage

## Customization

You can add your own configurations in ~/.vimrc.local to customize the config to your needs.

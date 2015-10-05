# dotVim with Steroids

Don't start with Vim from the scratch.

Vim is a super powerful editor, because it is relatively easy to adapt to fit your needs. It has nothing to envy to other popular editors such as Sublime Text 2 or Brakets.io

This repository is a help to give steroids to your Vim editor. I uploaded my configuration files and pluggins (through git submodules for easy installation), with these you can convert your regular Vim on a Vim with steroids, thanks to the careful selection of a few plugins.


## Installation

First, clone this repository to your .vim folder.

    git clone https://github.com/mismatso/dotvim.git ~/.vim

Create a symbolic link to vim config file

    ln -s ~/.vim/.vimrc ~/.vimrc

Now install the plugins bundles as git submodules

    cd ~/.vim
    git submodule init
    git submodule update

Then, install Pathogen to `~/.vim/autoload/pathogen.vim`.  Or copy and paste:

    mkdir -p ~/.vim/autoload ~/.vim/bundle && \
    curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

If you're using Windows, change all occurrences of `~/.vim` to `~\vimfiles`.

On GNU/Linux you can install the patched fonts for Vim-Airline that way

    ~/.vim/fonts/install.sh

If you're using other operating system see more information about install the fonts [here](https://powerline.readthedocs.org/en/latest/installation.html#fonts-installation).

## The look of your "new" powerful Vim Editor

In the following screenshot you can see the scheme color Monokai, the status bar Airline, the NERD Tree Explorer, and the font "S LG Meslo for Powerline" and others.

![A screenshot of Vim-Airline](https://s3.amazonaws.com/mismatso/public/vim/screenshots/vim-airline.png  "Vim-Airline")

In the following screenshot you can see the CtrlP pluging in action.

![A screenshot of Vim-CtrlP](https://s3.amazonaws.com/mismatso/public/vim/screenshots/vim-ctrlp.png  "Vim-CtrlP")


## Plugins included in this dotVim repository

These are the plugins that I needed to feel really comfortable to use Vim as editor for development.

* **NERD Tree**
A tree explorer plugin for vim.
https://github.com/scrooloose/nerdtree.git

* **CtrlP**
Full path fuzzy file, buffer, mru, tag, ... finder for Vim.
https://github.com/kien/ctrlp.vim.git

* **Ultisnips**
UltiSnips is the ultimate solution for snippets in Vim. It has tons of features and is very fast.
https://github.com/SirVer/ultisnips.git

* **Snippets**
This repository contains snippets files for various programming languages.
https://github.com/honza/vim-snippets.git

* **Airline**
This repository contains snippets files for various programming languages.
https://github.com/bling/vim-airline.git

* **Fullscreen**
A plugin which help users to toggle a fullscreen mode on GVim or MacVim.
https://github.com/lambdalisue/vim-fullscreen.git

* **Fugitive**
May very well be the best Git wrapper of all time.
https://github.com/tpope/vim-fugitive.git

* **Bufferline**
Super simple vim plugin to show the list of buffers in the command bar
https://github.com/bling/vim-bufferline.git

* **Multiple-cursors**
True Sublime Text style multiple selections for Vim
https://github.com/terryma/vim-multiple-cursors.git

* **BufExplorer**
Quickly and easily switch between buffers
https://github.com/jlanzarotta/bufexplorer.git

* **Colors-Solarized**
Precision colorscheme for the vim text editor
https://github.com/altercation/vim-colors-solarized.git

* **Monokai**
Monokai color scheme for Vim converted from Textmate theme with the same name
https://github.com/sickill/vim-monokai.git


## Learn how to keep your own dotfiles on GitHub

If you want to learn how to keep your own vim settings on GitHub, you should see the following vimcast, in which it’s done a similar process that I did to put all things together in this repository.

http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/

Some settings used in my .vimrc were taken from thoughtbot, others were taken from mscoutermarsh, and many others from vim.wikia.com

* **thoughtbot**
A set of vim, zsh, git, and tmux configuration files.
https://github.com/thoughtbot/dotfiles

* **mscoutermarsh**
Vim/Tmux config.
https://github.com/mscoutermarsh/dotfiles

* **vim.wikia**
A wiki about Vim
http://vim.wikia.com/


## Contributing

Please don't send pull request for patching, because this is my vim configuration for production development environment. Instead that I suggest make a fork of this repo or [email me](mailto:mismatso@gmail.com)  with the suggestions of pluggins and fixes to .vimrc for improved the Vim behavior, I will give you the credits on this readme file.


## Self-Promotion

If you want you can give a tour for my [blog](http://www.mizaqblog.com) and follow me on [Twitter](https://twitter.com/mismatso).


## License

**dotVim with Steroids** by *Misael Matamoros Soto* is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Based on a work at https://github.com/mismatso/dotvim.

![Licencia Creative Commons](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png) 

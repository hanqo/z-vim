z-vim
=====

## About
[z-vim] is the `.vimrc` file for my personal use.
Anyone is free and welcome to clone, update or fork it.

## Quick Start
1. Set up [Git]

    This is probably done already since you're using Github.

    If not, for Debian based Linux users:
    `$ sudo apt-get install git`

2. Clone [z-vim]

    `$ git clone https://github.com/zhao-han/z-vim.git`

    And move `.vimrc` out to ~ directory.

    If a `.vimrc` is already existing, you might back it up before replacing.
    
    `$ mv .vimrc .vimrc_bak`

3. Set up [Vundle]:

    `$ git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

4. Install Plugins:

    Launch `vim` and run `:PluginInstall`

    Or 
    
    Installing from command line: `vim +PluginInstall +qall`
    
## License
MIT

[z-vim]:https://github.com/zhao-han/z-vim.git
[Vundle]:http://github.com/gmarik/Vundle.vim
[Git]:http://git-scm.com

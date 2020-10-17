# nvim config

## Screen

![nvim](https://user-images.githubusercontent.com/68990594/92236319-d1493480-eed2-11ea-9585-a224386fd5db.png)

## Screen Windows

![nvim-win](https://user-images.githubusercontent.com/68990594/96336615-b6a3d700-109e-11eb-930a-b8750ed7c2ac.png)

## Install Neovim

    https://github.com/neovim/neovim/wiki/Installing-Neovim

## Install dependency package

    pip install pynvim
    nodejs

## Install config

    git clone https://github.com/sauravj7/nvim_config ~/.config/nvim

    # For Windows
    git clone https://github.com/sauravj7/nvim_config  C:\Users\[USER NAME]\AppData\Local\nvim

## Edit Config (only for Windows)

    ## File nvim/init.vim

    change all ~/.config to ~/AppData/Local

    # For ex
    change 'source ~/.config/nvim/general/settings.vim'
    to     'source ~/AppData/Local/nvim/general/settings.vim'


    ## File nvim/vim-plug/plugins.vim

    change 'call plug#begin('~/.config/nvim/autoload/plugged')'
    to     'call plug#begin('~/AppData/Local/nvim/autoload/plugged')'

## Install Plugins

    # Open Neovim
    nvim

    # Install all of your plugins (restart neovim after this step)
    :PlugInstall 

    # Install coc extensions as you like 
    :CocInstall coc-clangd coc-json coc-java coc-cmake coc-python

[Full List of Extension](https://github.com/neoclide/coc.nvim/wiki/Using-coc-extensions#implemented-coc-extensions)

## Custom Mapping

    gr (codefix)
    gd (go to definition)
    gr (rename symbol)
    gf (format current file)
    K  (for documentation)

    alt + hjkl to resize window.
    ctrl + hjkl for window navigation.
    
    ctrl + n to redraw status bar.
    
    jk and kj for "ESC"
    
    space (leader key).

## Plugins Included

[Gruvbox](https://github.com/morhetz/gruvbox)  
[Startify](https://github.com/mhinz/vim-startify)  
[Nerdtree](https://github.com/preservim/nerdtree)  
[Airline](https://github.com/vim-airline/vim-airline)  
[Auto Pairs](https://github.com/jiangmiao/auto-pairs)  
[Cpp Highlight](https://github.com/octol/vim-cpp-enhanced-highlight)  
[Signify](https://github.com/mhinz/vim-signify)  
[Unimpaired](https://github.com/tpope/vim-unimpaired)  
[Which Key](https://github.com/liuchengxu/vim-which-key)  
[Devicons](https://github.com/ryanoasis/vim-devicons)  
[COC](https://github.com/neoclide/coc.nvim)  

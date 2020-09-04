# nvim_config

# Screen
![nvim](https://user-images.githubusercontent.com/68990594/92236319-d1493480-eed2-11ea-9585-a224386fd5db.png)

-- --
## Install Neovim
### Mac
    brew install neovim

### Ubuntu
    sudo apt install neovim

### Arch
    sudo pacman -S neovim


### Install dependency package
    pip install pynvim

## Install config
    git clone https://github.com/sauravj7/nvim_config ~/.config/nvim

## Install powerline fonts
    git clone https://github.com/powerline/fonts.git --depth=1
    cd fonts
    ./install.sh
    cd ..
    rm -rf fonts

## Install Plugins
### Open nvim
    nvim

### Install all of your plugins (restart neovim after this step)
    :PlugInstall
    
### Install coc extensions you like
    :CocInstall coc-clangd coc-json coc-java coc-cmake

-- --
## Custom Mappings
    gr (codefix)
    gd (go to definition)
    gr (rename symbol)
    gf (format current file)

    alt + hjkl to resize window.
    ctrl + hjkl for window navigation.
    
    ctrl + n to redraw status bar.
    
    jk and kj for "ESC"
    
    space (leader key).

-- -- 
# Plugins Included
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

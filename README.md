# NEOVIM TUTORIALS

```
               ,
              / \,,_  .'|
           ,{{| /}}}}/_.'            _____________________________________________
          }}}}` '{{'  '.            /                                             \
        {{{{{    _   ;, \          /            Ladies and Gentlemen,              \
     ,}}}}}}    /o`\  ` ;)        |                                                |
    {{{{{{   /           (        |                 this is ...                    |
    }}}}}}   |            \       |                                                |
   {{{{{{{{   \            \   --=:                                                |
   }}}}}}}}}   '.__      _  |     |                  N E O V I M                   |
   {{{{{{{{       /`._  (_\ /      \                                              /
    }}}}}}'      |    //___/        \____________________________________________/   
     }}}`                                                                         
                                                                                  
                                  
```

## Install neovim (Mac)

```
brew install neovim
```

## Plugins

### Vim-plug

```
curl -fLo ~/.config/nvim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Customization

Create ~/.config/nvim/init.vim file and add plugins.
Add this to the beggining of the init.vim file:

```nvim
call plug#begin()
call plug#end()
```

## Add plugins + Recommended plugins

To add some plugins, just put between the begin and end calls the plugins you wanto to install like this:

```nvim
call plug#begin()

" NERDTree - File navigation
Plug 'scrooloose/nerdtree' 

call plug#end()
```


![tender](https://cloud.githubusercontent.com/assets/829859/18413534/f7cb472c-77aa-11e6-86bf-9c790aadd2df.png)
==============================================================================================================

A 24bit colorscheme for Vim, Airline and Lightline (generated by [Estilo](http://estilo.jacoborus.codes))


## Screenshots

![javascript](https://cloud.githubusercontent.com/assets/829859/18417365/7780885a-782e-11e6-8e88-150cfc70e35b.png)
![statusplus](https://cloud.githubusercontent.com/assets/829859/18418261/0e0f54f4-7843-11e6-9825-bff197a7f76a.png)
![statusregular](https://cloud.githubusercontent.com/assets/829859/18491051/f81ba21a-7a04-11e6-85c6-e9bc3c98415f.png)
![nerdtree-yaml](https://cloud.githubusercontent.com/assets/829859/18417875/4b3e382e-783c-11e6-94ea-afb9bf0d68f2.png)
![gvdiff](https://cloud.githubusercontent.com/assets/829859/18417983/3253da42-783e-11e6-93ac-b0f506f0a3c5.png)
![gitcommit](https://cloud.githubusercontent.com/assets/829859/18418089/270b409c-7840-11e6-8618-1aa81f612860.png)


## Installation

Install manually or use a package manager:

```viml
" vim-plug
Plug 'jacoborus/tender'
" NeoBundle
NeoBundle 'jacoborus/tender'
" Vundle
Plugin 'jacoborus/tender'
```

Once your plugin is installed you can set the color scheme in your `.vimrc` or `init.vim`

Enable true color in neovim:

```viml
set termguicolors
```

Enable true color in vim v7.4.1770 or newer:

```viml
set guicolors
```

Fix for MacVim:

```viml
let macvim_skip_colorscheme=1
```

Use colorscheme:

```viml
colorscheme tender
```

Use [lightline](https://github.com/itchyny/lightline.vim) themes (`tender` and `tenderplus`):

```viml
" enable tender lightline theme
let g:tender_lightline = 1
" set lighline theme (inside lightline config)
let g:lightline = { 'colorscheme': 'tender' }
```

Use [airline](https://github.com/vim-airline/vim-airline) themes (`tender` and `tenderplus`):

```viml
" enable tender airline theme
let g:tender_airline = 1
" set airline theme
let g:airline_theme = 'tender'
```


<br><br>

---

© 2016 [jacoborus](http://jacoborus.codes) - Released under [MIT License](https://raw.github.com/jacoborus/nanobar/master/LICENSE)

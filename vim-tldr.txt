Vim 101
===

Basics
---
- :help <Enter> y tenés toda la papa
- Links: entrar = CTRL-], atras = CTRL-O, adelante = CTRL-I
- help: normal = nada, visual = v_, insert = i_, command = :, option = ''

File Explorer
---
- Abrir: :e.  o :vsp.
- Ir un dir arriba: -
- Nuevo archivo: %
- Nuevo directorio: d
- Rename: R
- Borrar: D
- Cambiar Layout: i
- Ir a directorio (cd): c
- Ocultar dotfiles: gh


Rotar ventanas: <C-w> r 

Ejecutar comando en rango de lineas
<rango>normal <comando>
    I//
    dd


Seguir un file como link
gf


Instalar solarized
git clone https://github.com/lifepillar/vim-solarized8.git ~/.vim/pack/themes/opt/solarized8

.vimrc
---
set nocompatible 
set filetype plugin indent on
colorscheme desert

set number
set splitright

set smartindent
set expandtab
set shiftwidth=4
set tabstop=4
set softtabstop


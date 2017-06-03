nerdtree-grep-plugin
====================

A really rough integration of `:grep` with nerdtree. Adds a `'g'` menu item that
prompts the user for a search pattern to use with `:grep`. `:grep` is run on the
selected dir (using the parent if a file is selected).

Originally written by [scrooloose](https://gist.github.com/scrooloose/205807),
enhanced by [masaakif](https://gist.github.com/masaakif/414375).

## Installation

For Pathogen

`git clone https://github.com/MarSoft/nerdtree-grep-plugin.git ~/.vim/bundle/nerdtree-grep-plugin`

Now reload `vim`.

For Vundle

```
Plugin 'scrooloose/nerdtree'
Plugin 'MarSoft/nerdtree-grep-plugin'
```

For NeoBundle

```
NeoBundle 'scrooloose/nerdtree'
NeoBundle 'MarSoft/nerdtree-grep-plugin'
```

For Plug
```
Plug 'scrooloose/nerdtree'
Plug 'MarSoft/nerdtree-grep-plugin'
```

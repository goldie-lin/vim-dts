vim-dts
=======

Linux kernel DTS/DTSI syntax highlighting for Vim

Mirror of dts.vim from Ubuntu 14.04
(located in `/usr/share/vim/vim74/syntax/dts.vim` of `vim-runtime` package)


Motivation
----------

*   Useful for backporting to use in Ubuntu 12.04 or older environment.
*   Separate into one standalone syntax file is good for managing
    (install/update/remove) all vim script/syntax with
    [Vundle](https://github.com/gmarik/Vundle.vim),
    [Neobundle](https://github.com/Shougo/neobundle.vim),
    or [Vim-Plug](https://github.com/junegunn/vim-plug).


Usage
-----

Add the following lines to your `~/.vimrc`.

```vim
autocmd BufRead,BufNewFile *.dts,*.dtsi set filetype=dts
```

Then, restart vim to apply the changes.

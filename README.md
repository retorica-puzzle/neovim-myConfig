# neovim-myConfig

This my config basic installation for windows

## Installation

Install scoop with powershell -> <a href="scoop.sh">scoop.sh</a>

Error powershell SSH/TLS fix with command

```sh
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
```

Install neovim with scoop

```sh
scoop install neovim
```
## Plugins init.vim 
Default directory `C:\Users\nameuser\AppData\Local\nvim`
or
See with command `:echo stdpath(‘config’) `

See more documentation from <a href="https://github.com/junegunn/vim-plug">junegunn/vim-plug</a>

## Install coc-explorer
My favorite plugin to manage my projects.

```sh
:CocInstall coc-explorer
```
or

See more documentation from <a href="https://github.com/weirongxu/coc-explorer">weirongxu/coc-explorer</a>

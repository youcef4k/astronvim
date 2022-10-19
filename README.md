# astronvim

## Setup 
```bash
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
cd ~/.config/nvim/lua
git clone https://github.com/youcef4k/astronvim user
cp user/gruvbox.vim ~/.config/nvim/colors
nvim
:PackerSync
TSInstall cpp python lua vim json cmake bash
:LspInstall pyright, sourcery, clangd, bashls, opencl_ls, sumneko_lua, grammarly, cmake, jsonls, vimls, astro
```

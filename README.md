<h1 align="center" >🧛 dracula.nvim</h1>

<p align="center"><a href="https://draculatheme.com/">Dracula</a> colorscheme for <a href="https://neovim.io/">NEOVIM</a> written in Lua</p>
<p align="center">Forked from <a href="https://github.com/Mofiqul/dracula.nvim">mofiqul/dracula.nvim</a></p>

## ✔️ Requirements

- Neovim >= 0.5.0

## #️ Supported Plugins

- [LSP](https://github.com/neovim/nvim-lspconfig)
- [Lualine](https://github.com/hoob3rt/lualine.nvim)
- [NvimTree](https://github.com/kyazdani42/nvim-tree.lua)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [indent-blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)

## ⬇️ Installation

Install via package manager

```lua
-- Using Packer:
use 'babchoo/dracula.nvim'
```

## 🚀 Usage

```lua
-- Lua:
vim.cmd[[colorscheme dracula]]
```

If you are using [`lualine`](https://github.com/hoob3rt/lualine.nvim), you can also enable the provided theme:

> Make sure to set theme as 'dracula-nvim' as dracula already exists in lualine built in themes

```lua
require('lualine').setup {
  options = {
    theme = 'dracula-nvim'
  }
}
```

## 🔧 Configuration

```lua
-- customize dracula color palette
vim.g.dracula_colors = {
    comment = "#7970a9",
    menu = "#22212c",
    nontext = "#3b4048",
    visual = "#44475a",
    orange = "#ffca80",
    black = "#1a1826",
    red = "#ff5555",
    green = "#8aff80",
    yellow = "#ffff80",
    purple = "#9580ff",
    pink = "#ff80bf",
    cyan = "#80ffea",
    white = "#f8f8f2",
    selection = "#44475a",
    bright_red = "#ff6e6e",
    bright_green = "#a2ff99",
    bright_yellow = "#ffff99",
    bright_blue = "#aa99ff",
    bright_magenta = "#ff99cc",
    bright_cyan = "#99ffee",
    bright_white = "#ffffff",
    bg = "#22212c",
    fg = "#f8f8f2",
}
-- set italic comment
vim.g.dracula_italic_comment = true
```

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
}'
```

## 🔧 Configuration

```lua
-- customize dracula color palette
vim.g.dracula_colors = {
	fg = "#F8F8F2",
	bg = "#282A36",
	comment = "#6272A4",
	menu = "#21222C",
	nontext = "#3B4048",
	selection = "#44475A",
	visual = "#3E4452",
	black = "#191A21",
	cyan = "#8BE9FD",
	green = "#50fa7b",
	orange = "#FFB86C",
	pink = "#FF79C6",
	purple = "#BD93F9",
	red = "#FF5555",
	white = "#ABB2BF",
	yellow = "#F1FA8C",
	bright_blue = "#D6ACFF",
	bright_cyan = "#A4FFFF",
	bright_green = "#69FF94",
	bright_magenta = "#FF92DF",
	bright_red = "#FF6E6E",
	bright_white = "#FFFFFF",
	bright_yellow = "#FFFFA5",
}
-- use transparent background
vim.g.dracula_lualine_bg_color = "#44475a"
-- set italic comment
vim.g.dracula_italic_comment = true
```

# 🏔 Barstrata
<p align="center">
Vibrant but dark colorscheme for neovim.<br/>
</p>

![Barstrata Typescript Preview](https://user-images.githubusercontent.com/40544194/197351333-29a9a3af-fcbc-46f5-8b91-be2f191e3075.png)
Base code forked from [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim)

## ✨ Features

- Supports the latest Neovim features
- Terminal colors inside Neovim

### Plugin Support

- [TreeSitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [LSP Diagnostics](https://neovim.io/doc/user/lsp.html)
- [LSP Trouble](https://github.com/folke/lsp-trouble.nvim)
- [LSP Saga](https://github.com/glepnir/lspsaga.nvim)
- [Git Signs](https://github.com/lewis6991/gitsigns.nvim)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [NvimTree](https://github.com/kyazdani42/nvim-tree.lua)
- [WhichKey](https://github.com/liuchengxu/vim-which-key)
- [Indent Blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [BufferLine](https://github.com/akinsho/nvim-bufferline.lua)
- [ALE](https://github.com/dense-analysis/ale)
- [vim-sneak](https://github.com/justinmk/vim-sneak)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [Hydra](https://github.com/anuvyklack/hydra.nvim)
- [Lualine](https://github.com/nvim-lualine/lualine.nvim)

## ⚡️ Requirements

- Neovim >= 0.5.0

## 📦 Installation

Install the theme with your preferred package manager:

[vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'kvrohit/barstrata.nvim'
```

[packer](https://github.com/wbthomason/packer.nvim)

```lua
use 'kvrohit/barstrata.nvim'
```

## 🚀 Usage

Enable the colorscheme:

```lua
-- Lua
vim.cmd [[colorscheme barstrata]]
```

```vim
" Vim Script
colorscheme barstrata
```

## ⚙️ Configuration

> Configuration needs to be set **BEFORE** loading the color scheme with `colorscheme barstrata`

| Option                     | Default   | Description              |
| -------------------------- | --------- | ------------------------ |
| barstrata_italic_comments  | `true`    | Make comments italic     |
| barstrata_italic_keywords  | `false`   | Make keywords italic     |
| barstrata_italic_booleans  | `false`   | Make booleans italic     |
| barstrata_italic_functions | `false`   | Make functions italic    |
| barstrata_italic_variables | `false`   | Make variables italic    |
| barstrata_italic_types     | `false`   | Make types italic        |
| barstrata_transparent      | `false`   | Disable background color |
| barstrata_variant          | `default` | Colorscheme variant      |

```lua
-- Example config in lua
vim.g.barstrata_italic_functions = true
-- Load the colorscheme
vim.cmd [[colorscheme barstrata]]
```

```vim
" Example config in Vim Script
let g:barstrata_italic_functions = 1

" Load the colorscheme
colorscheme barstrata
```



## ☑️ Todo

<details>
<summary>To add examples</summary>
Shell script<br/>
Markdown<br/>
YAML<br/>
Rust<br/>
HTML<br/>
CSS<br/>
JavaScript
</details>

##  Extras

- Alacritty color theme: `extras/alacritty/barstrata.yaml`

## 👍 Credits

- The source of this theme [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim)

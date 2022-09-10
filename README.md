# 🏔 Barstrata

A cold, dark color scheme for Neovim written in Lua forked from [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim) which was ported from [vim-substrata](https://github.com/arzg/vim-substrata) theme.

## ✨ Features

- Supports the latest Neovim `0.5` features like TreeSitter and LSP
- Terminal colors inside Neovim
- Color themes for terminals:
  - `alacritty`
  - `gnome-terminal`
  - `iterm2`
  - `kitty`
  - `konsole`
  - `wezterm`

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

```vim
" Setting brighter colorscheme variant
let g:barstrata_variant = "brighter"
```


## ☑️ Todo

<details>
<summary>To add examples</summary>
## Preview
### Terminal
### Shell script
### Markdown
### YAML
### Rust
### HTML
### CSS
### JavaScript
</details>

##  Extras

- Alacritty color theme: `extras/alacritty/barstrata.yaml`

## 👍 Credits

- The source of this theme [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim)

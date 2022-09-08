# 🏔 Barstrata

A cold, dark color scheme for Neovim written in Lua ported from [vim-barstrata](https://github.com/arzg/vim-barstrata) theme.

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

## Preview

### Terminal

![01-gnome-terminal](https://user-images.githubusercontent.com/1040966/126907857-4bcc17d0-eb5b-4efb-b19b-aed7c281ddce.png)

### Shell script

![02-shell-script](https://user-images.githubusercontent.com/1040966/126907859-a3237745-6f67-4fe6-a990-6be96a466fcd.png)

### Markdown

![03-markdown](https://user-images.githubusercontent.com/1040966/126907860-09243fbf-c01d-4369-9ea1-25e31f705f33.png)

### YAML

![04-yaml](https://user-images.githubusercontent.com/1040966/126907862-8435f068-e494-42f0-8d1c-dd00d110199a.png)

### Rust

![05-rust](https://user-images.githubusercontent.com/1040966/126907863-60ad9141-cf7e-479e-a2a2-034bb04f3359.png)

### HTML

![06-html](https://user-images.githubusercontent.com/1040966/126907867-c50c6865-22d9-4396-ac72-eb42c36be454.png)

### CSS

![07-css](https://user-images.githubusercontent.com/1040966/126907868-190283cc-ae80-44b9-ad1e-f046a2c823bc.png)

### JavaScript

![08-js](https://user-images.githubusercontent.com/1040966/126907870-1e45a9d1-9ed2-4a7c-8b5a-99a99f212e5b.png)

## ☑️ Extras

- Eclipse color theme: `extras/eclipse/barstrata.xml`
- Gnome Terminal color theme: `extras/gnome-terminal/barstrata.sh`
- iTerm2 color theme: `extras/iterm2/barstrata.itermcolors`
- Konsole color theme: `extras/konsole/barstrata.colorscheme`
- WezTerm color theme: `extras/wezterm/colors/Barstrata.toml`
- kitty color theme: `extras/kitty/barstrata.conf`
- Alacritty color theme: `extras/alacritty/barstrata.yaml`

## 👍 Credits

- The original authors of the excellent [vim-barstrata](https://github.com/arzg/vim-barstrata) theme.
- Lua plugin derived from [neon](https://github.com/rafamadriz/neon) and influenced by [tokyonight.nvim](https://github.com/folke/tokyonight.nvim).
- Gnome terminal, Konsole and iTerm2 colors exported from [terminal.sexy](http://terminal.sexy).

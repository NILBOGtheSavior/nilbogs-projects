---
title: 'Configuring Neovim'
description: 'Configuring neovim as NILBOGs ideal development environment'
pubDate: 'March 2 2026'
heroImage: '../../assets/img/neovim_thumbnail.jpg'
---

![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)
![Neovim](https://img.shields.io/badge/NeoVim-%2357A143.svg?&style=for-the-badge&logo=neovim&logoColor=white)

## Summary

Configuring neovim as NILBOGs ideal development environment. After using [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) for almost a year, a new configuration will be made from scratch.

## Checkpoints

- [ ] Set up directory structure

```
󰉋 nvim/
├── 󰆧 init.lua
└── 󰉋 lua/
    ├── 󰉋 config/
    │   ├── 󰒓 config.lua
    │   ├── ...
    │   └── 󰒓 config.lua
    └── 󰉋 plugins/
        ├── 󰈙 plugin.lua
        ├── ...
        └── 󰈙 plugin.lua
```

- [ ] Configure `vim.opt`
- [ ] Install plugins
    - [ ] [lazydev.nvim]() - nvim lsp
    - [ ] [Lazy.nvim](https://github.com/folke/lazy.nvim) - plugin manager
    - [ ] [nvim-autopairs](https://github.com/windwp/nvim-autopairs) - brackets and parentheses
    - [ ] [nvim-dap](https://github.com/mfussenegger/nvim-dap) - debug adapter protocol
    - [ ] [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - git indicators
    - [ ] [indentmini.nvim](https://github.com/nvimdev/indentmini.nvim) - indentation plugin
    - [ ] [Neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim) - file menu
    - [ ] [Comment.nvim](https://github.com/numToStr/Comment.nvim) - quick toggle comments
    - [ ] [which-key.nvim](https://github.com/folke/which-key.nvim) - keybinding popup
    - [ ] [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - fuzzy finder
    - [ ] [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - language server
    - [ ] [mason.nvim](https://github.com/mason-org/mason.nvim) - language server manager
    - [ ] [nvim-cmp](https://github.com/hrsh7th/nvim-cmp) - autocompletion
    - [ ] [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - color themes
    - [ ] [todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - highlight todo comments
    - [ ] [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - parser
    - [ ] [nvim-colorizer.lua](https://github.com/norcalli/nvim-colorizer.lua) -
    - [ ] [md-pdf.nvim](https://github.com/arminveres/md-pdf.nvim) - PDF converter for MD
    - [ ] [fidget.nvim](https://github.com/j-hui/fidget.nvim) - status notifier
    - [ ] [nvim-surround](https://github.com/kylechui/nvim-surround) - surround selections
    - [ ] [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) - status line
    - [ ] [conform.nvim](https://github.com/stevearc/conform.nvim) - formatter
- [ ] Validation


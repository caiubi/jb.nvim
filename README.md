# 🎨 JB for Neovim

<p>Color scheme for Neovim, inspired by JetBrains IDEs.</p>

<table width="100%">
  <tr>
    <th>Dark</th>
    <th>Light</th>
  </tr>
  <tr>
    <td>
        <img width="512" alt="dark-js" src="https://github.com/user-attachments/assets/d04726cf-5b59-4b92-ace5-9894eb83d8a5" />
    </td>
    <td>
      <img width="512" alt="light-js" src="https://github.com/user-attachments/assets/591bf1f9-162f-438c-91a5-0bcfab74b800" />
    </td>
  </tr>
</table>

## Features

- Supports both light and dark themes
- Terminal colors.


<details>
<summary>Supported Languages</summary>

| Language      | Syntax | Treesitter                     | Semantic     |
|---------------|--------|--------------------------------|--------------|
| Blade         | n/a    | ✅ (EmranMR/tree-sitter-blade) | n/a          |
| C/C++         | ⚠️     | ✅ (c,cpp)                     | n/a          |
| CSS           | ⚠️     | ✅ (css)                       | n/a          |
| EditorConfig  | n/a    | ✅ (editorconfig)              | n/a          |
| HTML          | ⚠️     | ✅ (html)                      | n/a          |
| JavaScript    | ⚠️     | ✅ (javascript)                | ✅ (ts_ls)   |
| JSON          | ✅     | ✅ (json)                      | n/a          |
| Lua           | ⚠️     | ✅ (lua,luadoc)                | ✅ (lua_ls)  |
| Markdown      | ⚠️     | ✅ (markdown,markdown_inline)  | n/a          |
| Nix           | ⚠️     | ✅ (nix)                       | ✅ (nil_lsp) |
| PHP           | ⚠️     | ✅ (php,phpdoc)                | n/a          |
| RegExp        | ⚠️     | ✅ (regex)                     | n/a          |
| Sass/SCSS     | ⚠️     | ✅ (scss)                      | n/a          |
| Shell Script  | ⚠️     | ✅ (bash)                      | n/a          |
| Twig          | n/a    | ✅ (twig)                      | n/a          |
| TypeScript    | ⚠️     | ✅ (typescript)                | ✅ (ts_ls)   |

</details>


<details>
<summary>Supported Plugins</summary>

| Plugin                                                                          | Source |
|---------------------------------------------------------------------------------|--------|
| [copilot.vim](https://github.com/github/copilot.vim)                            | n/a    |
| [fzf-lua](https://github.com/ibhagwan/fzf-lua)                                  | n/a    |
| [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)                     | n/a    |
| [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim) | n/a    |
| [neogit](https://github.com/NeogitOrg/neogit)                                   | n/a    |
| [nvim-notify](https://github.com/rcarriga/nvim-notify)                          | n/a    |
| [nvim-scrollbar](https://github.com/petertriho/nvim-scrollbar)                  | n/a    |
| [supermaven-nvim](https://github.com/supermaven-inc/supermaven-nvim)            | n/a    |

</details>

## Installation

Install the theme with your preferred package manager, such as
[folke/lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
return {
    "nickkadutskyi/jb.nvim",
    lazy = false,
    priority = 1000,
    opts = {},
    config = function()
        vim.cmd("colorscheme jb")
    end,
}
```

### Usage

```lua
vim.cmd("colorscheme jb")
```

```vim
colorscheme jb
```

## Configuration

n/a

## Overriding Colors & Highlight Groups

n/a

## Extras

n/a

## Contributing

n/a

# nvim-old

> **Older config, kept for reference.** My current Neovim setup is [AbiXnash/nvim](https://github.com/AbiXnash/nvim)
> (Neovim 0.12, lazy.nvim, the [Hell Pine](https://github.com/abxengg/hell-pine.nvim) colorscheme).

My earlier Neovim config, built on [AstroNvim](https://github.com/AstroNvim/AstroNvim) v4+ from its user template.

## What's in it

- AstroCommunity packs for Lua and Python, plus community plugins such as nvim-surround, the VS Code-style heirline
  winbar and codesnap (`lua/community.lua`)
- Plugin overrides in `lua/plugins/`: AstroCore, AstroLSP, AstroUI, cmp, conform, none-ls, nvim-lint, flash, fzf,
  neo-tree, gitsigns, nvim-ufo, rainbow-delimiters, toggleterm, treesitter, undotree, and React formatting
- Java settings in `lua/ftplugin/java.lua`
- `package.json`: the Node tools it expects (TypeScript language server, Angular language service, ESLint /
  eslint_d, Prettier), installed with `npm install`
- `.stylua.toml`, `selene.toml` and `neovim.yml` for linting the config itself

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```

#### Clone the repository

```shell
git clone https://github.com/AbiXnash/nvim-old ~/.config/nvim
```

#### Start Neovim

```shell
nvim
```

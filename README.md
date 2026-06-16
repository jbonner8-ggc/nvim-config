# jbonner8's Neovim Configuration

This is my personal Neovim configuration, forked from the excellent [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim).

It is designed to be a lightweight, highly functional, and fully documented setup tailored to my daily development workflow.

---

## Quick Start

### 1. Prerequisites

Ensure you have the latest stable Neovim (v0.10+) installed along with:

- **System Utilities**: `git`, `make`, `unzip`, and a C compiler (`gcc` / `clang`).
- **Search Tools**: [ripgrep](https://github.com/BurntSushi/ripgrep) and [fd-find](https://github.com/sharkdp/fd).
- **Parser**: [tree-sitter CLI](https://github.com/tree-sitter/tree-sitter).

### 2. Installation

Clone this configuration directly to your Neovim config directory:

```bash
git clone https://github.com/jbonner8-ggc/nvim-config.git ~/.config/nvim
```

Then launch Neovim:

```bash
nvim
```

Plugins will automatically download and install on first launch.

---

## My Customizations

This section tracks the active changes and configurations I've made to tailor Neovim for my development needs:

- **Branching Strategy**:
  - `main`: Keeps the baseline configuration clean and synchronized with upstream `kickstart.nvim`.
  - `personal-config`: Where my active personal customizations, specialized keymaps, and daily configurations live.
- **LSP & Telescope Keymaps**: Customized search and navigation keymaps (e.g., `<leader>s/` for live grep in open files, `grd` for Goto Definition, and `grt` for Goto Type Definition).
- **Repository Restructuring**: Standardized the primary development branch from `master` to `main`.
- **Upstream Synchronization**: Merged the latest upstream changes to benefit from performance and plugin updates.

---

## Upstream Documentation

For the original kickstart.nvim documentation, install recipes, or advanced troubleshooting, see the [original kickstart.nvim repository](https://github.com/nvim-lua/kickstart.nvim).

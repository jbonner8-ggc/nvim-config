<h1 align="center">jbonner8's Neovim Configuration</h1>

<p align="center">
  <a href="#quick-start">Quick Start</a> •
  <a href="#my-customizations">Customizations</a> •
  <a href="#upstream-documentation">Upstream Docs</a> •
  <a href="https://github.com/jbonner8-ggc/nvim-config">GitHub Repository</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/neovim-%3E%3D0.10-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim">
  <img src="https://img.shields.io/badge/lua-2C2D72?style=flat-square&logo=lua&logoColor=white" alt="Lua">
  <img src="https://img.shields.io/badge/license-MIT-8b5cf6?style=flat-square" alt="license">
  <img src="https://img.shields.io/badge/platform-linux%20%7C%20macos%20%7C%20windows-64748b?style=flat-square" alt="platform">
  <img src="https://img.shields.io/badge/fork-kickstart.nvim-6366f1?style=flat-square" alt="forked from kickstart.nvim">
</p>

<p align="center">
  A lightweight, single-file, and fully documented Neovim configuration,<br>
  tailored for my daily development workflow and forked from <a href="https://github.com/nvim-lua/kickstart.nvim">kickstart.nvim</a>.
</p>

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

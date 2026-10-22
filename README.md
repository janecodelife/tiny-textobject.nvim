# tiny-textobject.nvim

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-ea4aaa?style=for-the-badge&logo=github)](https://github.com/sponsors/janecodelife)

A lightweight, simple, and dependency-free Easily handle text objects (inner/around) without need for Tree-sitter.

---

## 🚀 Features

- **`if` (Inner Function):** Selects everything _inside_ the function braces (`{ ... }`), automatically trimming the top and bottom whitespace lines.
- **`af` (Around Function):** Selects the entire function block, including the function signature (`public function name()`, `class`, etc.) and the braces.
- **Smart Lookahead:** If your cursor isn't directly on a function block when you press `af`, it automatically searches forward for the next one.
- **No Treesitter required:** Perfect for lightweight setups or languages where Treesitter isn't fully configured.

---

💝 Support me by the only available way now: USDT to buy a new dev laptop. Info is below,
or contact me by 📩 email: janecodelife@gmail.com

## Thank You So Much

---

## 📦 Installation

```lua
vim.pack.add({
	"https://github.com/janecodelife/tiny-textobject.nvim",
})

require("tiny-textobject").setup()
```

## Video 📺

<p align="center">
  <a href="https://www.youtube.com/watch?v=jBUKpSBhoxI">
    <img src="./assets/tiny-textobject.png" alt="tiny-textobject" width="100%">
  </a>
</p>

---

## ⌨️ Mappings

The plugin maps text objects in both **Visual** (`x`) and **Operator-pending** (`o`) modes.

| Keymap | Mode     | Description                     |
| ------ | -------- | ------------------------------- |
| `vaf`  | Visual   | Select around the function      |
| `vif`  | Visual   | Select inside the function      |
| `daf`  | Operator | Delete around the function      |
| `dif`  | Operator | Delete inside the function      |
| `yaf`  | Operator | Yank (copy) around the function |
| `yif`  | Operator | Yank (copy) inside the function |
| `caf`  | Operator | Change around the function      |
| `cif`  | Operator | Change inside the function      |

---

## 💝🤟 Support the Project 🤟💝

<p align="center">
  <a href="https://github.com/sponsors/janecodelife">
    <img src="https://img.shields.io/badge/👉%20Become%20a%20Sponsor-GitHub%20Sponsors-ea4aaa?style=for-the-badge&logo=github" alt="Become a Sponsor on GitHub" />
  </a>
</p>

Every bit of support fuels the expansion of this ecosystem and helps me write cleaner tools for all of us. Thank you for standing behind independent developers!_ 🙏🤟

---

## 💝🤟 A huge thank you to our sponsors! 💝🤟

<!-- SPONSORS -->
<!-- SPONSORS -->

---

## 🔗 My Other Plugins

Check out my other open-source tools to supercharge your Neovim environment:

- **[livewire-secure-properties](https://github.com/janecodelife/livewire-secure-properties)** - Secure livewire app properties by default and void headache.
- **[todo-tracker.nvim](https://github.com/janecodelife/todo-tracker.nvim)** - Assign and list app todos in a blink
- **[folders-bookmark.nvim](https://github.com/janecodelife/folders-bookmark.nvim)** - Bookmark folders and accessing them by keymap in a blink
- **[copy-history.nvim](https://github.com/janecodelife/copy-history.nvim)** - Access your copy (Yank) history and paste it again with support of edit by 1 click in a blink.
- **[rest-client.nvim](https://github.com/janecodelife/rest-client.nvim)** - run http request from anywhere in a blink
- **[smart-window-focus.nvim](https://github.com/janecodelife/smart-window-focus.nvim)** - resize split window on focus to be full size to easy to see and debug.
- **[markdown-toc.nvim](https://github.com/janecodelife/markdown-toc.nvim)** - access markdown file headings (Table Of Content)
- **[tiny-textobject.nvim](https://github.com/janecodelife/tiny-textobject.nvim)** - handle text objects (inner/around) without need for Tree-sitter.

---

## If Have A Question 🤝 (Contact Me) 🤟

I will be there to answer to all messages

- **X (Twitter)**: [https://x.com/janecodelife](https://x.com/janecodelife)
- **YouTube**: [https://www.youtube.com/@JaneCodeLife](https://www.youtube.com/@JaneCodeLife)
- **Email**: [janecodelife@gmail.com](janecodelife@gmail.com)

[![Follow on X](https://img.shields.io/badge/Follow-@janecodelife-000000?style=for-the-badge&logo=x)](https://x.com/janecodelife)
[![Subscribe on YouTube](https://img.shields.io/badge/Subscribe-@JaneCodeLife-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@JaneCodeLife)

---

## Upcoming 🚀 (Stay Tuned!)

### The Ultimate Neovim Config for All Modern Web & Laravel Devs ⚡

# Thank You

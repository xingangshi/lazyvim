# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

[lazy.nvim 快速起步](https://cloud-atlas.readthedocs.io/zh-cn/latest/linux/desktop/nvim/lazy.nvim/lazy.nvim_startup.html)

## Install the LazyVim Starter

1. Make a backup of your current Neovim files:

```bash
# required
mv ~/.config/nvim{,.bak}

# optional but recommended
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}
```

2. Clone the starter

```bash
git clone https://github.com/xingangshi/lazyvim.git ~/.config/nvim

```

3. Remove the `.git` folder, so you can add it to your own repo later

```bash
rm -rf ~/.config/nvim/.git
```
4. Start Neovim!

```bash
nvim
```


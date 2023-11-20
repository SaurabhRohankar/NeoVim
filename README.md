# NeoVim

## Installation Instructions

### 1. Install ripgrep

```bash
sudo apt install ripgrep
```

### 2. Install Packer
Clone the Packer.nvim repository into the appropriate directory:

```bash
git clone --depth 1 https://github.com/wbthomason/packer.nvim \
~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

### 3. Run PackerSync
Navigate to the lua/saura/packer.lua file in your Neovim configuration and run the following command within Neovim:

```vim
:PackerSync
```
This will ensure that Packer installs and configures the specified plugins.

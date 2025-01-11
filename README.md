# 💤 LazyVim

My template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

# Make a backup of your current Neovim files:

## required

mv ~/.config/nvim{,.bak}

## optional but recommended

mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak}

# Clone the starter

git clone https://github.com/gustavocaldassouza/nvim-config ~/.config/nvim

# Windows

# required

Move-Item $env:LOCALAPPDATA\nvim $env:LOCALAPPDATA\nvim.bak

# optional but recommended

Move-Item $env:LOCALAPPDATA\nvim-data $env:LOCALAPPDATA\nvim-data.bak

git clone https://github.com/gustavocaldassouza/nvim-config $env:LOCALAPPDATA\nvim

# The important things

- Set to zsh, but still getting fish errors:
  - Turns out ~/.config/alacritty/alacritty.yml still had this set to `/bin/fish`

```
sudo pacman -S paru
sudo pacman -S yadm
sudo pacman -S 1password
sudo pacman -S neovim python-pynvim wl-clipboard
sudo pacman -S github-cli
sudo pacman -S waynergy-cli
```

Notes:

  - See ./waynergy.sh for how to run `waynergy-cli`.

# Development things

## dotfiles

```
cd ~/Development/projects && gh repo clone dotfiles
sudo pacman -S tree-sitter-cli
sudo pacman -S yaml-language-server
sudo pacman -S lua-language-server
sudo pacman -S marksman
sudo pacman -S typos
sudo paru -S prosemd-lsp
sudo paru -S efm-langserver
```

## Rust

```
sudo pacman -S rustup rust-analyzer bacon
```

## Ruby

```
paru -S chruby
echo 'source /usr/share/chruby/chruby.sh' >> ~/.zshenv
paru -S ruby-install
rehash
ruby-install 3
```

## Node

```
sudo pacman -S fnm
rehash
fnm install 18
fnm default 18
```

- Update shells
  - `eval "$(fnm env --use-on-cd)"`
  - `eval "$(fnm completions --shell zsh)"` to `.zshrc`

# Productivity

## CLI

```
sudo pacman -S zoxide exa ripgrep bat topgrade
cargo install zr
```

-- Update shells
  - `eval "$(zoxide init zsh)"`

## Communications

```
# sudo pacman -S slack-desktop
sudo pacman -S slack-electron
sudo pacman -S mailspring
sudo pacman -S tutanota-desktop-bin
```

# 3. Leisure things

# Install Cider for music

```
sudo pacman -S cider (from chronic-aur)
```

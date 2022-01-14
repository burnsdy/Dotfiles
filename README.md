# Dotfiles

### Configurations
Note: gitconfigs maintained separately across multiple devices
- Zsh
  - Customizable theme provided through [powerlevel10k](https://github.com/romkatv/powerlevel10k)
- NeoVim
  - Preconfigured with 20+ useful plugins
  - Has full backwards compatibility to Vim
- Tmux

### Installation
1. Install powerlevel10k theme: `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
2. Configure shell theme: `p10k configure`, then install the [recommended font](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
3. Symlink files to your home directory (through use of [Dotbot](https://github.com/anishathalye/dotbot)): `./install`
4. Install essential shell utilities: `./install_utils`
5. Configure Vim/NeoVim plugins: `nvim -c :PlugInstall`

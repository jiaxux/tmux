# Tmux Configuration

## Prerequisites

1. Install [Tmux Plugin Manager (TPM)](https://github.com/tmux-plugins/tpm):
   ```bash
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   ```

2. For tmux versions < 3.3:
   Create a symlink from `~/.config/tmux/tmux.conf` to `~/.tmux.conf`:
   ```bash
   ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
   ```

3. Reload tmux configuration:
   ```bash
   tmux source-file ~/.config/tmux/tmux.conf
   ```
   Or press `prefix + I` to install plugins via TPM.
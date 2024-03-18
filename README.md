# Tmux Configuration

Built initially from [typecraft's video](https://www.youtube.com/watch?v=jaI3Hcw-ZaA) on configuring Tmux.

## Installation

After cloning this repository, use a symbolic link to point Tmux to the configuration file inside it. Beware that the first command here will delete any existing Tmux configuration that is present. You may want to copy it to a backup location first, just in case.

```shell
rm -rf ~/.tmux.conf
ln -s $(pwd)/tmux-config/tmux.conf ~/.tmux.conf
```

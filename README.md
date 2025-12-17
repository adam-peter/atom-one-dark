# Atom One Dark for Tmux

A tmux theme using the [Atom One Dark](https://github.com/atom/atom/tree/master/packages/one-dark-syntax) color palette. Forked from [catppuccin/tmux](https://github.com/catppuccin/tmux).

## Installation

### TPM

1. Install [TPM](https://github.com/tmux-plugins/tpm)
2. Add the plugin:

```bash
set -g @plugin 'adam-peter/atom-one-dark'
set -g @plugin 'tmux-plugins/tpm'
```

### Manual

1. Clone this repo to `~/.tmux/plugins/atom-one-dark`
2. Add to your `~/.tmux.conf`:

```bash
run-shell ~/.tmux/plugins/atom-one-dark/atom-one-dark.tmux
```

3. Reload tmux: `tmux source-file ~/.tmux.conf`

## Configuration

Requires a [Nerd Font](https://www.nerdfonts.com/) for icons.

### Window tabs

```sh
set -g @atom_one_dark_window_tabs_enabled on
```

### Separators

```sh
set -g @atom_one_dark_left_separator "█"
set -g @atom_one_dark_right_separator "█"
```

### Date/Time

```sh
set -g @atom_one_dark_date_time "%Y-%m-%d %H:%M"
```

### User

```sh
set -g @atom_one_dark_user "on"
```

### Host

```sh
set -g @atom_one_dark_host "on"
```

## License

MIT

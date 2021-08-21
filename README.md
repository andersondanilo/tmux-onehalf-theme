# OneHalf color theme configuration for Tmux

Tmux OneHalf dark theme based on the vim theme https://github.com/sonph/onehalf

Note: For terminal with truecolors support

Screenshot with nvim with the theme from https://github.com/sonph/onehalf

<img src="https://i.imgur.com/WlUV0tu.png" title="Tmux grovbox dark colorscheme" style="width: 100%; " />

## Dependencies

- `set -g @plugin 'tmux-plugins/tmux-cpu' # *Plugin after theme (dont work before)`
- Patched nerd font (tested with DejaVuSansMono Nerd Font)


## Installation

### Install manually

Source or copy the code from `tmux-onehalf-dark.conf`

### Install through [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add plugin to the list of TPM plugins in `.tmux.conf`

```bash
set -g @plugin 'andersondanilo/tmux-onehalf-theme'
```

Hit `prefix + I` to fetch the plugin and source it. Your Tmux should be updated with the theme at this point.

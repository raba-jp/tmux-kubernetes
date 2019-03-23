# tmux-kubernetes

This plugin displays kubernetes current context above tmux status bar.

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm) (recommended)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'raba-jp/tmux-kubernetes'

Hit `prefix + I` to fetch the plugin and source it. You should now be able to
use the plugin.

### Manual Installation

Clone the repo:

    $ git clone https://github.com/raba-jp/tmux-kubernetes ~/clone/path

Add this line to the bottom of `.tmux.conf`:

    run-shell ~/clone/path/kube-context.tmux

Reload TMUX environment with: `$ tmux source-file ~/.tmux.conf`. You should now
be able to use the plugin.

### License
[MIT](https://github.com/rabafea/tmux-git-user/blob/master/LICENSE)

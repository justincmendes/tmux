
# tmux (config)

## Prerequisites

Have tmux installed:

    brew install tmux

**IMPORTANT:** make sure you have the latest version of bash installed (**v4.0+**)!

    brew install bash

`tmux-tokyo-night` uses Bash's (v4.0+) `declare -A` to define associative arrays.
See [this](https://stackoverflow.com/a/76405553) for more details.

And finally, you should know a bit about [tmux commands](https://tmuxcheatsheet.com/)
(`Prefix + ?` in a tmux session to see shortcuts).

Prefix in this config file is currently: `Control + Space`


## Setup

Run the following commands in your terminal:

Download the `.tmux.conf` file into `~/.tmux.conf`:

	wget https://raw.githubusercontent.com/justincmendes/tmux/main/.tmux.conf -O ~/.tmux.conf

Install tpm:

	git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

Open a tmux session:

	tmux

Then in your new tmux session (entered from `tmux`) enter the following:

	tmux source ~/.tmux.conf

If you see no output from the command above, that's good news!

All that's left is to install the tmux plugins:

`Prefix + I` (i.e. `Control + Space, Shift + i`)

And you're done! Enjoy your brand new tmux config :)

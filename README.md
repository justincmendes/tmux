# tmux (config)

## Prerequisites
Have tmux installed:
`brew install tmux`

**IMPORTANT:** make sure you have the latest version of bash or zsh installed!
`brew install bash`
`brew install zsh`

## Setup
Run the following commands in your terminal:

Download the `.tmux.conf` file into `~/.tmux.conf`:
`wget https://raw.githubusercontent.com/justincmendes/tmux/main/.tmux.conf -O ~/.tmux.conf`

Open a tmux session:
`tmux`

Then in your new tmux session (entered from `tmux`) enter the following:
`tmux source-file ~/.tmux.conf`

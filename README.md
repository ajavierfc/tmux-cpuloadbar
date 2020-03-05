# tmux-cpuloadbar
CPU load bar indicator for tmux pane

## configure
I created a symbolic link targeting /path/to/loadbar so I configured mine editing `~/.tmux.conf` and add/update lines like:
```
set -g status-right '#(loadbar)'
set -g status-interval 5

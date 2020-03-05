# tmux-cpuloadbar
CPU load bar indicator for tmux pane

## configure
I created a symbolic link targeting /path/to/loadbar so I configure mine editing ~/.tmux.conf and add/update your config like:
```
set -g status-right '#(loadbar)'
set -g status-interval 5

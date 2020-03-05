# tmux-cpuloadbar
CPU load bar indicator for tmux pane

## configure
You can create a symbolic link targeting /path/to/loadbar and therefore edit `~/.tmux.conf` and adding/updating lines like:
```
set -g status-right '#(loadbar)'
set -g status-interval 5
```

## preview
<img src='https://i.imgur.com/d7FponM.png'>

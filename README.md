# tmux CPU load bar
CPU load bar indicator for tmux pane

## Configure
You can create a symbolic link targeting /path/to/loadbar and therefore edit `~/.tmux.conf` adding/updating lines like:
```
set -g status-right '#(loadbar)'
set -g status-interval 5
```

## Preview
<img src='https://i.imgur.com/d7FponM.png'>

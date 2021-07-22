# tmux CPU load bar
CPU load bar indicator for the tmux bar

## Configure
Tmux will use this as en executable script, so place it wherever it's bin path accesible and give it execution grants.

You can create a symbolic link targeting /path/to/loadbar and therefore edit `~/.tmux.conf` adding/updating lines like:
```
set -g status-right '#(loadbar)'
set -g status-interval 5
```

## Preview
<img src='https://i.imgur.com/d7FponM.png'>

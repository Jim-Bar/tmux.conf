# How to use this tmux.conf

  - Clone the repository to `/etc/tmux` (create this directory)
  - Then in `/etc/tmux.conf` (create it if it does not exist), append:

```
# Load sub-tmux.conf file
source-file /etc/tmux/tmux.conf
```

Alternatively, do the same with `~/.tmux.conf` (only for the current user).

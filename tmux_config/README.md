
[0] close all tmux sessions

[1] touch .tmux.config in user home directory

[2] tmux


| Action                    | Shortcut                       |
|---------------------------|--------------------------------|
| Prefix                    | Ctrl + e                       |
| Reload the config file    | `r`                            |
| Split vertical            | `v`                            |
| Split horizontal          | `h`                            |
| Zoom                      | `z`                            |
| New window                | `c`                            |
| Go to window              | Shift + Arrow (↑ ↓ ← →)        |
| Rename window             | `$`                            |
| Kill window               | `&`                            |
| Rename a session          | `$`                            |
| Disconnect a session      | `d`                            |
| List all sessions         | `s`                            |
| List all sessions         | `tmux ls`                      |
| Go back to session        | `tmux a -t session_name`       |
| Create a session          | `tmux new -s "session_name"`   |
| Kill a session            | `tmux kill-session -t session_name` |



to load the config file manually 

[0] tmux

[1] tmux source-file ~/.tmux.config
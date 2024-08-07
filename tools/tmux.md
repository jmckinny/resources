# Tmux

## Session Management
- `tmux ls` (or tmux list-sessions)
- `tmux new -s session-name`
- `Ctrl-b d` Detach from session
- `tmux attach -t [session name]`
- `tmux kill-session -t session-name`
- `Ctrl-b c` Create new window
- `Ctrl-b d` Detach current client
- `Ctrl-b l` Move to previously selected window
- `Ctrl-b n` Move to the next window
- `Ctrl-b p` Move to the previous window
- `Ctrl-b & Kill` the current window
- `Ctrl-b ,` Rename the current window
- `Ctrl-b q` Show pane numbers (used to switch between panes)
- `Ctrl-b o` Switch to the next pane
- `Ctrl-b ?` List all keybindings

## Moving Between Windows
- `Ctrl-b n` (Move to the next window)
- `Ctrl-b p` (Move to the previous window)
- `Ctrl-b l` (Move to the previously selected window)
- `Ctrl-b w` (List all windows / window numbers)
- `Ctrl-b` window number (Move to the specified window number, the
- default bindings are from 0 -- 9)

## Tiling Commands
- `Ctrl-b %` (Split the window vertically)
- `CTRL-b "` (Split window horizontally)
- `Ctrl-b o` (Goto next pane)
- `Ctrl-b q` (Show pane numbers, when the numbers show up type the key to go to that pane)
- `Ctrl-b {` (Move the current pane left)
- `Ctrl-b }` (Move the current pane right)

## Make a pane its own window
- `Ctrl-b :` "break-pane"

## add to ~/.tmux.conf
- Ctrl-b | split window horizontal
- Ctrl-b - split window vertically
- Ctrl-b h select pane left
- Ctrl-b j select pane down
- Ctrl-b k select pane up
- Ctrl-b l select pane right

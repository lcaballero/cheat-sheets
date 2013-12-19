# tmux Cheat Sheet

## Creating Sessions

__Command__  | __Description__

`tmux new-session` | Creates a new session without a name. Can be shortened to tmux `new` or simply `tmux`.

`tmux new -s development` | Creates a new session called "development."

`tmux new -s development -n editor` | Creates a session named "development" and names the first window "editor".

`tmux attach -t develop.` | Attaches to a session named "development."

____________


## Default Commands for Sessions, Windows and Panes

__Command__  | __Description__

`PREFIX` `d` | Detaches from the session, leaving the session in the background.

`PREFIX` `:` | Enters Command mode.

`PREFIX` `c` | Creates a new window from within an existing tmux session.  Shortcut for `new-window`.

`PREFIX` `0..9` | Selects windows by number.

`PREFIX` `w` | Displays a selectable list of windows in the current session.

`PREFIX` `,` | Displays a prompt to rename a window.

`PREFIX` `&` | Closes the current window after prompting for confirmation.

`PREFIX` `%` | Divides the current window half vertically.

`PREFIX` `"` | Divides the current window in half horizontally.

`PREFIX` `o` | Cycles through open panes.

`PREFIX` `q` | Momentarily displays pane numbers in each pane.

`PREFIX` `x` | Closes the current pane after prompting for confirmation.

`PREFIX` `Space` | Cycles through the various pane layouts.


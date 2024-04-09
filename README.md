# Tmux Commands

- **Prefix key**: `ctrl space` ~~`ctrl + b`~~

## Create a New Window (Set as the Currently Active Window)

- `<prefix> c`

## Reload Tmux Environment

- `<prefix> I`
  > Reloads the Tmux environment

## Change Between Windows

- `<prefix> <window_number>`

  > Switches to the specified window number

  or

- `<prefix> n`
  > Switches to the next window
- `<prefix> p`
  > Switches to the previous window

## Move Windows

- `<prefix> :`
  - `swap-window -s 2 -l 1`
    > Moves a window to a new position in the window list. `-s` specifies the source window, and `-l` specifies the new position.

## Close a Window

- Kill all the panes inside; or
- `<prefix> &`
  > Closes the current window

## Manage Panes

- Split into panes horizontally

  - `<prefix> %`
    > Splits the current pane into two panes horizontally

- Split into panes vertically
  - `<prefix> "`
    > Splits the current pane into two panes vertically

## Navigate in the Panes

- `<prefix> <arrow_key>`
  > Navigates to different panes using arrow keys

## Swap Panes

- `<prefix> {`

  > Swaps the current pane with the previous one

  or

- `<prefix> }`
  > Swaps the current pane with the next one

## Toggle Panes

- `<prefix> q <pane_number>`
  > Displays pane numbers and allows you to switch to a specific pane

## Zooming into a Pane

- `<prefix> z`
  > Zooms into the current pane, making it full-screen

## Turning a Pane into a Window

- `<prefix> !`
  > Converts the current pane into a window

## Close a Pane

- `<prefix> x`
  > Closes the current pane

## Create a New Session

- `tmux`
  > Starts a new tmux session

## Create a New Session with a Name

- `tmux new -s my-session`
  > Starts a new tmux session with a specific name

## Whilst in Tmux

- `<prefix> : new-session`
  > Starts a new tmux session

## List Active Sessions

- `tmux ls`
  > (outside tmux) Lists all active tmux sessions
- `<prefix> s`
  > Lists all windows in the current session
- `<prefix> w`
  > Displays a preview of each window in the current session

## Attach to a Session

- `tmux attach`
  > Attaches to the most recently used tmux session
- `tmux attach -t my-session`
  > Attaches to a specific tmux session with the name "my-session" --

## Other Commands

- [Tmux Cheat Sheet](https://tmuxcheatsheet.com)

## Navigate in the Panes Using vim-tmux-navigator

- `ctrl h`
  > Left
- `ctrl j`
  > Down
- `ctrl k`
  > Up
- `ctrl l`
  > Right
- `ctrl \`
  > Previous split

## Switch windows

- `shift alt l`
  > Right
- `shift alt h`
  > Left

## Entering copy mode

- `<prefix> [`

## Entering copy mode

- `ctrl v space`
  or
- `V` or `v`

## Paste

- `<prefix ]`

## Ps.: You need to download a Nerd Font

[Nerd Fonts Releases](https://github.com/ryanoasis/nerd-fonts/releases/tag/v2.2.2)

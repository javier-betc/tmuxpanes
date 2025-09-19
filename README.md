setup:
in tmux, press Ctrl+B to enter tmux commands

press : to have it take a config line

enter this:
bind-key C-x setw synchronize-panes on \;  set-window-option status-bg red \; display-message "pane sync on"; bind-key M-x setw synchronize-panes off \;  set-window-option status-bg green \; display-message "pane sync off"

(if using the ahk script use this in it to enter e.g. tmuxpanes only)

usage:
Have some panes first with Ctrl+B " and / or Ctrl+B % (vertical and horizontal splits)

with Ctrl+B Ctrl+X all panes will type in at the same time

with Ctrl+B Alt+X sync is off

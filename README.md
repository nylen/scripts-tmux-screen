# scripts-tmux-screen

This package provides scripts that help manage `tmux` and `screen` sessions.

The scripts are packaged using `npm` for convenience.

## Installation

    sudo npm install -g scripts-tmux-screen

Similarly, to uninstall:

    sudo npm rm -g scripts-tmux-screen

## Scripts

### tmx

`tmx` is a wrapper for `tmux`.  Pass it a session name, and it will either
create that session, or attach to it, detaching any other clients.

### tmux-session

`tmux-session` is a wrapper for `tmux` that initializes a session and runs one
or more commands, each in its own window.

`tmux-session` requires tmux 1.7 or higher, for the `-l` (literal) option to
the `send-keys` command.

### More to come eventually!

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

### npmi

`npmi` is a wrapper for `npm install` that will automatically add the given
packages to the `package.json` file, then re-indent it using
[`json-align`](https://github.com/nylen/node-json-align).

    # To install package abcde:
    npmi abcde

### More to come eventually!

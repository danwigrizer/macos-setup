# `tmux`

```zsh
# tmux - the terminal multiplexer
brew update && brew install tmux
```

In case you want to tweak `tmux`:

> `tmux`:  
> Example configuration has been installed to: `/usr/local/opt/tmux/share/tmux`  
> Bash completion has been installed to: `/usr/local/etc/bash_completion.d`


# `tree`

Tree is a recursive directory listing command that produces a depth indented listing of files, which is colorized ala dircolors if the `LS_COLORS` environment variable is set and output is to `tty`. `tree` is, in many ways, a nicer `ls`.

Install it with:

```zsh
# tree - a recursive directory listing command that produces a depth indented listing of files
brew update && brew install tree
```

Here is an example of it in use:

```zsh
tree ~ -L 1
  /Users/<USER>
  ├── Desktop
  ├── Documents
  ├── Downloads
  ├── Library
  ├── Movies
  ├── Music
  ├── Pictures
  └── Public

  8 directories, 0 files
```

For more information, read: http://mama.indstate.edu/users/ice/tree/. 
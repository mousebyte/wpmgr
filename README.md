# wpmgr
nitrogen-based wallpaper manager script

## Installation and Usage
You will need [nitrogen](https://github.com/l3ib/nitrogen) in order for the script to work.
To install the script, just copy the main file (`wpmgr`) to a directory in your `PATH` and make it executable.
The zsh completion file (`_wpmgr`) can be installed anywhere on `fpath` (such as `/usr/share/zsh/functions/Completion/Linux`).
```
Usage: wpmgr COMMAND [ARG]

  -l                        list profiles
  -s, --save PROFILE        save current Nitrogen settings as a profile
  -r, --restore PROFILE     load a profile
  -d, --delete PROFILE      delete a profile
  -n, --new                 create a new profile in Nitrogen 

  -c, --next [PATTERN]      cycle forwards through profiles
  -C, --prev [PATTERN]      cycle backwards through profiles

If PATTERN is specified on the cycling commands, wpmgr will only cycle to profiles matching PATTERN.
```

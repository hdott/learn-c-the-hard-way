# Excercise 4 - Using a Debugger
> Presents _gdb_ and _lldb_ debuggers and main commands to be able to work with them.

## Notes:
- `gdb --args` > passes arguments to the program
- `thread apply all bt` > dump a backtrace for all threads
- `gdb --batch --ex r --ex bt --ex q --args` > run the program so that if it bombs, you get a backtrace
- `run [args]` > start program with [args]
- `break [file:]function` > set break point at [file:]function _shortcut: **b**_
- `backtrace` > dump a backtrace of the current calling stack _shortcut: **bt**_
- `print expr` > print the value of *expr* _shortcut: **p**_
- `continue` > continue runing the program _shortcut: **c**_
- `next` > next line, but step _over_ function calls _shortcut: **n**_
- `step` > next line, but step _into_ function calls _shortcut: **s**_
- `shell` > start a shell
- `clear` > clear a breaking point
- `info break`, `info watch` > show information about breakingpoints and watchpoints
- `attach pid` > attach to a running process so you can debug it
- `detach` > detach from process
- `list` > list out the next ten source lines

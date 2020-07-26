# Excercise 4 - Using a Debugger

## Notes:
- `gdb --args` > passes arguments to the program
- `thread apply all bt` > dump a backtrace for all threads
- `gdb --batch --ex r --ex bt --ex q --args` > run the program so that if it bombs, you get a backtrace
- `run [args]` > start program with [args]
- `break [file:]function` > set break point at [file:]function _shortcut: **b**_

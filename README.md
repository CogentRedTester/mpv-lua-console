# mpv-lua-console

A modified version of the in-built console.lua that provides a REPL to run Lua commands inside of mpv.

Currently in a completely unfinished place. Do not use.

## To Do List

- [X] Execute lines as lua code instead of mpv commands
- [X] Handle errors
- [X] Provide separate environment for executed code
- [X] Make all existing variables/functions local to prevent access
- [X] Make mp/mp.msg/mp.utils available in the environment
- [ ] Switch from using mpv message logs to a proper in-built logger
- [ ] Auto-complete variables/functions in the global environment
- [ ] Remove 'help' command, or add text from the lua manual.
- [ ] Auto-complete table entries
- [X] Provide shortcut for printing tables

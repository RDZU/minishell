
### Minishell
Recreate bash behavior

## Mandatory Part

- Display a prompt when waiting for a new command.
- Have a working history.
- Implement pipes (| character). The output of each command in the pipeline is connected to the input of the next command via a pipe.
- Handle environment variables ($VARIABLE) which should expand to their values.
- Handle $? which should expand to the exit status of the most recently executed foreground pipeline.
### Implement Redirections

- "<" should redirect input.
- ">" should redirect output.
- "<<" should be given a delimiter, then read the input until a line containing the delimiter is seen.
- ">>" should redirect output in append mode.

### Signals
- ctrl-C displays a new prompt on a new line.
- ctrl-D exits the shell.
- ctrl-\ does nothing.

### Builtins

-  echo with option -n
-  cd with only a relative or absolute path
-  pwd
- export
- unset
- env
- exit

<img src="https://github.com/RDZU/minishell/blob/main/img/minishell" alt="Minishell" border="0">

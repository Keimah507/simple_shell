# Simple Shell

## Description
Simple_shell is a command line interpreter, or shell. This shell, is intentionally minimal and has basic functionality.
Standard functions and sys calls used:
`acces, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.`

## Requirements

Simple_shell is designed to run in the `Ubuntu 14.04` linux environment. Compiled using the GNU compiler with flags
`-Wall, -Werror, -Wextra, and -pedantic.`

## Installation
- Clone this repository: `git clone: https://github.com/Keimah507/simple_shell.git`
- Use `cd simple_shell` to change directories into the repository.
- Compile using the command: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
- Run the shell in interactive mode: `./hsh`
- Or in non-interactive mode: `echo "pwd" | ./hsh`

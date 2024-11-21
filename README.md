# PIPEX
this is a 42 project that aims to mimic the behavior of the pipe operator in the shell. The program takes two commands and a file as arguments and executes the first command with the file as input and the second command with the output of the first command as input. Bonus part can handle multiple pipes and herdoc.

## Usage
```bash
make
./pipex infile cmd1 cmd2 outfile
```
or for bonus part:
```bash
make bonus
./pipex_bonus here_doc LIMITER cmd1 cmd2 ... cmdn outfile
```

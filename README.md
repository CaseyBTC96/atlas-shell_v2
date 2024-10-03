# Shell v2
Shell v2 is a project for Atlas which emulates the Unix shell `/bin/sh`.
Over 7days, I wrote this entire project from scratch.
You can compile via the Makefile, which will create the `hsh` executable.
commands can be piped in such as `echo "ls -la" | ./hsh`, or you can simply run `./hsh` and the program will ask for your input. You can exit the interactive mode with the `exit` command.

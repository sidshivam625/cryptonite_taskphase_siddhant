# Chaining commands
## Chaining with semicolon 
``;`` separates commands in a similar way to how Enter separates lines. Basically, when we hit Enter, our shell executes the typed command and, after that command terminates, it gives the prompt to input another command. The semicolon is analogous, just without the prompt and with us entering both commands before anything is executed.


## Your first shell script 

`bash` command is used to execute commands from a text file. 

Created a new file named `x.sh` and added the given arguments to it and saved it. Executed the file in terminal with `bash` command and got the flag.

![your first shell script](https://github.com/user-attachments/assets/8de3655d-91c6-42e9-9ff0-696f775d5674)

## Redirecting script output.

We know that ``|`` is used between one command's output and a different command's input. Therefore we can send the output of several programs to one command by using ``|``. 
piped the output of `x.sh` into `/challenge/solve` as directed and got the flag.



## Executable Shell Scripts

If the shell script file is executable , we can simply invoke it via its relative or absolute path without the use of `bash` command. 

Created a filed called`q4.sh` in `/home/hacker` . Executed it but it didnt execute directly. Checked the file permissions using `ls -l` and then used `chmod` to give execution permissions to user. Executed it succesfully to get the flag.

![executable shell scripts](https://github.com/user-attachments/assets/62bde483-6943-45dc-a28d-b97f1b833cbc)






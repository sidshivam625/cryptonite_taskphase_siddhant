# Practicing piping
## Redirecting Output
`stdout` is redirected to other files using `>`.
directed the calling of `PWN` using `echo` command to `COLLEGE` file to get the flag.

## Redirecting more output
output of any command can be redirected using `>`.

Redirceted the output of `/challenge/run` to `myflag` to get the flag.

## Appending output
`>>` used to append input to a file which already has existing data. It doesnot overwrite the exisitng data

## Redirecting errors

## Redirecting input
`<` is used to redircet input. The film to right of `<` contains the input which needs to be redirected to the command on left side of `<`.

Redirect the output of `echo COLLEGE` to `PWN` using `>` and the redirected it from `PWN` to `/challenge/run` as directed to get the flag

## Grepping stored results 
`grep`- used to find any content from a file.

redirected the output  of`/challenge/run` to `/tmp/data.txt` then used the `grep` function on `/tmp/data.txt` to find `pwn.college` and get the flag.

## Grepping live output. 

Standard output from the command to the left of the pipe will be connected to (piped into) the standard input of the command to the right of the pipe using `|` pipe operator . 
Only pipes standard output and not error

Ran the `/challenge/run` simultaneously with greping `pwn.college` using `|` to get the flag.




## Grepping errors
Learnt that ``>&`` can be used to redirect one file descriptor to another.
`2>& 1` will redirect standard error to standard error and then `|` can be used to pipe standard error. 




## Duplicating piped data with tee

The ``tee`` command, named after a "T-splitter" from plumbing pipes, duplicates data flowing through pipes to any number of files provided on the command line. This is helpful for debugging the commands.



## Writing to multiple programs
Learnt about the Process Substitution method which is used to feed the output of a process (or processes) into the stdin of another process using `>(command)`



## Split-piping stderr and stdout.

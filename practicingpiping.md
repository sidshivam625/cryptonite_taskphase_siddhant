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


## Grepping errors 

## Duplicating piped data with tee

## Writing to multiple programs

## Split-piping stderr and stdout.

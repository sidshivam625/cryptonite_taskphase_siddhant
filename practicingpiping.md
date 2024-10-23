# Practicing piping
## Redirecting Output
`stdout` is redirected to other files using `>`.
directed the calling of `PWN` using `echo` command to `COLLEGE` file to get the flag.

![redirecting output](https://github.com/user-attachments/assets/2dcdeb83-38de-4a68-aeca-b1c03e8a6c90)



## Redirecting more output
output of any command can be redirected using `>`.

Redirceted the output of `/challenge/run` to `myflag` to get the flag.

![redirecting more output](https://github.com/user-attachments/assets/0404574e-5711-456c-b580-c9d3f11a288f)


## Appending output
`>>` used to append input to a file which already has existing data. It doesnot overwrite the exisitng data

![appending output](https://github.com/user-attachments/assets/6ac007d5-65e1-4e00-8880-c3bfac8ed121)


## Redirecting errors

![redirecting errors](https://github.com/user-attachments/assets/40845699-e136-4518-b01f-423fda7f52ba)


## Redirecting input
`<` is used to redircet input. The film to right of `<` contains the input which needs to be redirected to the command on left side of `<`.

Redirect the output of `echo COLLEGE` to `PWN` using `>` and the redirected it from `PWN` to `/challenge/run` as directed to get the flag

![redirecting input](https://github.com/user-attachments/assets/d4c495b0-a0a5-4de8-ae2c-c231f34a3c91)


## Grepping stored results 
`grep`- used to find any content from a file.

redirected the output  of`/challenge/run` to `/tmp/data.txt` then used the `grep` function on `/tmp/data.txt` to find `pwn.college` and get the flag.

![grepping stored results](https://github.com/user-attachments/assets/23b4c793-74ab-4759-a728-f34adad362fe)

## Grepping live output. 

Standard output from the command to the left of the pipe will be connected to (piped into) the standard input of the command to the right of the pipe using `|` pipe operator . 
Only pipes standard output and not error

Ran the `/challenge/run` simultaneously with greping `pwn.college` using `|` to get the flag.


![grepping live output](https://github.com/user-attachments/assets/5541cc0c-3c0f-4b34-8c20-dd2af4c24f25)





## Grepping errors
Learnt that ``>&`` can be used to redirect one file descriptor to another.
`2>& 1` will redirect standard error to standard error and then `|` can be used to pipe standard error. 

![grepping errors](https://github.com/user-attachments/assets/30cde55a-b92f-4d15-8a7c-b3babd01b958)



## Duplicating piped data with tee

The ``tee`` command, named after a "T-splitter" from plumbing pipes, duplicates data flowing through pipes to any number of files provided on the command line. This is helpful for debugging the commands.

![duplicating piped data with teee](https://github.com/user-attachments/assets/e2b5ad5e-99dd-45f6-b68a-591183da07bd)




## Writing to multiple programs
Learnt about the Process Substitution method which is used to feed the output of a process (or processes) into the stdin of another process using `>(command)`

![writing to multiple programs](https://github.com/user-attachments/assets/f4b8d140-8ab1-4e97-af82-6f193b1217f6)



## Split-piping stderr and stdout.

![split piping stderr and std output](https://github.com/user-attachments/assets/ac4d4762-3634-4544-8621-85d11f91f65b)


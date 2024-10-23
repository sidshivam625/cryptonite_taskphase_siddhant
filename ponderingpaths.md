# Pondering paths
## The Root
Learnt that all filesystems start with ```/``` which is used to access a system's directories, files and programs.

Invoked ```/pwn``` to get the flag


## Program and  absolute paths
Learnt to access program using its absolute path .

Executed ```/challenge/pwn``` to get the flag.
## Position thy self 
Learnt that ```cd``` is used to change to another directory. 

Executed the ```/challenge/run```command to get the new directory. Switched to the new directory using ```cd```.
Executed ```/challenge/run``` again to get the flag

## Position elsewhere
Executed the ```/challenge/run```command to get the new directory. Switched to the new directory using ```cd```.
Executed ```/challenge/run``` again to get the flag.

## Position yet elsewhere
Executed the ```/challenge/run```command to get the new directory. Switched to the new directory using ```cd```.
Executed ```/challenge/run``` again to get the flag.

## implicit relative paths, from / 
Learnt that :
  A relative path is any path that does not start at root (i.e., it does not start with /).
  
  A relative path is interpreted relative to your current working directory (cwd).
  
  Your cwd is the directory that your prompt is currently located at.


Executed the ```/challenge/run```command to get the new directory. Switched to the new directory using ```cd```.
As given in the hint the relative path starts with c, so executed ```challenge/run``` to get the flag.

## explicit relative paths, from /

Learnt that ``` .``` symbol in a path represents the current directory.
This means that when we use `` ./ ``before a directory or file name, we're explicitly stating that we're referring to something in the current directory.
For example, if we're in the ``/challenge`` directory and want to refer to a file named example.txt, we could use:
example.txt (implicitly in the current directory)
./example.txt (explicitly in the current directory)
Both paths point to the same file, but the second one uses ``.`` to clarify that the file is in the current directory.


## implicit relative path
Linux explicitly avoids automatically looking in the current directory when you provide a "naked" path. 

Therefore after switching to `/challenge` as cwd, `run` argument isnt executed directly, rather it requires a relative path to be executed.



## home sweet home







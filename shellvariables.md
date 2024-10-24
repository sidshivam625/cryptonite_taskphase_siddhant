# Shell Variables
## Printing Variables
Learnt how the value of any variable can be printed using ``echo $``.
![printing variables](https://github.com/user-attachments/assets/6b50e9bf-d910-4ce2-bb85-39e4e9e00079)



## Setting Variables
Variable can be assigned a value using ``=``.
![setting variable](https://github.com/user-attachments/assets/f07d633a-77ed-494f-a576-fcb1ea6dc2ec)



## Multi word Variables
Quoting can be used to assign values having space between them.

![multi word variable](https://github.com/user-attachments/assets/6d5996d1-4220-4bb2-956f-a158c56da351)

## Exporting Variables
Variables assigned in one shell cannot be used in the other shell. They need  to be explicitly exported using the command ``export <variable>``

![exporting variables](https://github.com/user-attachments/assets/27ec6a1a-83b7-4a71-b789-69132821e08a)

## Printing exported variables

`env` command is used to access every exported variable set in my shell. 
executed the `env` command and looked for `flag` variable to get the flag. 
`env $` can be used to directly get variable without looking for it. 

![printing exported variables](https://github.com/user-attachments/assets/d7a63e63-2910-49e2-8472-83988c3a6a79)


## storing command output 
we can store output of any command to a variable using ``$()``.

![storing command output](https://github.com/user-attachments/assets/c0b378fa-7e09-437b-bb94-8d66d8e18c50)






## Reading input
``read`` can be used to input any value from the user and assign it to a variable.

![READING INPUT](https://github.com/user-attachments/assets/17d5029d-0473-4e94-b422-62668a2f6281)


## Reading files
We can redirect the output of any program as an input to the ``read <variable>`` command using ``<``.

![reading files](https://github.com/user-attachments/assets/e399021b-95a2-4880-97c6-0197e0429e5a)





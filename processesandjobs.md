# Processes and Jobs
## Listing Processes.
``ps aux`` or ``ps -ef`` can be used to list the running processes on the system.  

`/challenge/run` was renamed so listed all the running files to check for a similar one. Executed the file to get the flag.

![Listing processes](https://github.com/user-attachments/assets/ad1b90e6-abca-4efb-8d87-bf00a159af90)


## Killing Processes.
`kill` command is used to terminate processes. 
terminated the `/challenge/dont_run` command in order to execute `/challenge/run` and get the flag.

![killing process](https://github.com/user-attachments/assets/29681ee3-ea9e-481b-a8fa-fd8a487b8f3b)


## Interrupting Processes 
`CTRL+C` pauses whatever application is waiting for input and causes the application to exit. 

Interrupted the ``/challenge/run `` file to get the the flag.

![Intrupting programs](https://github.com/user-attachments/assets/ee2b9dc0-7eae-4dac-b534-4c64c50d6ec4)


## Suspending Processes 
Processes can be suspended to the background by pressing `CTRL+Z` in order to free up the terminal.

![suspending process](https://github.com/user-attachments/assets/92dc9636-5980-479a-ae6c-6eee7e6afd09)


## Resuming Processes 
`fg` command is an inbuilt command that is used to resume suspended processes. 
Suspended `/challenge/run` and then resumed it using `fg` to get the flag

![resuming process](https://github.com/user-attachments/assets/424c08b2-b97a-4a8a-9ee3-ee7453ffd424)


## Backgrounding Processes

``fg`` is used to resume a process in the foreground. We can also resume a process in the background using ``bg``. This allows the process to keep running, while giving the shell back to invoke more commands in the meantime. 

![backgrounding processes](https://github.com/user-attachments/assets/c9e5cdd7-d9d3-476a-a5cd-ec3dc2616b97)


## Foregrounding Processes. 
process which has been sent to background canbe foregrounded using `fg`.

![foregrounding procceses](https://github.com/user-attachments/assets/2e19f5ee-dd97-4e9f-a345-ab5aa622ef57)


## Starting Backgrounded processes. 

A proccess can be sent to background without suspending it by appending an `&` at the end.

![starting background process](https://github.com/user-attachments/assets/52c32e8e-7966-467f-96b0-c00f0db3f116)

## Process Exit codes

Every shell command, including every program and every builtin, exits with an exit code. This can be used  to check if the process succeeded in its functionality.


![process exit code](https://github.com/user-attachments/assets/5ce9d4eb-a8b5-45b2-a0d7-a10e48135214)


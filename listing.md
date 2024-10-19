# Listing Process
 ```ps``` command lists all running processes.
 
 ***"Standard" Syntax:*** In this syntax, you can use````-e```` to list "every" process and````-f```` for a "full format" output, including arguments. These can be combined into a single argument ````-ef````.
 
***"BSD" Syntax:*** In this syntax, you can use ````a```` to list processes for all users, ````x```` to list processes that aren't running in a terminal, and ````u```` for a "user-readable" output. These can be combined into a single argument aux.

Executed the ````ps```` command with ````-ef```` command to check all the running processes along with their path. Found and executed the process whose path contained the challenge directory and found the flag



# killing Process
kill command is used to stop a running process by executing kill PID

called the ps command to check all running processes and found the dont_run process. Noted its PID and executed the kill command. executed the /challenge/run process to  get the flag.


#

# Untangling Users


## Becoming root with su

Becoming root is a  common action that Linux users take, therefore there are two utilities used for this purposes: ``su`` and ``sudo``.
But`` su`` is an old method to elevate the user to root access. It checks for root password.

![becoming root with su](https://github.com/user-attachments/assets/2aa701c9-c9b5-41db-957a-83ccd029a711)




## other users with su
You can give any username as an arguement to`` su ``to switch to that user instead of root.

![other users with su](https://github.com/user-attachments/assets/7bacb641-98bd-4e35-bee3-cbe6702a3dd6)


## cracking passwords 
Learnt the use of the famous program`` John The Ripper``. 
SYNTAX : `` john <password file> ``
![cracking passwords](https://github.com/user-attachments/assets/1ee560cb-245c-4f10-9719-93385fad7c15)


## using sudo

``sudo`` defaults to running a command as root. ``sudo`` relies on policies that it checks to determine the user's authorization and run things as root. These policies are defined in ``/etc/sudoers``.

![using sudo](https://github.com/user-attachments/assets/4f85f3ea-4afb-4a80-b03d-ed8d262cd66a)


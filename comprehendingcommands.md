# comprehending commands
## cat: not the pet, but the command!
Learnt that cat is used for reading the contents of a file. It can also concatenate multiple files. 

Used ``` cat /flag``` command as directed to get the flag.

![cat](https://github.com/user-attachments/assets/e08a8ebf-0f0e-4f94-8bee-bffe6284a863)

## catting absolute paths
````cat```` can be used to read files outside cwd by specyfying absolute path of file as cat's argument.

![catting absolute paths](https://github.com/user-attachments/assets/55a6b7f4-5acc-4f00-bf2c-bf798d565ba2)


## more catting practice
The challenge restricted the use of ````cd```` command and forced to use the absolute path as arguement of ````cat````.

![more catting practice](https://github.com/user-attachments/assets/71bfe4fc-5797-44d8-a974-571ac6bdd0b2)



executed the ````cat```` command with the absolute path given and got the flag.

## grepping for a needle in a haystack 

````grep```` command is used to search for contents in a file
used ``grep`` command to search for ``pwn.college`` in the `/flag` file and found the flag.

![grepping needle hay](https://github.com/user-attachments/assets/a1c60d15-22f2-4b3d-ba50-290e5750cb1a)



## listing files

Learnt the use of ``ls ``which lists the contents of the cwd.
The challenge hid the flag in random file in the ``challenge`` folder. Used ``ls`` to find the file. 

![listing files](https://github.com/user-attachments/assets/c04e311d-1ecc-4245-bb7b-461f642e6778)



## touching files

``touch`` is used to create files. The challenge required us to create 2 files using ``touch``.

![touching files](https://github.com/user-attachments/assets/bce9acdc-5398-4054-a25e-fcf4b3ffd24c)



## removing files
``rm`` command is used to remove files. The challenge created a ``delete_me`` file which was required to be deleted using rm inorder to get the flag.

![removing files](https://github.com/user-attachments/assets/21758513-c417-409e-beec-05b68d8800b1)


## hidden files
Learnt that some files can be hidden from ``ls`` by simply putting ``.`` infornt of the filename.
Hidden files can be listed by using ``ls -a``.

![hidden files](https://github.com/user-attachments/assets/421803b9-ef40-4bcd-9144-fe9c1f8fd5e4)



## An epic filesystem quest

## making directories 
Learnt that ``mkdir ``can be used to create directories. Challenge specified to make a diretory and create a file in that. A file can then be created using ` touch` command as learnt earlier.

![making directories](https://github.com/user-attachments/assets/93121dde-42a6-466f-99d3-3cc6983ee7eb)


## finding files

![finding ](https://github.com/user-attachments/assets/312c63d4-0af5-4539-8947-84425f8daa9c)




## linking files

> A hard link is when you address your appartment using multiple addresses that all lead directly to the same place (e.g., Apt 2 vs Unit 2).

> A soft link is when you move appartments and have the postal service automatically forward your mail from your old place to your new place.
 
> Symbolic links are created with the ln command with the -s argument

> syntax :`` ln -s <target-file> <pointing-file>``

![linking files](https://github.com/user-attachments/assets/7b1694e9-691f-43b8-9e43-5e6c381c9ea7)



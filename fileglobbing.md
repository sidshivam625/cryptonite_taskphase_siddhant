# Matching with *
Leanrt that * can be used as a wildcard to shorten argumments by replacing that argument with any file that matches the pattern
It can be used to match any part of the file name inclduing any amount of charecters. 

Only typed `/ch*` to `cd` as directed to type 4 charecters only and executed `/challenge/run` to get the flag.

![matching with star](https://github.com/user-attachments/assets/babf9d82-1334-4cca-801a-da359275d5a2)

# Matching with ?
`?` works as a single charecter wildcard. 

Replaced c and l with `?` as directed to get the flag.

![matching with question mark](https://github.com/user-attachments/assets/d2cea7ed-97d1-4b16-9911-0740355f57c3)



# Matching with []
Learnt that ``[]`` is a limited form of ``?``, in that instead of matching any character, ``[]`` is a wildcard for some subset of potential characters and matches every character in that subset with the missing position.

![matching with bracket](https://github.com/user-attachments/assets/711d3c56-b1d0-4fff-9ccc-90b2fc2270e2)


# Matching paths with []   
`[]` can be used to glob path arguments also.
![globbing path with bracket](https://github.com/user-attachments/assets/2028e679-8244-4214-a405-d7101636acd2)


# Mixing globs
Used `[cep]` for globbing via the first charecter of the files and thenn used `*` to complete rest of the characters.

![mixing globs](https://github.com/user-attachments/assets/ff1bd613-b5e5-47c7-91f5-2e242c13b278)


# Exclusionary globbing
Learnt that ``!`` and ``^`` can be used inside`` []`` to exclude all files starting with letters which are in the ``[]``.

![exclusionary globbing](https://github.com/user-attachments/assets/eb10b3d4-fb2a-4a18-9d7a-b01bccbc2f3d)



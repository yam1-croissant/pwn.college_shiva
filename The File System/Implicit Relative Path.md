# Implicit Relative Path 

In this challenge we learn the use of "." for running commands

# My Solve 

## Flag:pwn.college{4Ggz77R1W0mP91UmxstHkO-YdHn.QXxUTN0wiNwAzNzEzW}

First i run "/" to check if a dir exists, when it does i change dir to "/". Then i change dir to /challenge.
At last i run "./run".

hacker@paths~implicit-relative-path:~$ /

bash: /: Is a directory

hacker@paths~implicit-relative-path:~$ cd /challenge

hacker@paths~implicit-relative-path:/challenge$ ./run

Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:

pwn.college{4Ggz77R1W0mP91UmxstHkO-YdHn.QXxUTN0wiNwAzNzEzW}

# What i Learned

Using "." to run commands when it lies in the same dir

# Reference

-none.

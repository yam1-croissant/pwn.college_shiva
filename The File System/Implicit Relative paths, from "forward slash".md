# Implicit Relative paths, from "/"

In this challenge we are to find the directory to run the following command "challenge/run", using the "/"

# My Solve

## Flag:pwn.college{M7_w691M99ySx9Gn92ErUdYJzXi.QX5QTN0wiNwAzNzEzW}

In this challenge we need to find a directory that does not start at a root.The relative path is interpreted with reference to the cwd(current working directory).
if we are expected to find a text file example - (/user/bin/meow.txt)

We can find this either by the command user/bin/meow.txt if our cwd is "/" 

or

by the command /bin/meow.txt if our cwd is "/user" and so on.

>hacker@paths~implicit-relative-paths-from-:~$ cd /

>hacker@paths~implicit-relative-paths-from-:/$ challenge/run

>Correct!!!

>challenge/run is a relative path, invoked from the right directory!

>Here is your flag:

>pwn.college{M7_w691M99ySx9Gn92ErUdYJzXi.QX5QTN0wiNwAzNzEzW}

## What I learned

Sometimes the directory is not at root so we will have to switch using / and run commands which according to the cwd

# Relative Paths from root
In this challenge we are asked to run the /challenge/run using a relative path

# My Solve

## Flag: pwn.college{8_3eM_DVJ3Ycv7_o5fhaBJbULJ0.QXwUTN0wiNwAzNzEzW}

First we execute "/" to check if dir exists, when we change directory to root.
From here we run ./challenge/run as it is an executable command where dir, challenge exists.


hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run

Correct!!!

./challenge/run is a relative path, invoked from the right directory!

Here is your flag:

pwn.college{8_3eM_DVJ3Ycv7_o5fhaBJbULJ0.QXwUTN0wiNwAzNzEzW}

# What I learned 

I learnt the different syntax where, ./challenge represent if a dir challenge exists in the cwd (relative path) , whereas
/challenge is an absolute path. 

I kept making an error with the syntax, like .challenge/run or i was doing ./run with my cwd as /challenge$

# Reference 

- none.
  

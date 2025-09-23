# Comparing Files

using diff command on 2 similar files to find the flag 

# My Solve 

## Flag: pwn.college{c5v9DAW54MEu3ptbkYoWUlYHRVY.01MwMDOxwiNwAzNzEzW}

hacker@commands~comparing-files:~$ cd /challenge

hacker@commands~comparing-files:/challenge$ ls

DESCRIPTION.md  decoys_and_real.txt  decoys_only.txt

hacker@commands~comparing-files:/challenge$ diff decoys_and_real.txt decoys_only.txt

39d38
< pwn.college{c5v9DAW54MEu3ptbkYoWUlYHRVY.01MwMDOxwiNwAzNzEzW}

# What I learnt

using the diff command specifies the all the differences betweent to files using 
a , c , d and < > to specify whats the change

# Reference 
-none.

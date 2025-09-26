# Exclusionary Globs 

Using inverted globs to find the flag

# My Solve 
## Flag: pwn.college{0VdgZl6_KledqIxVfjthFbAPy10.QX2IDO0wiNwAzNzEzW}

```
Connected!                                                                        
hacker@globbing~exclusionary-globbing:~$ ls /challenge/files
amazing      delightful   great       jovial    magical     pwning   splendid   victorious  youthful
beautiful    educational  happy       kind      nice        queenly  thrilling  wonderful   zesty
challenging  fantastic    incredible  laughing  optimistic  radiant  uplifting  xenial
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]*
You got it! Here is your flag!
pwn.college{0VdgZl6_KledqIxVfjthFbAPy10.QX2IDO0wiNwAzNzEzW}
hacker@globbing~exclusionary-globbing:/challenge/files$
```

# What I learnt

Just like complement, here ! and ^ can be used to find files etc, which DO NOT contain those letters in it

# Reference 

none.

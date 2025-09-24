# Linking files

Tricking the system into getting the flag using the symlinks

# My Solve

## Flag: pwn.college{oitfztJVw1TFzxHxZdqmwVkC-fD.QX5ETN1wiNwAzNzEzW}

hacker@commands~linking-files:~$ /challenge/catflag

About to read out the /home/hacker/not-the-flag file!

cat: /home/hacker/not-the-flag: No such file or directory

hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag

hacker@commands~linking-files:~$ /challenge/catflag

About to read out the /home/hacker/not-the-flag file!

pwn.college{oitfztJVw1TFzxHxZdqmwVkC-fD.QX5ETN1wiNwAzNzEzW}

# What I learnt 

using the command ln -s {original path} {linking path} links the 2 files 

# References

-none.

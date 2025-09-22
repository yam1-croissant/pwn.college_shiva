# Home sweet Home

Find the flag by stating the file as an argument in the command line

# My Solve

## Flag: pwn.college{crbmxJTH_y2XRNW0uccTLLniPNz.QXzMDO0wiNwAzNzEzW}


I had to follow the given criteria - 

  1. Your argument must be an absolute path.
  2.The path must be inside your home directory.
  3.Before expansion, your argument must be three characters or less.

Here argument is ~ which is /home/hacker, so i created a file using "touch" command in "~", because the flag gets pasted in a file in the home directory. After than i run the command 
"/challenge/run ~/m"

hacker@paths~home-sweet-home:~$ ls

Desktop

hacker@paths~home-sweet-home:~$ touch ~/f

hacker@paths~home-sweet-home:~$ /challenge/run ~/f

Writing the file to /home/hacker/f!
... and reading it back to you:
pwn.college{crbmxJTH_y2XRNW0uccTLLniPNz.QXzMDO0wiNwAzNzEzW}

## What I learnt

Understanding what an argument is and how to make a file using "touch" command

## Reference - 

Linux commands - for 'touch'

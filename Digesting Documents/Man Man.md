# Man Man

Need to find the hidden name for the manual for the command /challenge/challenge by reading the manual's manual

# My Solve 
## Flag: pwn.college{k6jKkg3IwmiadNZWpJWZGMr505N.QX2EDO0wiNwAzNzEzW}

```

hacker@man~searching-for-manuals:~$ man man
MAN(1)                Manual pager utils                MAN(1)

NAME
       man - an interface to the system reference manuals

SYNOPSIS
       man [man options] [[section] page ...] ...
       man -k [apropos options] regexp ...
       man -K [man options] [section] term ...
       man -f [whatis options] page ...
       man -l [man options] file ...
       man -w|-W [man options] page ...

DESCRIPTION
       man  is  the system's manual pager.  Each page argument

hacker@man~searching-for-manuals:~$  man -k /challenge/challenge
kjkgwmiadp (1)       - print the flag!
hacker@man~searching-for-manuals:~$ man kjkgwmiadp
hacker@man~searching-for-manuals:~$ /challenge/challenge --kjkgwm 635
Correct usage! Your flag: pwn.college{k6jKkg3IwmiadNZWpJWZGMr505N.QX2EDO0wiNwAzNzEzW}
```

# What I learnt 

we can use man -k to find the manual for a given command

# Reference 

-none.

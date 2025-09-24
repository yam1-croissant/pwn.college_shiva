# Reading Manuals 

Undestanding commands via the man command to find the right argument to get the flag

# My Solve 

## Flag: pwn.college{oRXgjdDBHE1UAE6RCacUxCe1FaG.QX0EDO0wiNwAzNzEzW}



hacker@man~reading-manuals:~$ man challenge

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --ogjdac NUM
              print the flag if NUM is 161

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                                    May 2024                                   CHALLENGE(1)
~


hacker@man~reading-manuals:~$ /challenge/challenge --ogjdac 161
Correct usage! Your flag: pwn.college{oRXgjdDBHE1UAE6RCacUxCe1FaG.QX0EDO0wiNwAzNzEzW}

# What I learnt 

Reading carefuly the manual of commands 

# Reference  

none.

# Reading Files

# My Solve 
## Flag : pwn.college{o-hmudqyT_z4m4xsIbBMqHAwah8.QXwIDO0wiNwAzNzEzW}
```
Connected!                                                                        
hacker@variables~reading-files:~$ echo "/challenge/read_me" > flag
hacker@variables~reading-files:~$ read PWN < flag
You invoked 'read', but it looks like you didn't redirect the 
/challenge/read_me file to it!
You've set the PWN variable, but not to the correct value. Set it to the 
contents of /challenge/read_me by using input redirection and the 'read' 
builtin.
hacker@variables~reading-files:~$ echo "/challenge/read_me" > PWN
You've set the PWN variable, but not to the correct value. Set it to the 
contents of /challenge/read_me by using input redirection and the 'read' 
builtin.
hacker@variables~reading-files:~$ read PWN < /challenge/read_me
You've set the PWN variable properly! As promised, here is the flag:
pwn.college{o-hmudqyT_z4m4xsIbBMqHAwah8.QXwIDO0wiNwAzNzEzW}
hacker@variables~reading-files:~$
```

# What I learnt 
reading files using the read (built in cmd) and redirecting input

# References 

none.

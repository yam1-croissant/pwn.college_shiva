# Exporting Variables

# My Solve 
## Flag: pwn.college{ApEL23Nurq2iPdilBvtJT60Dyhv.QXyYTN0wiNwAzNzEzW}
```
Connected!                                                                        
hacker@variables~exporting-variables:~$ PWN=COLLEGE
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ export PWN
You've set the PWN variable to the proper value!
hacker@variables~exporting-variables:~$ COLLEGE=PWN
You've set the PWN variable to the proper value!
You've set the COLLEGE variable to the proper value!
hacker@variables~exporting-variables:~$ sh
sh-5.2$ /challenge/run PWN
CORRECT!
You have exported PWN=COLLEGE and set, but not exported, COLLEGE=PWN. Great 
job! Here is your flag:
pwn.college{ApEL23Nurq2iPdilBvtJT60Dyhv.QXyYTN0wiNwAzNzEzW}
sh-5.2$
```

# What I learnt 

sh opens a mini shell where u can execute commands, and if we want variables we set to run in that mini shell then we need to export them before running them.

# Reference 

none.

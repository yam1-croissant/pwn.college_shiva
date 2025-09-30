# Duplicating piped data with tee 

# My Solve 
## Flag: pwn.college{oMt9luza1Sgt3MfSfB4GuqINiDV.QXxITO0wiNwAzNzEzW}

```
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee cmd1 | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat cmd1
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "oMt9luza"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret oMt9luza | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{oMt9luza1Sgt3MfSfB4GuqINiDV.QXxITO0wiNwAzNzEzW}
```

# What I learnt 

using the tee command between the | operator saves the data in a file, helps in finding bugs

# Reference 

none.

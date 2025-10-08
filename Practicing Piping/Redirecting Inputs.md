# Redirecting Inputs

# My solve 
## Flag: pwn.college{wkceM6PJB93FZRf5h_a3nWyve-R.QXwcTN0wiNwAzNzEzW}
```
Connected!                                                                        
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read 
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{wkceM6PJB93FZRf5h_a3nWyve-R.QXwcTN0wiNwAzNzEzW}
```
# What I learnt

Redirecting input using <, Normally, a program takes input from your keyboard.
You can redirect it to read from a file instead. so here we first redirected the output (college) to the file PWN, then we took the file PWN as the INPUT for the command /challenge/run [command < input_file]

# References 
none.

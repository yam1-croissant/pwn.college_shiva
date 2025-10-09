# Changing File Ownership

# My Solve 
## Flag:pwn.college{wJs4jDQw0C0Y7S9y0gimHhd4hs3.QXxEjN0wiNwAzNzEzW}

```
hacker@permissions~changing-file-ownership:~$ chown hacker /flag
hacker@permissions~changing-file-ownership:~$ /flag
bash: /flag: Permission denied
hacker@permissions~changing-file-ownership:~$ cat /flag
pwn.college{wJs4jDQw0C0Y7S9y0gimHhd4hs3.QXxEjN0wiNwAzNzEzW}
```

# What I learnt 

Chown command is used to change the ownership of a file, usually this command is accessible only if you are root 

# Reference 
none.

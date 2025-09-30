# Spliting Piping Stderr and Stdout

# My Solve
## Flag: pwn.college{MWDJCezUbP9le7C7stK8a6J3ktb.QXxQDM2wiNwAzNzEzW}

```
Connected!                                                                        
hacker@piping~split-piping-stderr-and-stdout:~$ /challenge/hack > >( /challenge/planet ) 2> >( /challenge/the )
Congratulations, you have learned a redirection technique that even experts 
struggle with! Here is your flag:
pwn.college{MWDJCezUbP9le7C7stK8a6J3ktb.QXxQDM2wiNwAzNzEzW}
```

# What I learnt 
the | operator links the stdout of the left command with the stdin of the right command and 2> redirects errors of /challenge/hack to /challenge/the

# Reference 

none.

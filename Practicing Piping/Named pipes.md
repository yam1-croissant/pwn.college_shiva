# Named Pipes 

# My solve 
## Flag: pwn.college{glkNMbE0Q699DFunUKgp8fC-I7C.01MzMDOxwiNwAzNzEzW}

```
Terminal 1 -

Connected!                                                                        
hacker@piping~named-pipes:~$ mkfifo /tmp/flag_fifo
hacker@piping~named-pipes:~$ /challenge/run > /tmp/flag_fifo
You're successfully redirecting /challenge/run to a FIFO at /tmp/flag_fifo! 
Bash will now try to open the FIFO for writing, to pass it as the stdout of 
/challenge/run. Recall that operations on FIFOs will *block* until both the 
read side and the write side is open, so /challenge/run will not actually be 
launched until you start reading from the FIFO!
^C^C
hacker@piping~named-pipes:~$ cat flag_fifo
cat: flag_fifo: No such file or directory
hacker@piping~named-pipes:~$ cat /tmp/flag_fifo
^C
hacker@piping~named-pipes:~$ /challenge/run
The stdout of /challenge/run does not seem to point to a FIFO!
hacker@piping~named-pipes:~$ /challenge/run > /tmp/flag_fifo
You're successfully redirecting /challenge/run to a FIFO at /tmp/flag_fifo! 
Bash will now try to open the FIFO for writing, to pass it as the stdout of 
/challenge/run. Recall that operations on FIFOs will *block* until both the 
read side and the write side is open, so /challenge/run will not actually be 
launched until you start reading from the FIFO!


Terminal 2 -
hacker@piping~named-pipes:~$ cat /tmp/flag_fifo
You've correctly redirected /challenge/run's stdout to a FIFO at 
/tmp/flag_fifo! Here is your flag:
pwn.college{glkNMbE0Q699DFunUKgp8fC-I7C.01MzMDOxwiNwAzNzEzW}
```

# What I learnt

we will have to unblock the pipe, by running the command in a diff terminal

# Reference 

none.

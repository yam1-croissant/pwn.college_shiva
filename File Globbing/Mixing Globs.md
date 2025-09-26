# Mixing Globs
Using the globs we learnt to curate from the given files to find the flag

# My Solve 

## Flag: pwn.college{0HszkgHW1y0OEDd40XLuijmUWW8.QX1IDO0wiNwAzNzEzW}

```
Connected!                                                                        
hacker@globbing~mixing-globs:~$ ls /challenge/files
amazing      delightful   great       jovial    magical     pwning   splendid   victorious  youthful
beautiful    educational  happy       kind      nice        queenly  thrilling  wonderful   zesty
challenging  fantastic    incredible  laughing  optimistic  radiant  uplifting  xenial
hacker@globbing~mixing-globs:~$ cd /challenge/files
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run c*n*g*
Error: you did not use a square bracket glob...
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [c*n*g]*
Error: your argument is too long! It must be 6 characters or less.
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [c*g]
Your expansion did not expand to the requested files (challenging, educational, 
pwning). Instead, it expanded to:
[c*g]
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [epc]*
You got it! Here is your flag!
pwn.college{0HszkgHW1y0OEDd40XLuijmUWW8.QX1IDO0wiNwAzNzEzW}
hacker@globbing~mixing-globs:/challenge/files$
```
# What I learnt - 

To find files using globs, we dont need to break head thinking of which letters are unique to the words relative to the other files which would take much longer, instead its best to use [abc] and mention the starting letters of the files and then the * glob will generate the rest of the file name

# Reference - 
none.

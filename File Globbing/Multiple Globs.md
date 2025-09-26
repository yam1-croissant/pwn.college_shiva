# Multiple Globs 

# My Solve 

## Flag:pwn.college{I1H2t2cvrOy3TJGIi1hvxvve2-q.0lM3kjNxwiNwAzNzEzW}

```
hacker@globbing~multiple-globs:~$ ls /challenge/files
amazing      delightful   great       jovial    magical     pwning   splendid   victorious  youthful
beautiful    educational  happy       kind      nice        queenly  thrilling  wonderful   zesty
challenging  fantastic    incredible  laughing  optimistic  radiant  uplifting  xenial
hacker@globbing~multiple-globs:~$ cd /challenge/files
hacker@globbing~multiple-globs:/challenge/files$ /challenge/run /*p
Your expansion did not expand to the requested files (happy optimistic pwning 
splendid uplifting).
Instead, it expanded to:
/tmp
hacker@globbing~multiple-globs:/challenge/files$ /challenge/run *p*
You got it! Here is your flag!
pwn.college{I1H2t2cvrOy3TJGIi1hvxvve2-q.0lM3kjNxwiNwAzNzEzW}
```
# What I learnt 

using multiple globs 

# Reference 

none.

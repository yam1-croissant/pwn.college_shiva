# Position yet elsehwhere
Challenge asks you to find the right directory to run the command "/challenge/run".

#My Solve

##Flag:pwn.college{I3teZR0MTA8PCDgPDruy9oPVezY.QX4QTN0wiNwAzNzEzW}

First we run the command "/challenge/run", we are then met with a error, stating the appropriate directory to run the following command, which happens to be /usr/include.
Once we change the working directory to the one instructed, and run the command we are get the flag.

hacker@paths~position-yet-elsewhere:~$ /challenge/run

Incorrect...
You are not currently in the /usr/include directory.

hacker@paths~position-yet-elsewhere:~$ cd /usr/include

hacker@paths~position-yet-elsewhere:/usr/include$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{I3teZR0MTA8PCDgPDruy9oPVezY.QX4QTN0wiNwAzNzEzW}

# What I learned 
 
The command 'cd' changes the working directory which allows us to view folders inside or even run commands

# Reference

-none

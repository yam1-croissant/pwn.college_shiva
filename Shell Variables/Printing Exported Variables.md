# Printing Exported Variables

# My Solve 
## Flag: pwn.college{EIfP0KHRbC3-M8R48Y7RYwwUJ0V.QX4UTN0wiNwAzNzEzW}
```
Connected!                                                                        
hacker@variables~printing-exported-variables:~$ env
SHELL=/run/dojo/bin/bash
HOSTNAME=variables~printing-exported-variables
PWD=/home/hacker
MANPATH=/run/dojo/share/man:
DOJO_AUTH_TOKEN=600ad53aeff134db301276f46234503f624452dc2e86548f4edabc1b962f80d5
HOME=/home/hacker
LANG=C.UTF-8
FLAG=pwn.college{EIfP0KHRbC3-M8R48Y7RYwwUJ0V.QX4UTN0wiNwAzNzEzW}
TERMINFO=/run/dojo/share/terminfo
TERM=xterm-kitty
SHLVL=2
LC_CTYPE=C.UTF-8
SSL_CERT_FILE=/run/dojo/etc/ssl/certs/ca-bundle.crt
PATH=/run/challenge/bin:/run/dojo/bin:/root/.cargo/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
DEBIAN_FRONTEND=noninteractive
_=/run/dojo/bin/env
hacker@variables~printing-exported-variables:~$
```
# What I learnt 

env is a command that prints all variables that are exported 

# References

none.

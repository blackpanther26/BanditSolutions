# level13
- ssh bandit13@bandit.labs.overthewire.org -p 2220
- password : ```wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw```
- ls
> we get our sshkey.private from here
- ssh -i sshkey.private bandit14@localhost -p 2220
> The -i option specifies the identity file (private key) to be used for authentication. In this case, sshkey.private is the private key file. This file is used to authenticate the user to the server without needing to enter a password.
> bandit14@localhost part specifies the user and host you're connecting to. bandit14 is the username, and localhost is the hostname.
- cd /etc/bandit_pass
- ls
- cat bandit14
- password : ```fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq```
- exit

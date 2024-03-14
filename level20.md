# level 20
- ssh bandit20@bandit.labs.overthewire.org -p 2220
- password : ```VxCazJaVykI6W36BkBU0mJTCM8rR95XT```
- ls
- ./suconnect
- echo "`VxCazJaVykI6W36BkBU0mJTCM8rR95XT" | nc -lp 4000 &
> - the command starts a TCP server that listens on port 4000 and sends the string VxCazJaVykI6W36BkBU0mJTCM8rR95XT
> - &: This puts the command in the background, allowing us to continue using the terminal while the server is running.
- ./suconnect 4000
- password : ```NvEJF7oVjkddltPSrdKEFOllh9V1IBcq```
- exit

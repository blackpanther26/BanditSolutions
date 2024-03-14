# level 16
- ssh bandit16@bandit.labs.overthewire.org -p 2220
- password : ```JQttfApK4SeyHwDlI9SXGR50qclOAil1```
- nmap -sV localhost -p 31000-32000
> Nmap is a network scanner. It can do Host Discovery, Port Scanning, Version Detection (Service Detection) and a lot more. For this task, the -p flag is important. This flag lets us choose which ports to scan. The -sV flag lets us do a service/version detection scan.
- openssl s_client -connect localhost:31790
> nmap gives us 5 ports , we check each of them by changing the port number in the abouve command , and finally we find 31790 is the correct port , which gives us a private key on entering the previous level password . this private key is now used to login to next level.
- mkdir /tmp/random_sshkey
- cd /tmp/random_sshkey
- touch bandit17.key
- nano bandit17.key
- ssh -i bandit17.key bandit17@localhost -p 2220
- exit

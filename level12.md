# level12
- ssh bandit12@bandit.labs.overthewire.org -p 2220
- password : ```JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv```
- ls
- mkdir /tmp/misty
- cp data.txt /tmp/misty
> copies data.txt to the directory /tmp/misty
- cd /tmp/misty
- ls
- xxd -r data.txt > dara
> Use xxd to convert the hex dump back to text 
- file dara
> to know the type of file 
- mv dara dara.gz
> to avoid Overwriting Existing Files
- gunzip dara.gz
> to unzip gzip files we use gunzip 
- ls
- file dara
- mv dara data.bz2
- bunzip2 data.bz2
> to unzip bzip2 compressed files
- ls
- file data
- mv data data.gz
- gunzip data.gz
- ls
- file data
> data: POSIX tar archive (GNU)
- mv data data.tar
- tar -xf data.tar
> to decompress the archive
- ls
- file data5.bin
- mv data5.bin data5.tar
- tar -xf data5.tar
- ls
- file data6.bin
- mv data6.bin data6.bz2
- bunzip2 data6.bz2
- ls
- file data6
- mv data6 data6.tar
- tar -xf data6.tar
- ls
- file data8.bin
- mv data8.bin data8.gz
- gunzip data8.gz
- ls
- file data8
- cat data8
- password : ```wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw```
- exit

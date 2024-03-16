# level5
- ssh bandit5@bandit.labs.overthewire.org -p 2220
- password :```lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR```
- ls
- cd inhere
- find . -type f -size 1033c -exec cat {} \;
> - This initiates the ```find``` command is used to locate files and directories based on various criteria.
> - The ```.``` specifies the starting point for the search, which is the current working directory.
> - ```-type f``` telling find to only search for regular files (not directories, symbolic links, etc.).
> - ```-size``` is an option for find that allows you to search based on file size.
> - ```1033c``` indicates a size of exactly 1033 bytes. The c at the end signifies that the size is specified in bytes.
> - ```-exec``` tells find to execute a command for each matched file.
> - ```cat``` : This is a common command-line utility used to display the contents of a file on the terminal.
> - ```{}``` : This acts as a placeholder that gets replaced with the actual filename found by find for each iteration.
> - ```;``` : This is the command terminator for find.
- password : ```P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU```
- exit

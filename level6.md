# level6
- ssh bandit6@bandit.labs.overthewire.org -p 2220
- password : ```P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU```
- find / -user bandit7 -group bandit6 -size 33c -exec cat {} \; 2>/dev/null
> - ```find /``` : This initiates the find command, instructing it to search for files and directories starting from the root directory (/). This searches the entire system.
> - ```-user bandit7``` : This option narrows the search to files owned by the user named "bandit7". The user who owns a file has the most control over its permissions.
> - ```-group bandit6``` : This further restricts the search to files where the primary group is "bandit6".
> - ```-size 33c``` : include only files that are exactly 33 bytes in size. The c at the end signifies that the size is specified in bytes.
> - ```2>/dev/null``` : This redirects the standard error (STDERR) stream of the command to ```/dev/null``` .
> - > - Standard error is where error messages from the command are typically written (e.g., permission issues, non-text files).
> - > - /dev/null is a special file that discards any data written to it, essentially hiding any errors that might occur during the execution.
- password : ```z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S```
- exit

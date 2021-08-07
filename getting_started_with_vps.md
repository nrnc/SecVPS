### Using the command line to get around our VPS

- pwd *print working directory*
- cd *change directory*
- ls *list all the files and folders in the current working directory*
- ls -l *list the files in long format*
- ls -l | more *result of ls -l piped into more program*
- drwxr-xr-x *d stands for directory r stands for read permission w stands for write permission x stands for executable permission*
- rm -rf *r stands for recursively delete f stands for forcely delete*
  
### Adding and deleting user files and ownership

- sudo userdel <username>username

### File Permissions

7 - read write and executable to true
6 - read write to true
5 - read and executable to true
4 - read to true

chmod 444 test.txt - **change the permission of owner group and everyone to readable, first digit corresponds to owner, second to group and third to everyone**

### [linux chmod permissions cheet sheet](https://isabelcastillo.com/linux-chmod-permissions-cheat-sheet)

- sudo chown <user>:<group> <filename> *change ownershipt*

### [vi cheet sheet](https://www.thegeekdiary.com/basic-vi-commands-cheat-sheet/)

- cp copying the file
- mv moving the files
- scp secure copy

# My lecture note
***note***: This note is written for study about shell command 
### pwd
----------------------------------------------
```sh
$ pwd
/home/yoohyunseok
```
This command shows the current path in a hierarchical directory.
### cd
----
```sh
$ cd path
```
This command change current path.
### ls
```sh
$ ls
```
This command shows lists files and directories in current path.
```sh
$ ls -l
$ ls -lh
```
-l: option can show detailed information. for example, files and directories authorization.
-lh: same as -l but size i units
### @@Tip
Autocompletion: "Tab" key
Past command: "up arrow"
### clear
```sh
$ clear
```
This command literally clear the shell.
### cp
```sh
$ cp file_name1 or directory_name1 file_name2 or directory_name2
```
This command copy files and directories. copy file1 to file2
### mv
```sh
$ mv file_name1 or directory_name1 file_name2 or directory_name2
```
This command moves files and directories or rename them. file1 to file2
### rm
```sh
$ rm file_name or directory_name
$ rm -r file_name or directory_name
```
This command remove file and directory completely. -r option can remove directory along with its contents
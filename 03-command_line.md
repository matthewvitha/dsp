# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  
"""

¥	show current working directory path —> pwd 
¥	creating a directory —> mkdir [options] <Directory>
¥	deleting a directory —> rmdir [options] <Directory> 
¥	creating a file using touch command —> touch [options] <filename>
¥	deleting a file —> rm [options] <file>
¥	renaming a file —> mv [options] <source> <destination>
¥	listing hidden files ls -a
¥	copying a file from one directory to another —> cp [options] <source> <destination>
¥	Look up manual page for command —> man <command>
¥	changing directory - cd

"""





---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

"""
ls: l
ist current contents of directory 

ls -a: 
list all files including hidden file starting with '.'


ls -l: 
list with long format - show permissions


ls -lh: 
list long format with with human readable format

ls -lah: 
long list format showing hidden files in human readable format  

ls -t: 
 lists the files in order of the time when they were last modified (newest first) rather than in alphabetical order.

ls -Glp: 
not sure

"""

---

### Q3.  More List Files in Unix  

""""

ls -R
ls -1
ls -t
ls -x
ls -c 

"""
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

### The X args command takes input from stdin and executes command over the input. An example of how to use it is with the "find" and "grep" command to identify a certain type of file in a directory, and then identify a specified string amongst those files in the directory. 

 


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

'pwd': show current working directory path
'mkdir dirname': make directory
'rm dir': deleting a directory
'touch filename': creating a file using `touch` command
'rm filename': deleting a file
'mv oldname newname': renaming a file
'ls -a': listing hidden files
'cp filename directory_path': copying a file from one directory to another
'cd ..': change directory up one directory
'ls': list all files in current directory

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

`ls`: show all files in current directory 
`ls -a`: list all files including hidden files
`ls -l`: list with long format including permissions
`ls -lh`: list with long format and readable file size
`ls -lah`: list with long format and readable file size and include hidden files   
`ls -t`: list in order, sorted by time and date
`ls -Glp`: list in long format and including directory indicator (/) and color coding for directories 

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

`ls -c`
`ls -C`
`ls -f`
`ls -R`
`ls -t`

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

Xargs reads data from standard input and executes the command one or more times based on the input that is read. An example of this would be:
'xargs find -name'
Using the above command, you can then feed input that will automatically search the current directory for files of that name. If you enter "*.py", it will return all python files from the current directory.
 


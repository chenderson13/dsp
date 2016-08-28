# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

###Q1.  Cheat Sheet of Commands  

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

> > REPLACE THIS TEXT WITH YOUR RESPONSE
pwd = print working directory
man [command] = opens help manual for the command you specify
cd = change directory
	cd ~ = return to home directory
ls = list all files in current directory
mkdir [dirname] = make new directory
rmdir [dirname] = removes empty directory (safer than rm)
touch [filename] = creates new file in working directory
rm [filename] = removes specified file
open [filename] = opens file using default program
nano [filename] = opens file using nano text editor
clear = clears terminal screen
exit = does what it says on the tin

---

###Q2.  List Files in Unix   

What do the following commands do:  
`ls`  	= short listing of directory contents
`ls -a`  	= “all”; list including hidden files
`ls -l`  	= long listing
`ls -lh`  	= long listing that prints file sizes in human-readable format
`ls -lah`  	= long listing that includes hidden files and prints file sized in 				human-readable format
`ls -t`  	= sort by last modified, newest first
`ls -Glp`  	= long listing, does not print group names, appends '/' indicator to 				directories



---

###Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

-c	= displays files by timestamp
-u	= displays files by file access time
-d	= displays only the directories
-R	= displays subdirectories in addition to directories
-m	= displays names as a comma-separated list

---

###Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

Xargs “combines arguments” - it builds and executes command lines. Can be used to run more than one command at a time and/or to run a command on more than one file at once. This allows one to easily pipe the outputs of functions into other functions as input. For example, you could search a list of text files for a given string and then pass all the files that had that string into a program that turned the files into csv files (all within one command line).

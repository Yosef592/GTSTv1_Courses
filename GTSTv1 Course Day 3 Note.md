
# Linux Commands
## ● Linux Systems uses shell. The shell help us to Communicate with the kernel and helps to execute codes.
## ● Shell also called “Terminal”


---


# Cont…
## ● The terminal have 5 parts.
### ○ Username = rexder
### ○ Hostname = HunterMachine
### ○ Current Directory = PATH
### ○ Priviledge = $-(user) , #-(root)
### ○ Command place = _

## ● Home directory is ~
## ● Local directory with .
## ● All directory *


### Directory = folder


---


# Linux Command Basics
## ● On linux there are over 100 commands. But we will see the main and the useful only.
## ● Also those commands have their own options and arguments.


---


# What is command
## “Small programs that do one task well”


# ls / List Directory
## SYNOPSIS
## ls [OPTION]... [FILE]...
## DESCRIPTION
## List information about the FILEs (the current directory by default).


# cont…
## ● ls -l
## ● ls -a
## ● ls filename
## ● ls -R => recursive
## You can combine them, ls -Rla
## Linux hidden files start with dot.


# cd / Change Directory
## SYNOPSIS
## cd [directory]
## DESCRIPTION
## It is used to change current working directory.


# cont…
## ● cd / => root
## ● cd => home
## ● cd .. => 1x Back
## ● cd ../.. => 2x Back
## ● cd foldername
## If folder name have space you have to add the name inside “ folder name “
## cd “folder name”


# Pwd / print working directory
## SYNOPSIS
## pwd [-options]
## DESCRIPTION
## It prints the path of the working directory, starting from the root.
## Example after typing pwd:
## /home/omar/Desktop/OSLab



# echo
## SYNOPSIS
## echo [option] [string]
## DESCRIPTION
## echo command in linux is used to display line of text/string that are passed as an argument . This is a built in command that is mostly used in shell scripts and batch files to output status text to the screen or a file.


# cont…
## ● You can write texts into files.
### ○ echo text > file.txt
## ● You can add texts(append)
### ○ echo text >> file.txt


# cat / head / tail / less
## SYNOPSIS
## cat [FILE]...
## DESCRIPTION
## Used to show the content of a file


# touch
## SYNOPSIS
## touch [FILE1] [FILE2] [FILE3]
## DESCRIPTION
## Creates any kind of Files with the name you gave it. With empty inside.


# Mkdir / make directory
## SYNOPSIS
## mkdir {FOLDER-NAME1}, {FOLDER-NAME2},  {FOLDER-NAME3}
## DESCRIPTION
## Creates Folder with the name u gave it.
## - DON’T forget to add the “ “ when youare using folders with space between them.


# clear
## SYNOPSIS
## clear
## DESCRIPTION
## Clears your screen.


# rm / remove
## SYNOPSIS
## rm [FILE1] [FILE2] [FILE3]
## DESCRIPTION
## Remove file.


# cont…
## ● rm -r => recursive(4 folders)
## ● rm -i => for prompt(ask)
## ● rm -f => force delete
## You can use them in combination too like, rm -rf ‘filename’


# Cp| mv / copy,move
## SYNOPSIS
## cp {old FILE place and name}, {new file Place}
## Mv {old FILE place and file name}, {new file Place}
## DESCRIPTION
## Copy/move files & folders.


# > is to save a text in a file

## ex = echo "dhsvbdjhsvbdf" > GTSTv1.txt

## this code are save a text is GTSTv1.txt


# grep - global search for regular expression

## ● grep [options] pattern [files]
## ● The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out).


# cont…
## ● grep -i “search” file
## ○ - case insensitive
## ● grep -c “search” file
## ○ - count numbers
## ● grep -l “search” *
## ○ - displays filename
## ● grep -R “search” foldername
## ○ - search text in folders
## ● grep -v ‘term’ filename
## ○ To display without this term
## ● grep -n “term” file
## ○ To display the term find number


# Wc - word count
## SYNOPSIS
## wc [OPTION]... [FILE]...
## DESCRIPTION
## It is used to find out number of lines, word count, byte and characters count in the files specified in the file arguments.


## Line(-l) word(-w) byte(-c)


# Multiple Command Executions
## ● You can run/ execute multiple commands in 1 line.
## ● using 3 methods:
## ○ And ( && )
## ○ Or ( || )
## ○ Pipeing( | )


# AND ( && )
## On AND operation All commands you entered will be executed. If both are working without error

# OR ( || )
## On OR operation the command will be executed. If it have error or not


# Piping ( | )
## On pipe, will help you run commands by using the output of the 1st command as the input for the next one.


# EXERCISE 2
## 1) Create A text file with name paragraph.txt
## “ Hello my name is (Yourname), i got this course of linux and said hello, and am tring to learn linux. I love linux, so i said HELLO world “
## 2) How many times did the word hello written ?
## 3) how many byte is the size of this text
## 4) how many words are there?


# class is over
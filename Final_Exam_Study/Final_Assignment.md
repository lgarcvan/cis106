---
name: Vanessa Garcia
semester: Fall 23
course: cis106
---

# Question 1

## awk
* scripting language used for processing & displaying text.Performs operations line by line
* Formula = awk + options + {awk command} + file + file to save (optional)

*EX:
*EX:
*EX:
<br>

## cat
* create, merge or print files in the standard output screen or to another file
* Formula:
  * cat + option +Files to display
* EX: Display the content of the /etc/passwd file.
  *  cat /etc/passwd
* EX:Display the content of the /etc/passwd file with line numbers and the $ to indicate the end of every line.
* EX: cat -nE /etc/passwd
<br>
* EX:Replace the ; for a , in the cereal.csv file
    * cat cereal.csv | tr ';' ','
## cp
* Copies files and directories, including their content
* Formula:
  * cp + files to copy + destination
* create directory ws, in ws directory create directory called doc
  * mkdir ws/docs
* Download sample doc,xls & pdf from ws
  * cp Downloads/sample  
  * sample1 , sample1 , sample1 
* Copy files to docs directory inside ws.
  * cp Downloads/sample1.docs website/docs/
  * cp Downloads/sample1.pdf website/docs/    
  * cp Downloads/sample1.xls website/docs/
<br>

## cut
* extract a specific section of each line of a file
* Formula:
  *  cut + option + Files
* EX: 
* EX:
* EX:
<br>  

## grep
* lets you find a word by searching the content of a file. This Linux command prints all lines containing the matching strings
* Formula:
  * grep + option + search criteria + file
* EX: Display every line that starts exactly with the word “love” in the book Dracula
   * grep  '^love' dracula.txt
* EX: output only lines that have ip addr
* my own ip addr
 * ip addr 
  * ip addr | grep "inet" 
* EX: how many users can log into  my computer
  * grep -c "/bin/bash" /etc/passwd 
* EX: Display every line that starts with an upper case letter or a number in the book Dracula
  * grep -E '^[A-Z]|^[0-9]' dracula.txt
<br>

## head
* 

<br>
## ls
## man
## mkdir
## mv
## tac
## tail
## touch
## tr
## tree

# Question 2

* How to work with multiple terminals open?
<br>

* How to work with manual pages?
 * ls --help 
<br>

* How to parse (search) for specific words in the manual page
<br>

* How to redirect output (> and |)
  * cat source.txt > destination.txt 
<br>

* How to append the output of a command to a file
  *  cat source.txt >> destination.txt 
<br>

* How to use wildcards
    * For copying and moving multiple files at the same time
<br>

* How to use brace expansion
    * For creating entire directory structures in a single command
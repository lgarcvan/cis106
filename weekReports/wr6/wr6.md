---
name: Vanessa Garcia
semester: Fall 23
course: cis106
---

# Week Report 6

## Wildcards(3):  ?, *, [] 

### Wildcard *
  <br>

* The main wildcard is a star or asterisk (*). Star alone matches anything & nothing & matches any number of character.
  <br>

* Use (*) when:
* list all files w/ particular file extension
* Don't remember complete name of file but portion of name
* Want to copy, move or remove all file that match particular name
  <br>

  * The * wildcard matches from 0 to any number of characters. 
  <br>

    * EX: ls *.txt match all files that end in .txt regardless of size of file name
  <br>

    * EX: *.txt* .pdf list all files that end in .txt & .pdf
  <br>

    * EX: ls file.* list all files that start with string "file" regardless file extension. No file in directory matched. 
  <br>

    * EX: *file.* list all files that have any letter before string "file" & after as well.
  <br>

### Wildcard ? 
<br>

* The ? wildcard metacharacter matches precisely one character. Proves useful with hidden files(dot files)
<br>

  * EX: List all hidden files
    * ls ./.??* 
<br>

  * EX: List all hidden files in parent directory
    * ls ../.??*
<br>

  * EX: List all files that have two character b/n letter b & k
    * ls b??k* 
<br>

### Wildcard []
<br> 

* The [] wildcard match a single character range.Uses exclamation mark to reverse match.For example match everything except vowels [!aeiou] or any character except number [!0-9]
<br>

  * EX: Match all file whose name doesn't have a number in file name
    * ls *[0-9].*
<br>
 * EX: Match all files whose name begins w/ any these two sets of character letter from a-f or p-z
    * ls [a-fp][0-9][$USER]
  <br>

  * EX: Match all files whose name begins w/ any 3 combo of numbers & current username 
    * ls [0-9][0-9][0-9]$USER
  <br>

* Practice 5
![q1.P5](q1.P.5.png)<br>
  <br>

* Practice 6
![q1.P6](q1.P.6.png)<br>
  <br>

* Practice 7
![q1.P7](q1.P.7.png)
<br>

### Brace Expansion {}
  <br>

 How to use it (3) examples?
  <br>

* Brace expansion is not a wildcard but another feature of bash that allows to generate arbitrary string to use w/ commands. 
<br>

* EX: Create whole directory structure in single command:
  * mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}    
  * <br>

* EX: Create N number of files use:
  * touch website{1..5}.html
  * touch file{A..Z}.txt
  * touch file{001..10}.py
  * touch file{{a..z},{0..10}}.js
<br>

* EX: Remove multiple files in a single directory 
  * rm -r {dir1,dir2,dir3,file.txt,file.py}  

  
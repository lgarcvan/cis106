---
name: Vanessa Garcia
semester: Fall 23
course: cis106
---

# Week Report 5

## Answer following questions:

* What are Command Options?
  "Commands are often followed by" options that modify/enhance their behavior.
<br>
* What are Command Arguments?
  * "" Arguments which are the items the command acts on.This can be a file or directory.
<br>    
* Which command is used for creating directories? 
  mkdir = mkdir + name of directory
* Provide at least 3 examples.
    * EX: create directory in different directory use Relative Path = mkdir wallpaper/ocean
      * EX: Absolute Path: mkdir = ~/wallpapers/forest 
    * EX: create multiple directories 'mkdir movies -/Downloads/games -/Documents/hw'
* create directory w/ parent(home) directory at the same time 
  * EX: create directory: assets.image/small inside website directory
      *  mkdir -p ~/website/assets/images/small
<br>
* What does the touch command do?
  touch command = create files

  * Provide at least 3 examples.
    * EX:create file (index.html) inside directory website = touch index.html
    * EX:create file inside website/assets/images/small called logo.png = 
    * touch ~/website/assets/images/small/logo.png 
    * EX:create file with space in name + touch "list of food.txt"  
<br>
* How do you remove a file? 
  rm command
  * Provide an example.
    * EX:remove script.sj & image.png file =
       * rm scripts/script.js assets/image.png
    * EX:script & assets directory = rmdir scripts/ assets/  
<br>  
* How do you remove a directory and can you remove non-empty directories in Linux? 
* In linux you cannot remove non-empty directories :
  *EX: remove empty directory = rmdir
  *EX: remove non-empty directory = rm -r +directory name or direct absolute path
  *Provide an example
   * EX:remove non-empty = rm-r wallpapers
<br>
* Explain the mv and cp command.
* mv = move & rename directories
  * EX: move directory from one DL directory to website/assets directory = mv Downloads/picture website/assets/
* cp = copies files/directories from a source to destination
  * EX:cp + files to copy + destination
  * EX: cp Downloads/wallpapers.zip Pictures    
* To copy directories use -r
  * EX: cp -r   +directory to copy + destination
* Copy w/Abs Path= cp -r ~/Downloads/wallpapers ~Pictures/
  copy these files to docs directory inside website directory
   * EX: cp Downloads/sample1.doc website/docs/ 
  
##Complete all the Practices in the Presentation:

#Practice 1
![p1.1](wr5-p1.1.png)<br>
![p1.2](wr5-p1.2.png)<br>
![p1.3](wr5-p1.3.png)<br>
![p1.4](wr5-p1.4.png)<br>
![p1.5](wr5-p1.5.png)<br>
![p1.6](wr5-p1.6.png)<br>
![p1.7](wr5-p1.7.png)<br>
![p1,8](wr5-p1.8.png)<br>
![p1.9](wr5-p1.9.png)<br>
<br>

#Practice 2
![p2.1](wr5-p2.1.png)<br>
![p2.2](wr5-p2.2.png)<br>
![p2.3](wr5-p2.3.png)<br>
![p2.4](wr5-p2.4.png)<br>
![p2.5-6](wr5-p2.5-6.png)<br>
<br>

#Practice 3
![p3.1](wr5-p3.1.png)<br>
![p3.2](wr5-p3.2.png)<br>
![p3.3-4](wr5-p3.3-4.png)<br>
![p3.5](wr5-p3.5.png)<br>
![p3.6](wr5-p3.6.png)<br>
<br>

#Practice 4
![p4.1-2](wr5-p4.1-2.png)<br>
![p4.3-4](wr5-p4.3-4.png)<br>
![p4.5](wr5-p4.5.png)<br>
Yes I can see the images
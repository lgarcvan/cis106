---
name: Vanessa Garcia
semester: Fall 23
course: cis106
---

# Homework 8 

* What is VIM?
    * text editor built to enable efficient text editing,switching back and forth between edit and command 
*  What is nano?
   * command line editor, you can directly start typing to modify your file, such commands can be used directly operations like cut, copy, paste
<br>

* Describe in your own words how to:
  * Start and quit vim
    * Open a terminal window and type vim
      * press enter & vim window appears
    * to exit from the file without saving 
    * first exit from insert mode by pressing the Esc key
    * next type semicolon  ( : ) & then type the command q! 
    *  :q!   
    *  press enter 
<br>
  
* What are the different vim modes:
  * Vim has three modes:
    * Normal mode is also called Command mode 
      * used for performing actions like navigation, text substitution, cut, copy, paste, delete
    * Insert mode 
      * writing text to a file in the insert mode of Vim editor
    *  Visual mode 
       * it is used to select text with arrow keys so that various commands such as cut, copy, paste, delete, etc can be performed on selected text.
       * it allows to select from any point in any line. In the normal mode, you can delete words and lines but not a selection of text.
<br>
  
* Insert text in vim
    * to write some content, go into insert mode
    * go into write mode by typing command i
    * after going into insert mode you will see insert in the status bar allowing to enter data 
  <br>
  
* Save a file in vim
    * first exit from insert mode by pressing the Esc key
    * to save file:
    * first type semicolon ( : ) & then type the command w
    *  :w
    *  press enter 
<br>
  
* Search for a word inside vim
    * first type backslash key
    * hen write the word and press enter
    *   /school
<br>
  
* Delete text in vim
  * move the cursor to the character that has to deleted
  * press Esc key
  * then press the x key to delete text
    * or
  * To delete the word 
  * move the cursor to the beginning of the word
  * use dw command in normal mode,word under the cursor will be deleted
  * dw
  * press enter
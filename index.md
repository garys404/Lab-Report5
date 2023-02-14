# Lab Report 3
## Researching Commands
##### Today we will mainly focus on the `grep` command. 

* a) First of all, we need to set up our database. The database that we need to use is a github repository you can find here [database we need to use today]([https://code.visualstudio.com/](https://github.com/ucsd-cse15l-w23/skill-demo1-data))

* b) Next, if we want to enter "docsearch", so we need to `cd docsearch`.

* c) Because we want to use the command-line options on files and directories from `./written_2`, there is one really useful thing we can do with any command is use output redirection to put whatever would be printed into a file. Then we can process that file with other commands. The `>` character does output redirection in bash.

  Try: `find written_2/ > find-results.txt`

  `find-results.txt` has been created in the current directory, and that contains the data from `./written_2`. So we want to use the command-line options   from `find-results.txt`.

##### Now we can try the four interesting command-line options of the `grep` command !

### 1. `grep -n` command 

* The `-n` option displays the line number along with the matching line.

#### Example 1:
  The input of the command:
  
      garysong@Garys-MacBook-Pro docsearch-main % grep -n "Beijing" find-results.txt`
 
  The output of the command:
  
      212:written_2//travel_guides/berlitz2/Beijing-History.txt
      
      223:written_2//travel_guides/berlitz2/Beijing-WhereToGo.txt
      
      235:written_2//travel_guides/berlitz2/Beijing-WhatToDo.txt

#### Example 2:
  The input of the command:
  
      garysong@Garys-MacBook-Pro docsearch-main % grep -n "China" find-results.txt
  
  The output of the command:
  
      185:written_2//travel_guides/berlitz2/China-WhereToGo.txt
      
      200:written_2//travel_guides/berlitz2/China-History.txt
      
      227:written_2//travel_guides/berlitz2/China-WhatToDo.txt

### 2. `grep -w` command 

* The -w option only matches the whole word instead of a substring.

#### Example 1:
  The input of the command:
  
  The output of the command:

#### Example 2:
  The input of the command:
  
  The output of the command:
  



### 3. `grep -v` command

* The -v option inverts the match, so only the non-matching lines are displayed.

#### Example 1:
  The input of the command:
  
  The output of the command:

#### Example 2:
  The input of the command:
  
  The output of the command:


### 4. `grep -i` command 

* This option is used to perform case-insensitive search.

#### Example 1:
  The input of the command:
  
  The output of the command:

#### Example 2:
  The input of the command:
  
  The output of the command:

 
 
 
 
 
* Click the link: [How to Download Vscode](https://code.visualstudio.com/). The image of the link will be like that.

 ![Image](VScodeDownload.png)

* Follow the steps of that website, find the suitable version for your computer, and download the VS code.

* Open the VScode, and you should create "new file" or click "open" to open a file. It is like the following graph.

 ![Image](123.png)

* After you open a file, you should click the second button circled with red in the top right corner to open terminal.

 ![Image](12345.png)

* Next, you should click the "terminal", and put your commands at the red arrow.

 ![Image](1234567.png)

* Congraduation! You can put your commands in the right way.

 ![Image](VScode.png)



## 2. Remotely Connecting
1. Look up your course-specific account for CSE15L here: [Your Specific Account](https://sdacs.ucsd.edu/~icc/index.php).
2. You need to follow the instructions and reset the password. Here is a tutorial: [How to Reset Your Password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit).
3. You need to open the terminal in VScode and use `ssh` to connect remotely. Your command should be like `ssh cs15lwi23zz@ieng6.ucsd.edu` and `zz` should be replaced by the letters in your course-specific account.
4. After inputing your password, if your successfully log in, your terminal will be like the following page.



### That is all for the report 

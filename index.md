# Lab Report 3
## Researching Commands
##### Today we will mainly focus on the `grep` command. 

* a) First of all, we need to set up our database. The database that we need to use is a github repository you can find: : [Datbase you need to use](https://github.com/ucsd-cse15l-w23/skill-demo1-data).
* b) Next, we need to copy our database that type `git clone https://github.com/ucsd-cse15l-w23/skill-demo1-data` in your bash command line.

* c) After that, you need to `cd skill-demo1-data` and search the data from the tutorial of the dirtory of `written_2`.

##### Now we can try the four interesting command-line options of the `grep` command !

### 1. `grep -r` command 

* The -r (or --recursive) option allows grep to search through all files and subdirectories in a given directory. This can be useful when searching for a particular string in multiple files.

#### Example 1:
  The input of the command:
   ![Image](input1.png)
  
 
  The output of the command:
   ![Image](output1.png)
  


#### Example 2:
  The input of the command:
   ![Image](input2.png)
  
  
  
  The output of the command:
   ![Image](output2.png)
  


### 2. `grep -w` command 

* The -w option only matches the whole word instead of a substring.

#### Example 1:
  The input of the command:
   ![Image](input3.png)
  
  The output of the command:
   ![Image](output3.png)

#### Example 2:
  The input of the command:
   ![Image](input4.png)
  
  The output of the command:
   ![Image](output4.png)
  



### 3. `grep -n` command

* The `-n` option displays the line number along with the matching line.

#### Example 1:
  The input of the command:
   ![Image](input5.png)
  
  The output of the command:
   ![Image](output5.png)

#### Example 2:
  The input of the command:
   ![Image](input6.png)
  
  The output of the command:
   ![Image](output6.png)


### 4. `grep -i` command 

* This option is used to perform case-insensitive search.

#### Example 1:
  The input of the command:
   ![Image](input7.png)
  
  The output of the command:
   ![Image](output7.png)

#### Example 2:
  The input of the command:
   ![Image](input8.png)
  
  The output of the command:
   ![Image](output8.png)

 
 
 
 
 
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

# Lab Report 3
## Researching Commands
##### Today we will mainly focus on the `grep` command. 

* a) First of all, we need to set up our database. The database that we need to use is a github repository you can find : [Datbase you need to use](https://github.com/ucsd-cse15l-w23/skill-demo1-data).
* b) Next, we need to copy our database that type `git clone https://github.com/ucsd-cse15l-w23/skill-demo1-data` in your bash command line.

* c) After that, you need to `cd skill-demo1-data` and search the data from the tutorial of the dirtory of `written_2`.

##### Now we can try the four interesting command-line options of the `grep` command !



### 1. `grep -r` command 

* The -r (or --recursive) option allows grep to search through all files and subdirectories in a given directory. This can be useful when searching for a particular string in multiple files.



#### * Example 1:

  The input of the command:
   ![Image](input1)
  
  The output of the command:
   ![Image](output1)
 


#### * Example 2:
  The input of the command:
   ![Image](input2)
  
  
  
  The output of the command:
   ![Image](output2)
   
   
  * There is a very useful command that is `-r`, which allows grep to search through all files and subdirectories in a given directory. For example, if we just put `grep "Hongkong" written_2`, the output will always be `"grep: written_2/: Is a directory"`. However, when we put the input `grep -r "Hongkong" written_2`, the output is just like the example 1.
  
  * Now, let's look at the example 2. We put `grep -r "Lucayans" written_2`. The output should be like the image in the Example 2.
  


### 2. `grep -w` command 

* The -w option only matches the whole word instead of a substring.



#### * Example 1:
  The input of the command:
   ![Image](input3)
  
  The output of the command:
   ![Image](output3)


#### * Example 2:
  The input of the command:
   ![Image](input4)
  
  The output of the command:
   ![Image](output4)
   
   
   
  * There is a very useful command that is `-w`, which only matches the whole word instead of a substring. In this command, we use to continue use the command that is `-r`,which allows grep to search through all files and subdirectories in a given directory. 
  * So, when we put the input `grep -r -w "inter" written_2`, the output is just like the example 1. `-w` command is a very useful command because it only matches the whole world instead of a substring. If we do the normal search, the output will also include "intership","interaction", and some words like that.
  
  * Now, let's look at the example 2. We put `grep -r -w "relation" written_2`. The output should be like the image in the Example 2.
  


### 3. `grep -n` command

* The `-n` option displays the line number along with the matching line.


#### * Example 1:
  The input of the command:
   ![Image](input5)
  
  The output of the command:
   ![Image](output5)




#### * Example 2:
  The input of the command:
   ![Image](input6)
  
  The output of the command:
   ![Image](output6)


  * There is a very useful command that is `-n`, which  displays the line number along with the matching line. In this command, we use to continue use the command that is `-r`,which allows grep to search through all files and subdirectories in a given directory. 
  * So, when we put the input `grep -r -n "Lucayans" written_2`, the output is just like the example 1. The specific word appears in the line 6 and line 7 in the specific txt. `-n` command is a very useful command because it can contains the specific line, which displays the line number of the matching line, and help us track the line.
  
  * Now, let's look at the example 2. We put `grep -r -n "Hongkong" written_2`. The output should be like the image in the Example 2.




### 4. `grep -i` command 

* This option is used to perform case-insensitive search.



#### * Example 1:
  The input of the command:
   ![Image](input7)
  
  The output of the command:
   ![Image](output7)



#### * Example 2:
  The input of the command:
   ![Image](input8)
  
  The output of the command:
   ![Image](output8)


  * There is a very useful command that is `-i`, which is used to perform case-insensitive search. In this command, we use to continue use the command that is `-r`,which allows grep to search through all files and subdirectories in a given directory. 
  * So, when we put the input `grep -r -i "hongkong" written_2`, the output is just like the example 1. There is a very interesting thing when we search "hongkong", the result of "Hongkong" will also appear. `-i` command is a very useful command when we want to perform a search that is not case-sensitive.
  
  * Now, let's look at the example 2. We put `grep -r -i "lucayans" written_2`. The output should be like the image in the Example 2.

 
 
 
 
 


### That is all for the report 

# Lab Report 3
## Researching Commands
##### Today we will mainly focus on the `grep` command. 

* a) First of all, we need to set up our database. The database that we need to use is a github repository you can find: : [Datbase you need to use](https://github.com/ucsd-cse15l-w23/skill-demo1-data).
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
   
   
  There is a very useful command that is `-r`, which allows grep to search through all files and subdirectories in a given directory. For example, if we just put `grep "Hongkong" written_2`, the output will always be `"grep: written_2/: Is a directory"`. However, when we put the input `grep -r "Hongkong" written`, the output is just like the example 1.
  
  Now, let's look at the example 2. We put `grep -r "Lucayans" written_2`. The output should be like the image in the Example 2.
  






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

 
 
 
 
 


### That is all for the report 

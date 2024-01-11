# Lab Report 1: Remote Access and File System 

This week in lab we explored basic commands `cd`, `ls`, and `cat`. 

## cd command 
The `cd` command is used to change directories. When the `cd` command is run with no arguments it produces no output and no changes in the terminal, since it needs a specified directory to complete the command. This empty output looks like so (where [user@sahara ~] is the prompt in the terminal): 

```
[user@sahara ~]$ cd
[user@sahara ~]$ 
```
Here, the start working directory was /home/ and it didn't change after running the command `cd` because there was no specified directory to move into. This is not an error message, just no change has occurred. 


In order for the `cd` command to perform appropriately, a directory needs to be specified, like so: 

```
[user@sahara ~]$ cd lecture1/
[user@sahara ~/lecture1]$ 
```
Now we can see that the prompt of the terminal changed to include the /lecture1/ directory we specified. This is not an error message and we expected this output to happen. The changed prompt signifies that the working directory changed from /home/ to /home/lecture1/ and now we have access to the files stored in /lecture1/. 

But what would happen if we passed a path to a file as an argument for the `cd` command? 

```
[user@sahara ~/lecture1]$ cd Hello.java
bash: cd: Hello.java: Not a directory
```
As you can see, we got an error message after passing a file Hello.java as an argument. In the message it states that the argument passed into the `cd` command has to be a directory, which Hello.java is not. 


## ls command
The `ls` command allows us to see the list of files and folders contained in the current directory. For example, if we use the `ls` command while in /home/lecture1/ working directory, this is the output that we will get: 




## cat command


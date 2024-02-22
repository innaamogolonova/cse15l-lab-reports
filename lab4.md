# Lab Report 4: Vim

## Step 4: Log into ieng6

Keys Pressed: `<up><ENTER>`
The `ssh iamogolonova@ieng6.ucsd.edu` command was just the last command I used in my bash history so I just pressed `<up>` once in order to access it and `<ENTER>` to execute it. Since I have the SSH key set up on my `ieng6` account I didn't need to do anything else to log in. 

## Step 5: Clone your fork of the repository from your Github account (using the SSH URL)

Keys Pressed: `triple-click` and `Ctrl-C`
Once I was on the GitHub website and in my corerct repo I clicked on code and SSH and triple-clicked on teh SSH URL and then `Ctrl_C` to copy the SSH. Then with the SSH URL in my Clipboard I went to the terminal and executed the following command below. 

Keys Pressed: `git clone Ctrl-V <ENTER>`
I typed out the command `git clone` and pasted the SSH URL into the terminal and then pressed `<ENTER>` to execute the command. 
## Step 6: Run the tests, demonstrating that they fail

Keys Pressed: `cd l<TAB> <ENTER>`, `bash t<TAB> <ENTER>`
I had to `cd` into the lab7 directory to run the tests in the cloned repo. Pressing `cd l<TAB>` autocompleted to `cd lab7/`. Then after executing the `cd` command I typed `bash t<TAB>` which `bash test.sh` which ran the tests on ListExamples.java. The terminal showed that one of the tests failed. 

## Step 7: Edit the code file to fix the failing test

Keys Pressed: `vim L<TAB>.j<TAB> <ENTER>`, `x i 2 <ESC> :wq`
I used `vim` to open the file I needed to edit (since I knew exactly where and what the error was). Pressing `L<TAB>.j<TAB>` autocompleted to `ListExamples.java` and opened the appropriate file. After opening that file my cursor was already on the appropriate line (to change index1 to index2) so I deleted 1 by pressing `x`, inserted 2 by pressing `i 2`, returned to Normal Mode by pressing `<ESC>` and saved the file by pressing `:wq`. 

## Step 8: Run the tests, demonstrating that they now succeed

Keys Pressed: `<up><up><ENTER>`
I knew that the `bash test.sh` command was two up in the search history so I pressed the up key twice and then ENTER to run it. The command ran and showed that all tests passed successfully. 

## Step 9: Commit and push the resulting change to your Github account

Keys Pressed: `git add .`, `git commit -m "fix ListExamples.java`, 'git push`
I prefer to type of the git commit and push commands so I did that. I typed `git add .` to stage all the new changes I made on the repo. I then typed `git commit -m <message>` to commit the changes. And then I types `git push` to push all the new changes onto my GitHub account. 

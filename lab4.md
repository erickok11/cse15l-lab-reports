## Lab 4 Report
### Step 4(Log in to ieng6)
![Image](step4.png)
~~~
Key pressed: ssh<space>lkok@ieng6-201.ucsd.edu<enter> 
~~~
This command is used to log in to the ieng6 system.
Since the key is saved on my computer, so it did not prompt me to enter the password.

### Step 5(clone the repository)
![Image](step5.png)
~~~
Key pressed: git<space>clone<space><command-v> 
~~~
This command is used to clone the repository. Since I have copied the link
to the clip board. I pressed <ctrl-v> to paste the link after the command.

### Step 6 (Run the test)
![Image](step6.png)
~~~
Key pressed: cd<space>l<tab><enter> 
bash<space>te<tab><enter> 
~~~
This step is the set the current directory to the lab7 directory and run the test.sh shell script.
I pressed tab in this steps to let the terminal autofill the remaining command for me to reduce the 
time used to type the whole file name.
### Step 7 (Edit the code file)
![Image](step7.png)
~~~
Key pressed: vim<space>ListEx<tab><.>j<tab><enter> 
</>change<enter><down><right><right><right>i<backspace>2 
<esc><:>wq<enter> 
~~~
This step is to use the vim editor to open the file I wanted to edit. 
First I used </>change to find the word change in the file 
to locate the code I wanted to change in the file. Then I used arrow keys to move to the place I want to fix. 
Then I pressed i to change it to insert mode. I then pressed <backspace> to delete "2" and inserted 1 to fix the code. 
Finally,  I pressed <esc> button the back to normal mode and typed <:>wq to quit the editor with savings.
### Step 8 (Rerun the tests)
![Image](step8.png)
~~~
Key pressed: <up><up><enter> 
~~~
Since I haved already run the command that runs the tests script in the last two steps, therefore
I pressed up arrow key for two times to retrive that command and press enter to run it again.

### Step 9 (Commit and push)
![Image](step9.png)
~~~
Key pressed:
git<space>init<enter> 
git<space>add<space><.><enter>
git<space>commit<space><->m<space><">Fixed<space>the<space>bug<"><enter> 
git<space>push<enter> 
~~~
The init command is used to create a new git repository. After that I used the add command
to add a change to the git repository. Then I used the commit command to commit the changes
with the message "Fixed the bug". Finally I used the push command to upload the local repository
to the remote repository.



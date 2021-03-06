##Difficult Commands  
 
 **`cat`** has three functions:

+ to display the contents of a file `cat file_name`
+ to combine copies of a file without changing the original `cat file1 file2 file3`
+ to create a new file `cat > new_file` 
[^1] `cat >> new_file`
[^2]  

**`cp`** copies files & directories `cp source_file new_file` [^3]  

**`curl`** transfers data from or to a server `curl [option] [URL...]`

**`echo`** can repeat the input or give the value of a variable `echo [option] [string]` 

 **`echo "text" > file`** used to create and write in a file [^4]
 
 **`echo "text" >> file`** used to create and write in a file, if the file already exists the text will be added to the end of the file.

 **`mv source_file new_file`** can be used to move and rename files `mv oldname newname` [^5]

 **`git diff`** shows changes that occurred between commits
  
 **`git log`** lets you look back over the git and see what has happened. The options let you choose the configuration of the log.

 **`git rm`** used to remove a file from git control
 `git rm file' [^6]

[^1]:This will overwrite a file with the same name.
[^2]:This will add to the end of the file if it already exists.
[^3]: `-u` It will only copy if the new file doesn't exist or if there have been changes. 
[^4]: will overwrite if the file already exists.
[^5]: for renaming.
[^6]: `git rm --cached file` lets you keep the removed file on your hard drive.




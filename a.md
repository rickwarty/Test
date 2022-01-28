# Git and Github full 
- ## ` ls` command : to see the list of folder in the directory
  It is baically used to show the list of the file and folder 
```bash
   ls
```
- ## ` cd `  command : to go to the new directory
  - it is stand for change directory
  - it is use to switch between folder
```bash
     cd folder_name
```
- ## ` cd.. `  command : to go back to previous directory
  - it is use go back in previous folder 
```bash
     cd..
```
- ## ` git init `  command : to iniialize the folder into git
  - it is use to initialize the folder as git so the git can track the history 
  - first go to that folder and run the following command
```bash
     git init
```
- ## `ls -a `  command : show the hidden folder list
  - it is use to see the hidden file and folder
  - 
```bash
     ls -a
```

- ## `touch`  command: To creat a new file 
  - it is use to create a new file
  - touch file_name.extension ( extesnion can be any type like .py .txt .cpp .java .md etc)
```bash
     touch new_file.ext
```

- ## ` ls` command : To see all the file and folder
  It is baically used to show the list of the file and folder 
```bash
   ls
```
- ## ` cd folder_name`  command : To move to the another folder 
  - it is stand for change directory
  - it is use to switch between folder
```bash
     cd folder_name
```
- ## ` cd.. `  command
  - it is use go back in previous folder 
```bash
     cd..
```
- ## ` git init `  command
  - it is use to initialize the folder as git so the git can track the history 
  - first go to that folder and run the following command
```bash
     git init
```
- ## `ls -a `  command:
  - it is use to see the hidden file and folder
  - 
```bash
     ls -a
```

- ## ` git status`  command : To see the change in git repo
  -  It is basically use to see the all the cahnges that are made in the git repository
  - 
```bash
     git status
```

- ## `git add  filename`  command : To add the file in tracking area
  -  When we run this command is make the file into the tracking area where the git can track the history
  - Without running this command git can not track the history of the file that has neen modiefied
  - By this command we can stage only one file into tracking area
```bash
     git add filename.ext
```

- ## `git add .`  command : To stage all the file into tracking area
  -  This command add all the file into the staging area
```bash
     git add .
```
- ## `git restore --staged file_name.ext`  command : To stage the file from trackin area
  -  This command remove all the file from staging area into unstage 
  - file name can be like a.md, a.py, a.txt etc.
```bash
     git restore --unstage file name_
```

- ## `git commit -m "a.txt file added`  command : To commit all the changes
  -  It is use to commit or save all the chnages that has been made into file
  - `-m` means to provide a message while comminting the file 
```bash
     git commit -m "Message while commiting"
```

- ## `cat file.ext`  command : To see the content inside the file
  - It shows the content that has inside the file
```bash
     cat file_name.ext
```

- ## `git log`  command : It shows entire commited history
  - To see the history of the all the modification and commited 
```bash
     git log
```
- ## `rm -rf file_name.ext` 
  ### command : To remove file or folder 
  -  This command is to remove the file or folder from directory
```bash
     rm -rf file_name.ext
```
- ## `git reset hash_code` 
  ### command : To go back to any specific commit
  - It is use to reset the commit or go back to previous commit
  - Hash code : get it from the ``git log'``
```bash
     git reset hash_code
```

- ## `git stash` 
  ### command : Means saving it in directory without committing it 
  - By running this command it saves the file in directory without recording it in git repository
  - But whenever we need this file we can bring it back
```bash
     git stash
```
- ## `git stash pop` 
  ### command : To return all the file in the staging area who area saved without committing it
  - It bring back all the file into staging area the file that has been saved in the directory without committing the file 
```bash
     git stash pop
```

- ## `git stash clear` 
  ### command : To remove all the file that are back staged without committed  
```bash
     git stash clear
```

# Attach the local git directory to github repository

- ## `git remote add origin urls` 
  ### command : It is use to attach your local directory to github repository
  - urls: this url is generates when we create a new respository on github
  - example - https://github.com/rickwarty/Git-Basic.git

```bash
     git remote add origin urls
```
































- ## `` 
  ### command : 
  -  
  -  
```bash
     git 
```

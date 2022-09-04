##### 1. How to list all the branches?
A : to list all the branches, we use command called $git branch.

##### 2. How to check all the possible commands of Git?
A : To check all the possible commands of Git, we use command called $git help ...all

##### 3. How to check all the options of a command?
A : To check all the options of a command, we use command called $git command-help

##### 4. How to check the commit history?
A : To check the commit history , we use the command called $git log

##### 5. How to commit the changes?
A : $git commit   -m<commit message>

##### 6. How to discard changes of a specific file (test.html) in the working directory?
  A : $git restore <filename>

##### 7. How to stage the changes of a specific file (test.html)?
  A : For staging the file we use $git add <filename>
      for staging all the files we use $git add.

##### 8. What are the different ways to stage all the changes?
  A : $git add. or $git add -A  or  $git add  ---all

##### 9. How to check the status?
  A : $git status

##### 10. How check status in short format?

##### 11. How to initialize the git?
  A : $git init

##### 12. How to list all the configurations?
  A : $git config -l 

##### 13. How to configure email for a specific repo?
  A : $git config user.email <email>

##### 14. How to configure email at global?
  A : $git config--global user.email <email>

##### 15. How to configure user name at global?
  A : $git config --user.name <name>

##### 16. How to configure user name for a specific repo?
  A : $git config user. name <name>
  

##### 17. Explain how you will generate the SSH key?

##### 18. How to create a branch (my-first-branch)?
  A : $git branch <branch name>

##### 19. How to checkout to a branch (my-first-branch)?
  A : $git checkout <branch name>

##### 20. How to create a branch & checkout to that branch (my-second-branch)?
  A : $git checkout-b <branch name>

##### 21. How to delete a branch (my-third-branch)?
  A : $git branch -D <branch name>

##### 22. How to merge the branch (my-fourth-branch)?
  A : $git merge <branch name>

##### 23. How to pull the changes from 'main' branch?
  A : $git pull origin master

##### 24. How to clone a repo using https url?
  A : $git clone <http url>

##### 25. How to clone a repo using ssh url?
  A : $git clone <ssh url>

##### 26. How to clone a repo from a specific branch?
  A : $git clone -b <branch name> <http url or <ssh url>

##### 27. How to roll back to a specific commit?
  A : $git rest <commit id> or $git revert <commit id>

##### 28. How to change the commit message of the last commit?
  A : $git commit  --amend -m <commit message>

##### 29. How to list all the stashes?
  A : $git stash list

##### 30. How to stash the changes?
  A : $git stash

##### 31. How to apply the topmost stash and leave it in the stash list?
  A : $git stash apply

##### 32. How to apply the topmost stash and remove it from the stash list?
  A : $git stash pop

##### 33. How to apply a specific stash based on the stash number?
  A : $git stash apply stash@[number}

##### 34. How to drop a specific stash based on the stash number?
  A : $git stash drop stash@[number]

##### 35. How to clear the complete stash list?
  A : $git stash clear

##### 36. Why we use .gitignore file?
  A : It tells which files need to be ingnored when committed project to the github repository 

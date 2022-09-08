##### 1. How to list all the branches?
Ans : $ git branch 

##### 2. How to check all the possible commands of Git?
Ans : $ git help --all

##### 3. How to check all the options of a command?
Ans : $ git command -help

##### 4. How to check the commit history?
Ans : $ git log

##### 5. How to commit the changes?
Ans : $ git commit -m <commit message>

##### 6. How to discard changes of a specific file (test.html) in the working directory?
Ans : $ git restore <file name>

##### 7. How to stage the changes of a specific file (test.html)?
Ans : $ git add <test.html>

##### 8. What are the different ways to stage all the changes?
Ans : $ git add <file name> / git add . / git -A / git -all

##### 9. How to check the status?
Ans : $ git status

##### 10. How check status in short format?

##### 11. How to initialize the git?
Ans : $ git init

##### 12. How to list all the configurations?
Ans : $ git config -l

##### 13. How to configure email for a specific repo?
Ans : $ git config user.email "xxxxxxx"

##### 14. How to configure email at global?
Ans : $ git config --global user.email "xxxxxxx"

##### 15. How to configure user name at global?
Ans : $ git config --global user.name "xxxxxx"

##### 16. How to configure user name for a specific repo?
Ans : $ git config user.name "xxxxxx"

##### 17. Explain how you will generate the SSH key?
Ans : 1. Execute the following to begin the key creation
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
This command will create a new SSH key using the email as a label
2. You will then be prompted to "Enter a file in which to save the key." You can specify
a file location or press “Enter” to accept the default file location.
3. The next prompt will ask for a secure passphrase. You can enter a passphrase or
press “Enter” to skip the passphrase.
At this point, a new SSH key will have been generated at the previously specified file
path.
4. After you create the ssh key, add that key in your GitHub account
5. Test the SSH connection
$ ssh -T git@github.com

##### 18. How to create a branch (my-first-branch)?
Ans : $ git branch <my-first-branch>

##### 19. How to checkout to a branch (my-first-branch)?
Ans : git checkout <branch name>

##### 20. How to create a branch & checkout to that branch (my-second-branch)?
Ans : git checkout -b <my-second-branch>

##### 21. How to delete a branch (my-third-branch)?
Ans : git branch -D <my-third-branch>

##### 22. How to merge the branch (my-fourth-branch)?
Ans : git merge <my-fourth-branch>

##### 23. How to pull the changes from 'main' branch?

##### 24. How to clone a repo using https url?
Ans : git clone <http url or ssh url>

##### 25. How to clone a repo using ssh url?
Ans : $ git clone <http url or ssh url>

##### 26. How to clone a repo from a specific branch?
Ans : $ git clone -b <branch-name> <http url or ssh url>

##### 27. How to roll back to a specific commit?
Ans : $ git reset <commit id> / git reset <head number>
$ git revert <commit id> / git revert <head number>

##### 28. How to change the commit message of the last commit?
Ans : $ git commit --amend -m <commit message>

##### 29. How to list all the stashes?
Ans : $ git stash list

##### 30. How to stash the changes?
Ans : $ git stash

##### 31. How to apply the topmost stash and leave it in the stash list?
Ans : $ git stash pop / git stash apply / git stash apply n

##### 32. How to apply the topmost stash and remove it from the stash list?


##### 33. How to apply a specific stash based on the stash number?
Ans : $ git stash pop <stash no.>

##### 34. How to drop a specific stash based on the stash number?
$ git stash clear / git stash drop <stash id>

##### 35. How to clear the complete stash list?

##### 36. Why we use .gitignore file?

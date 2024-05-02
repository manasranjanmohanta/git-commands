1. To unstage the file from the staging area: ` git restore --staged <file-name>`
2. To clone from different branch: ` git clone -b <branch-name> <repository-url>`
3. To show all the commit changes or history : `git log` or `git log --pretty=format:"%h - %an, %ar : %s"`
4. To set your current branch to upstream : `git push --set-upstream origin <branch-name>`
5. To remove files from staging, but keep your changes: `git reset HEAD <file>`
6. To unstage the last three commits:`git reset HEAD^3`.
7. To unstage changes to a certain file from HEAD: `git reset <filename>`
   (To know more about HEAD click [here](https://github.com/manasranjanmohanta/git-commands/blob/main/Git-HEAD.md))
8. Delete a branch :
   - To delete a local branch : `git branch -d <branch-name>`
   - To delete a remote branch : `git push origin --delete <branch_name>`
   

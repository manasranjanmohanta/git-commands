1. To unstage the file from the staging area: ` git restore --staged <file-name>`
2. To remove files from staging, but keep your changes: `git reset HEAD <file>`
3. To unstage the last three commits:`git reset HEAD^3`.
4. To unstage changes to a certain file from HEAD: `git reset <filename>`
5. To clone from different branch: ` git clone -b <branch-name> <repository-url>`
6. To show all the commit changes or history : `git log` or `git log --pretty=format:"%h - %an, %ar : %s"`
7. To set your current branch to upstream : `git push --set-upstream origin <branch-name>`
   

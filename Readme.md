1. To unstage the file from the staging area: ` git restore --staged <file-name>`
2. To clone from different branch: ` git clone -b <branch-name> <repository-url>`
3. To show all the commit changes or history : `git log` or `git log --pretty=format:"%h - %an, %ar : %s"` or `git log --oneline`
4. To set your current branch to upstream : `git push --set-upstream origin <branch-name>`
5. To remove files from staging, but keep your changes: `git reset HEAD <file>`
6. To unstage the last three commits:`git reset HEAD^3`.
7. To unstage changes to a certain file from HEAD: `git reset <filename>`
   (To know more about HEAD click [here](https://github.com/manasranjanmohanta/git-commands/blob/main/Git-HEAD.md))
8. Delete a branch :
   - To delete a local branch : `git branch -d <branch-name>`
   - To delete a remote branch : `git push origin --delete <branch_name>`
9. To see the local branches : `git branch`
10. To see the remote branche s : `git branch -r`
11. To Switch branches : `git checkout <branch-name>` or `git switch <branch-name>` (To know more about [click](https://bluecast.tech/blog/git-switch-branch/) here)
12. How to revert back to a specific commit - read [Here](https://medium.com/swlh/using-git-how-to-go-back-to-a-previous-commit-8579ccc8180f)
   

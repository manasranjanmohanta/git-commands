# What is `git reset`?
The git reset command is a powerful tool that can be used to undo changes in your local repository. It can be used to unstage changes, undo commits, and even move the current branch to a different commit.

Here are some of the most common uses for the git reset command:

- Unstage changes:
    
    If you have made changes to files in your working directory but you don't want to commit them yet, you can use the git reset command to unstage them. This will remove the changes from the staging area, but it will not delete them from your working directory.
    
- Undo commits:
    
    If you have committed changes that you want to undo, you can use the git reset command to undo them. This will remove the commits from the commit history, but it will not delete the changes from your working directory.
    
- Move the current branch to a different commit:
    
    If you want to move the current branch to a different commit, you can use the git reset command to do so. This will update the HEAD pointer to point to the specified commit.
    

The git reset command has a number of options that can be used to control how it behaves. Here are some of the most common options:

- --soft: This option will unstage changes, but it will not undo commits.
- --mixed: This option will unstage changes and undo commits, but it will keep the changes in your working directory.
- --hard: This option will unstage changes, undo commits, and delete the changes from your working directory.

It is important to note that the git reset command can be dangerous if used incorrectly. If you are not careful, you can lose data. It is always a good idea to make a backup of your repository before using the git reset command.

Here are some examples of how to use the git reset command:

- Unstage changes: To unstage changes, you can use the following command:

Code

```
git reset HEAD
```

This will unstage all changes in the working directory.

- Undo commits: To undo commits, you can use the following command:

Code

```
git reset HEAD~1
```

This will undo the most recent commit. You can also use the --soft or --mixed options to control how the reset behaves.

- Move the current branch to a different commit: To move the current branch to a different commit, you can use the following command:

Code

```
git reset HEAD <commit-hash>
```

This will update the HEAD pointer to point to the specified commit.

The git reset command is a powerful tool that can be used to undo changes in your local repository. However, it is important to use it carefully to avoid losing data.

### Example to illustrate how git reset HEAD~1 works:

Let's say you have a Git repository with the following commit history:

```
A -- B -- C (HEAD)
```

- Commit A is the oldest commit.
- Commit B is the second commit.
- Commit C is the latest commit, and it's where your HEAD is currently pointing.
Now, if you run git reset HEAD~1, Git will move the HEAD pointer back one commit, effectively undoing the last commit (C). After running the reset command, your commit history will look like this:
```
A -- B (HEAD)
```

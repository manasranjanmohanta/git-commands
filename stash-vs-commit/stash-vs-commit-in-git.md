# Git Stash vs. Git Commit

Git stash and git commit are both commands used to save changes in Git. However, there are key differences between the two commands.

## Git Stash

- **Purpose:** Temporarily save uncommitted changes.
- **Location:** Local.
- **Effect on Working Directory:** Resets working directory to the last commit.
- **Publicly Visible:** No.

### Usage

To stash your changes:
```bash
git stash
```

To restore your changes:
```bash
git stash pop
```

## Git Commit

- **Purpose:** Permanently save changes to your local repository.
- **Location:** Local.
- **Effect on Working Directory:** Leaves working directory unchanged.
- **Publicly Visible:** Yes.

  
### Usage

To commit your changes:
```bash
git commit -m "Your commit message"
```

To push changes to a remote repository:
```bash
git push origin master
```

In general, use git stash to temporarily save changes and git commit to permanently save changes.

# What is HEAD in Git?
- HEAD in Git is a pointer to the current state of your repository. It's a symbolic reference that points to the current branch you're on, which in turn points to the latest commit in that branch. HEAD can be in one of two states: attached or detached.
- When HEAD is attached, it points to a branch. This is the normal state for HEAD, and it's what you'll be in most of the time. When you make a commit, HEAD moves to point to the new commit.
- When HEAD is detached, it doesn't point to a branch. Instead, it points to a specific commit. This can happen if you checkout a specific commit or tag, or if you use the `git reset` command to move HEAD to a specific point in the history.
- You can check the state of HEAD with the `git status` command. If HEAD is attached, it will show the name of the current branch. If HEAD is detached, it will show the SHA-1 hash of the commit that HEAD is pointing to.

Here are some examples of how to use HEAD:

- To checkout a specific branch, you can use the `git checkout` command. For example, to checkout the `master` branch, you would run `git checkout master`.
- To make a commit, you can use the `git commit` command. This will create a new commit and move HEAD to point to it.
- To reset HEAD to a specific point in the history, you can use the `git reset` command. For example, to reset HEAD to the previous commit, you would run `git reset HEAD~1`.

In summary-
- HEAD is a pointer to the currently checked out branch or commit. It answers the question **"Where am i right now in the repository?".**

HEAD is a powerful tool that can be used to control the state of your Git repository. By understanding how HEAD works, you can use it to checkout different branches, make commits, and reset your repository to a previous state.

#🚀 Git Commands Cheat Sheet for DevOps Engineers

Welcome to your go-to guide for Git! Whether you're setting up a new repository, collaborating with a team, or deploying code, these commands will keep your workflow smooth and efficient. Here's a breakdown of the most useful Git commands to help you succeed.

##🧑‍💻 Setting Up a Repository

1. Initialize a new Git repository

This command creates a .git directory, turning any folder into a Git-enabled repository.

```
git init
```

2. Clone an existing repository

Clones a repository from a remote location (like GitHub) to your local machine.

```
git clone <repository_url>
```

##📁 Working with Branches

3. Create a new branch

Creates a new branch for working on specific features or fixes.

```
git branch <branch_name>
```

4. Switch to a branch

Move to an existing branch to start working on it.

```
git checkout <branch_name>
```

5. Create and switch to a new branch (shorthand)

Create and switch to a new branch in one step.

```
git checkout -b <branch_name>
```

##📥 Staging & Committing Changes

6. Check the status of your files

Shows which files have changes or are staged for commit.

```
git status
```

7. Stage files for commit

Stages specific files for commit. To stage all files, use:

```
git add .
```

8. Commit your changes

Save your staged changes with a descriptive message.

```
git commit -m "Your message"
```

##🌍 Working with Remotes

9. Add a remote repository

Links your local repo to a remote one, often called origin.

```
git remote add origin <remote_url>
```

10. Push changes to a remote branch

Sends your changes to the remote repository.

```
git push origin <branch_name>
```

11. Pull changes from a remote repository

Fetches and integrates changes from a remote branch to your local branch.

```
git pull origin <branch_name>
```

##✂️ Advanced Git Commands

12. Merge two branches

Combines changes from one branch into another. Conflicts may arise, so be sure to resolve them!

```
git merge <branch_name>
```

13. Rebase branches

Rebases your current branch on top of another branch. This keeps your commit history cleaner.

```
git rebase <branch_name>
```

14. Stash your changes

Temporarily saves your uncommitted changes. Use git stash pop to retrieve them later.

```
git stash
```

##🗑️ Undoing Changes

15. Discard unstaged changes

Reverts changes in a file to the last committed state.

```
git checkout -- <file_name>
```

17. Reset staged files

Unstages a file without discarding changes.

```
git reset <file_name>
```

19. Reset to a previous commit

Reverts the entire repository to a specific commit, discarding changes made since.

```
git reset --hard <commit_hash>
```

##🧹 Cleaning Up

18. Remove untracked files

Removes untracked files from your working directory.

```
git clean -f
```

20. Delete a branch (locally)

Deletes a local branch that has already been merged.

```
git branch -d <branch_name>
```

##🔍 Git Logs and Tracking

20. View commit history

Shows the commit history with hash, message, and author.

```
git log
```

22. View changes between commits

Compares changes between two specific commits.

```
git diff <commit_hash> <commit_hash>
```

💡 Tips and Best Practices
Write clear and descriptive commit messages. Help yourself and your team by providing meaningful commit messages.
Commit often. Regular commits keep your work safe and trackable.
Use branches wisely. Isolate new features or bug fixes into separate branches.
Sync regularly with the remote. Use git pull frequently to ensure you’re up-to-date with team changes.
Check for conflicts. Always resolve conflicts in code during merges or rebases carefully.

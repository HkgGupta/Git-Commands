# Git Commands Most Used

## Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| **`git init`** | Initialize a local Git repository |
| **`git clone <repository>`** | Create a local copy of a remote repository |

## Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| **`git status`** | Check the status of the working directory |
| **`git add <file>`** | Add a file to the staging area |
| **`git add .` or `git add -A`** | Add all new and changed files to the staging area |
| **`git commit -m "message"`** | Commit changes with a message |
| **`git rm -r <file>`** | Remove a file or directory |

## Branching & Merging

| Command | Description |
| ------- | ----------- |
| **`git branch`** | List branches (the asterisk denotes the current branch) |
| **`git branch -a`** | List all branches (local and remote) |
| **`git branch <branch>`** | Create a new branch |
| **`git branch -d <branch>`** | Delete a branch |
| **`git push origin --delete <branch>`** | Delete a remote branch |
| **`git checkout -b <branch>`** | Create a new branch and switch to it |
| **`git branch -m <old-branch-name> <new-branch-name>`** | Rename a local branch |
| **`git checkout <branch>`** | Switch to a branch |
| **`git merge <branch>`** | Merge a branch into the current branch |
| **`git merge <source-branch> <target-branch>`** | Merge a branch into a target branch |

## Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| **`git push origin <branch>`** | Push a branch to your remote repository |
| **`git push -u origin <branch>`** | Push changes to the remote repository and set the upstream tracking |
| **`git push`** | Push changes to the remote repository (remembered branch) |
| **`git push origin --delete <branch>`** | Delete a remote branch |
| **`git pull`** | Update local repository with the latest changes from the remote |
| **`git pull origin <branch>`** | Pull changes from a remote repository branch |
| **`git remote add origin <repository>`** | Add a remote repository |

## Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| **`git log`** | View commit history |
| **`git log --summary`** | View detailed commit history |
| **`git log --oneline`** | View brief commit history |
| **`git diff <source-branch> <target-branch>`** | Preview changes before merging |

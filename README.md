# Git Commands Most Used

## Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| **`git init`** | Initialize a local Git repository |
| **`git clone <repository>`** | Create a local copy of a remote repository |

## Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| **`git status`** | Check status |
| **`git add <file>`** | Add a file to the staging area |
| **`git add .` or `git add -A`** | Add all new and changed files to the staging area |
| **`git commit -m "message"`** | Commit changes |
| **`git rm -r <file>`** | Remove a file (or folder) |

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
| **`git merge <branch>`** | Merge a branch into the active branch |
| **`git merge <source-branch> <target-branch>`** | Merge a branch into a target branch |

## Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| **`git push origin <branch>`** | Push a branch to your remote repository |
| **`git push -u origin <branch>`** | Push changes to remote repository (and remember the branch) |
| **`git push`** | Push changes to remote repository (remembered branch) |
| **`git push origin --delete <branch>`** | Delete a remote branch |
| **`git pull`** | Update local repository to the newest commit |
| **`git pull origin <branch>`** | Pull changes from remote repository |
| **`git remote add origin <repository>`** | Add a remote repository |

## Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| **`git log`** | View changes |
| **`git log --summary`** | View changes (detailed) |
| **`git log --oneline`** | View changes (briefly) |
| **`git diff <source-branch> <target-branch>`** | Preview changes before merging |

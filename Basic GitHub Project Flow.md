# Simple Git Workflow in a Project

## 1. Creating a New Repo

(i) Create a New Repository on GitHub  
(ii) Clone a repository

  ```bash
  git clone <repository>
  ```

or 

(i) Initialize a new Git repository:

```bash
git init
```
(ii) Add a Remote Repository

```bash
git remote add origin <repository>
```

## 2. New Branch

(i) Create and switch to a new branch:

  ```bash
  git checkout -b <branch-name>
  ```

or

(i) Switch to existing branch:

  ```bash
  git checkout <branch-name>
  ```

## 3. Make Changes and Stage Them

(i) Add specific files to the staging area:

  ```bash
  git add <file>
  ```

or 

(i) Add all changes:

  ```bash
  git add .
  ```

## 4. Commit Your Changes

(i) Commit the staged changes with a message:

  ```bash
  git commit -m "Your commit message"
  ```

## 5. Push Changes to the Remote Repository

(i) Push changes to the remote repository:

  ```bash
  git push
  ```

## 6. Compare and Create Pull Request

(i) Go to Your Repository on GitHub  
(ii) Navigate to the Pull Requests Tab  
(iii) Choose the Base and Compare Branches  
(iv) Review Your Changes  
(v) Add a Title and Description  
(vi) Create the Pull Request  

## 7. Review and Merge the Pull Request

Admin can Review and Merge the Pull Request

## 8. Pull Changes from Remote Repository (to stay up-to-date)

Fetch and merge changes from the remote repository:

  ```bash
  git pull origin <branch-name>
  ```

___

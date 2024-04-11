# Git Command Reference

This document provides a quick reference for common Git commands.

## Repository Setup

### Initialize a Repository
```bash
git init
```
Initializes a new Git repository in the current directory.

### Clone a Repository
```bash
git clone <repository_url>
```
Clones an existing repository from a remote server to your local machine.

## Basic Operations

### Check Repository Status
```bash
git status
```
Shows the current status of the repository, including tracked/untracked files and changes.

### Stage Changes
```bash
git add <file_name>
```
Stages changes in the specified file for the next commit.

### Commit Changes
```bash
git commit -m "Commit message"
```
Commits staged changes to the repository with a descriptive message.

### Push Changes
```bash
git push
```
Pushes committed changes from the local repository to the remote repository.

### Pull Changes
```bash
git pull
```
Fetches changes from the remote repository and merges them into the current branch.

### View Commit History
```bash
git log
```
Displays a chronological list of commits in the repository.

### Create a Branch
```bash
git branch <branch_name>
```
Creates a new branch with the specified name.

### Switch Branches
```bash
git checkout <branch_name>
```
Switches to the specified branch.

### Merge Branches
```bash
git merge <branch_name>
```
Merges changes from the specified branch into the current branch.

### Delete a Branch
```bash
git branch -d <branch_name>
```
Deletes the specified branch.

## Collaboration

### Add Remote Repository
```bash
git remote add origin <remote_url>
```
Adds a remote repository with the specified URL.

### Fetch Changes from Remote
```bash
git fetch
```
Fetches changes from the remote repository.

### View Remote Repository
```bash
git remote -v
```
Lists all remote repositories associated with the local repository.

### View Branches on Remote
```bash
git branch -r
```
Lists all branches on the remote repository.

### Pull Changes from Remote
```bash
git pull origin <branch_name>
```
Pulls changes from the specified branch on the remote repository.

### Push Changes to Remote
```bash
git push origin <branch_name>
```
Pushes committed changes to the specified branch on the remote repository.

### Collaborate with Others
```bash
git fetch
git merge origin/<branch_name>
git push
```
Fetches changes from the remote repository, merges them into the current branch, and pushes the changes back to the remote repository.

## Undoing Changes

### Discard Unstaged Changes
```bash
git checkout -- <file_name>
```
Discards unstaged changes in the specified file.

### Undo Staged Changes
```bash
git reset HEAD <file_name>
```
Unstages changes in the specified file, keeping the changes in the working directory.

### Undo Committed Changes
```bash
git revert <commit_hash>
```
Reverts the specified commit, creating a new commit with the reverted changes.

### Reset to a Previous Commit
```bash
git reset --hard <commit_hash>
```
Resets the repository to the specified commit, discarding all changes after that commit.

## Miscellaneous

### Ignore Files
Create a `.gitignore` file containing patterns of files to ignore.

### View Git Configuration
```bash
git config --list
```
Lists all Git configuration settings.

### Display Help
```bash
git help <command>
```
Displays help information for the specified Git command.
```

This README.md document provides a comprehensive reference for using Git commands in various scenarios. Each command is explained briefly along with its usage. You can expand upon this document as needed, including additional commands or more detailed explanations.

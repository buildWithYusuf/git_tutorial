Git Command History
1. Initialization
Create a new directory: Creates a directory for your project.
Command: mkdir git_tutorial
Navigate to the directory: Changes the current working directory.
Command: cd git_tutorial/
Initialize a Git repository: Initializes an empty Git repository in the directory.
Command: git init
2. File Operations
List files: Displays the contents of the current directory.
Command: ls
Check the current path: Prints the current working directory.
Command: pwd
Create a new file: Opens or creates a new file for editing.
Command: vi hello.txt
Create additional files: Creates multiple files.
Command: touch nibba.tx nibbi.txt
Remove a file: Deletes a file from the directory.
Command: rm hello.txt
3. Viewing Status
Check repository status: Displays the current status of your working directory, showing tracked and untracked files.
Command: git status
4. Staging and Committing Files
Stage a file for commit: Adds specific files to the staging area.

Command: git add nibbi.txt
Stage multiple files for commit: Adds multiple files to the staging area.

Command: git add nibba.txt nibba.tx
Commit staged changes: Records the staged changes in the repository with a commit message.

Command: git commit -m "adding nibba nibbi"
Stage and commit all changes: Stages all modified files and commits them.

Command: git add . followed by git commit -m "babusona"
5. Removing and Restoring Files
Remove a file: Deletes a file from the directory.
Command: rm nibbi.txt
Restore a file: Restores a deleted or modified file from the repository.
Command: git restore nibbi.txt
6. Configuration
Set global Git username: Configures your Git username globally for all repositories.
Command: git config --global user.name "buildWithYusuf"
Set global Git email: Configures your Git email globally for all repositories.
Command: git config --global user.email "devopsinterviews789@gmail.com"
7. Branching
Create a new branch: Creates a new branch and switches to it.
Command: git checkout -b dev
Check branches: Lists all branches in the repository and shows the current active branch.
Command: git branch
Switch to another branch: Switches to an existing branch.
Command: git checkout master
8. Viewing Commit History
View commit log: Displays the commit history.
Command: git log
View condensed commit log: Displays a one-line summary of the commit history.
Command: git log --oneline
9. Branching and Merging
Create and switch to a new branch: Creates a new branch and switches to it.
Command: git checkout -b dev2
Switch between branches: Changes the active branch.
Command: git checkout dev2
10. Additional Commands
Clear the terminal: Clears the terminal screen.
Command: clear
Summary
This document provides an overview of essential Git commands, including:

Repository initialization
File creation and management
Staging and committing changes
Branching and viewing commit history
Global configuration

*to check the remote origin in local
git remote -v
*To add the origin from github in local git 

git remote set-url origin ssh-url

This is the day one git journey
---Ends Here---

# Cheatsheet for Git Commands:
Let's discuss Git commands in short like viral youtube shorts!!

Git download for system : ```https://git-scm.com/downloads```

How to check it's version : ```git --version```

### Basic & Advanced Git Commands

#### Repository Management
```
git init        : initialize an empty Git repository
git clone <url> : cloning/copying an existing Git repository via URL
git remote add origin <remote_git_url> : add remote origin url
git remote remove origin : delete remote origin url
git remote -v : shows remote repository url's
```
#### Setup for user
Configuring user information accross local repositories
```
git config --global user.name "<user_name>" : set global username
git config --global user.email "<email_address>" : set global email
git config --global color.ui auto : set automatic command line coloring
```
#### Staging & Snapshot
Working with snapshots and the Git staging area
```
git status : shows the status of git repository, no untracked files
git add <file_name> : adding files(untracked) into files(staged) of current branch 
git add . : add all current directory files(untracked) of current branch
git commit -m "<message>" : commit all staged files of curent branch
```
#### Branching
```
git branch : shows all branches with * at active branch
git branch <branch_name> : creates a branch without switching to it
git checkout -b <branch_name> : creates a new branch and switch to that new branch
git switch <branch_name> : swithces to another branch from current branch
git checkout <branch_name> : switches to another branch form current branch
git branch -d <branch_name> : removes a branch from git
git branch -D <branch_name> : force or confirm the deletion of a branch from git
git merge <branch_name> : merges changes from another branch into the current branch
git rebase <branch_name> : 
````
#### Synchronizing with remote
```
git fetch : fetch all the remote branches
git push origin <branch_name> : push local changes to remote branch
git pull origin <branch_name> : pull remote changes to local branch
```
#### Logs
```
git log 	  : shows logs of current branch events with more info
git log --oneline : shows logs of branch events in one line
git reflog 	  : shows logs in simple way
```
#### Conflicts resolution
```
git log --merge 	: produce the list of commits which causing the conflict
git diff 		: identifies difference between the states repository or files
git checkout 		: undo the changes made to the file
git reset --mixed 	: undo changes to the working directory and staging area
git reset 		: undo local changes to the state of a Git repo. 
git reset --hard 	: resets the current branch tip, and also deletes any changes in the working directory and staging area 
git merge --abort 	: exit from merging process and return to the step before merging starts
git revert <commit hash>: rolls back to previous commit on current branch
git restore <file_name> : brings back deleted files(committed)
```
#### Stash
```
git stash : takes uncommitted changes (both staged and unstaged), saves it for later, and then reverts them from working copy.
git stash list : shows list of stashed items
git stash apply : saves the uncommitted changes locally, allowing you to make changes, switch branches, and perform other Git operations
git stash clear : clear the stashed items
git stash pop : popping an item from stash
git stash drop : delete most recent stash
```
#### Cherrypick & squash
```
git cherry-pick : picking one commit from one branch to another & also useful for undoing changes
git squash : combines multiple commits into one
```

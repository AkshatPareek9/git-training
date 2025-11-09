# git-training
Let's Start Learning Git

# Git commands:
```
mkdir git-train
```
```
cd git-train
```
# Initialize a git on local
```
git init
```
```
touch demo.txt
```
# check the git status
```
git status
```
# list the git branches
```
git branch
```
# switch to another branch
git checkout dev

# create new branch and switch to it
git checkout -b dev

# Add the file to git repo
git add demo.txt

# commit the changes with the message
git commit -m "Added demo.txt"

# Remove and restore the file
rm demo.txt

git restore demo.txt

# Restore the staged  file
touch a.txt b.txt c.txt

# to add all the files with single command
git add .

git restore --staged b.txt

# to check the git logs
git log

# to revert the wrong commit
git revert <commit-id>

# Remove the file from git repo
rm a.txt

git rm a.txt

git status

# Clone the git repo
git clone https://github.com/AkshatPareek9/git-training.git

# Push the code to git
git push origin main

# List the git
git remote -v

Git vs GitHub vs GitLab vs Bitbucket

Git = Version control system (VCS) - gives command line interface (CLI)
GitHub = Store the code on the repo which is publically available. | Best for Copilot and GithubActions - gives Graphical user interface (GUI)
GitLab = Same as Github with more functionality. Best for CICD and AI
Bitbucket = Best for integrate with Jira and CICD.

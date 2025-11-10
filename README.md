# git-training
Let's Start Learning Git

# Git vs GitHub vs GitLab vs Bitbucket

Git = Version control system (VCS) - gives command line interface (CLI)</br>
GitHub = Store the code on the repo which is publically available. | Best for Copilot and GithubActions - gives Graphical user interface (GUI)</br>
GitLab = Same as Github with more functionality. Best for CICD and AI</br>
Bitbucket = Best for integrate with Jira and CICD.</br>

# Difference between File system v/s VCS
File System = File can't recover once deleted.</br>
VCS = File can be recover if deleted or also rollback policy.</br>

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
</br> or </br>
git switch dev

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
</br>
git log --oneline

# to revert the wrong commit
git revert <commit-id>

# Remove the file from git repo
rm a.txt

git rm a.txt

git status

# Clone the git repo
git clone https://github.com/AkshatPareek9/git-training.git

# Push the code from local to git
git push origin main

# List the git
git remote -v

# Pull the code from git to local
git pull origin main

# Add remote git in local 
git remote add origin https://github.com/AkshatPareek9/git-training.git

git remote set-url origin https://<Personal Access token>@github.com/AkshatPareek9/git-training.git

# Difference between clone and fork
clone = from github to local = We are cloning github repo to local.
fork = from github to github = We are cloning the other's github repo into our's github repo.

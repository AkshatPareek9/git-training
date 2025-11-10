# git-training

**Let's Start Learning Git**

------------------------------------------------------------------------

## Git vs GitHub vs GitLab vs Bitbucket

-   **Git** = Version Control System (VCS) --- provides Command Line
    Interface (CLI)\
-   **GitHub** = Stores code in public repositories \| Best for Copilot
    & GitHub Actions --- provides Graphical User Interface (GUI)\
-   **GitLab** = Similar to GitHub but with more functionality \| Best
    for CI/CD and AI\
-   **Bitbucket** = Best for Jira integration & CI/CD

------------------------------------------------------------------------

## Difference Between File System vs VCS

-   **File System** = Files cannot be recovered once deleted.\
-   **VCS** = Files can be recovered if deleted; rollback supported.

------------------------------------------------------------------------

## Git Commands

    mkdir git-train

    cd git-train

### Initialize Git in Local

    git init

    touch demo.txt

### Check Git Status

    git status

### List Git Branches

    git branch

### Switch to Another Branch

    git checkout dev

**or**

    git switch dev

### Create New Branch and Switch to It

    git checkout -b dev

### Add File to Git Repo

    git add demo.txt

### Commit Changes With Message

    git commit -m "Added demo.txt"

### Remove and Restore File

    rm demo.txt
    git restore demo.txt

### Restore Staged File

    touch a.txt b.txt c.txt
    git add .
    git restore --staged b.txt

### Check Git Logs

    git log
    git log --oneline

### Revert a Wrong Commit

    git revert <commit-id>

### Remove File From Git Repo

    rm a.txt
    git rm a.txt
    git status

### Clone Git Repo

    git clone https://github.com/AkshatPareek9/git-training.git

### Push Code From Local to Git

    git push origin main

### List Git Remotes

    git remote -v

### Pull Code From Git to Local

    git pull origin main

### Add Remote Git in Local

    git remote add origin https://github.com/AkshatPareek9/git-training.git

    git remote set-url origin https://<Personal Access token>@github.com/AkshatPareek9/git-training.git

------------------------------------------------------------------------

## Difference Between Clone and Fork

-   **Clone** = From GitHub to Local --- cloning repository to your
    system.\
-   **Fork** = From GitHub to GitHub --- cloning someone else's repo
    into your own GitHub account.

------------------------------------------------------------------------

## Git Hooks
-  Check the code error or mistake before commit

   cd .git/hooks/
   vim pre-commit



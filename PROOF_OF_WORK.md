# Proof of Work

## Git Log
```
30c3ad2 Merge pull request #1 from MuhammadAmmanullah/development
ece41fd fix: resolved merge conflict
3723427 fix: staging label
b3ba625 feat: updated script with staging env
b8c77bf feat: initial commit with deploy script
6708014 Add DevOps section to README
```

## Reflection Questions

### Q1: Difference between Git and GitHub
Git is a version control tool that you install on your own machine to record the history of your project's files. It runs fully offline, so you can commit, branch and merge without needing the internet. GitHub is an online service that stores Git repositories in the cloud so many people can work on the same project.

### Q2: Working Directory, Staging Area and Local Repository
The Working Directory is the project folder where you create, edit and delete files directly. The Staging Area is a holding space where you collect the specific changes you want to include in your next commit, which you do with git add. The Local Repository is the folder that keeps the permanent history, and a change reaches it once you run git commit.

### Q3: Difference between git stash pop and git stash apply
git stash pop restores the most recently stashed changes to your working directory and deletes that stash from your stash list. git stash apply restores the stashed changes to your working directory but keeps a copy in the stash list for future use.

### Q4: Difference between git fetch and git pull
git fetch downloads the latest updates and references from the remote repository without altering or merging them into your local files. git pull downloads those remote updates and automatically merges them into your current active local branch.

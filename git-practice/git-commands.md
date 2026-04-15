## Basic Git commands:
These are commands to initialize, check status, stage, unstage and commit files
```
git init
git status
git add <file>
git add .
git rm --cached <file>
git commit -m "message"
```

# Restore:
Restores a file to the latest commit stage
```
git restore <file>
git restore . # to restore all files
```

# Github:
To check remote:
```
git remote -v
```

To check add new remote
```
git remote add <remote name> <URL> # eg for remote is: `origin`
```

To clone an already existing repo:
```
git clone <URL>
```

To clone a specific branch from the repo:
```
# to clone main alongside the branch
git clone -b <branch-name> <URL>

# to only clone that specific branch
git clone -b <branch-name> --single-branch <URL>
```

To update:
```
git push <remote> <branch>
git pull <remote> <branch>
```

To add a upstream branch for pull/pull
```
git push -u <remote> <branch>

# now, can use without adding branch/remote names
git push
git pull
```

# Git Branching:

To create a new branch:
```
git branch -c <branch>

git switch -c <branch>

git checkout -b <branch> 
```

To switch a branch:
```
git switch <branch>

git checkout <branch>
```

To push a particular branch to remote:
```
git push <remote> <branch>
```
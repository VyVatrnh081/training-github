# Retrieving updates from another repository and updating local repos
### 1. add a git URL as an alias
_git remote add [alias] [url]_
### 2. fetch down all the branches from that Git remote
_git fetch [alias]_
### 3. merge a remote branch into your current branch to bring it up to date
_git merge [alias]/[branch]_
### 4. transmit local branch commits to the remote repository branch
_git push [alias] [branch]_
### 5. fetch and merge any commits from the tracking remote branch
_git pull_

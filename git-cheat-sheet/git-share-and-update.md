# Retrieving updates from another repository and updating local repos
### 1. add a git URL as an alias
git remote add [alias] [url]
### 2. fetch down all the branches from that Git remote
 git fetch [alias]
### 3. merge a remote branch into your current branch to bring it up to date
 git merge [alias]/[branch]
### 4. transmit local branch commits to the remote repository branch
 git push [alias] [branch]
### 5. fetch and merge any commits from the tracking remote branch
 git pull

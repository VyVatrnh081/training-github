# Working with snapshots and the Git staging area
### 1. show modified files in working directory, staged for your next commit
_git status_
### 2. add a file as it looks now to your next commit (stage)
_git add [file]_
### 3. unstage a file while retaining the changes in working directory
_git reset [file]_
### 4. diff of what is changed but not staged
_git diff_
### 5. diff of what is staged but not yet committed
_git diff --staged_
### 6. commit your staged content as a new commit snapshot
_git commit -m “[descriptive message]”_

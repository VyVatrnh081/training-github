# Examining logs, diffs and object information
### 1. show the commit history for the currently active branch
_git log_
### 2. show the commits on branchA that are not on branchB
_git log branchB..branchA_
### 3. show the commits that changed file, even across renames
git log --follow [file]
### 4. show the diff of what is in branchA that is not in branchB
git diff branchB...branchA
### 5. show any object in Git in human-readable format
git show [SHA]

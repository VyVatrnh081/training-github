# Versioning file removes and path changes
### 1.  delete the file from project and stage the removal for commit
_git rm [file]_
### 2.  change an existing file path and stage the move
_git mv [existing-path] [new-path]_
### 3.  show all commit logs with indication of any paths that moved
_git log --stat -M_

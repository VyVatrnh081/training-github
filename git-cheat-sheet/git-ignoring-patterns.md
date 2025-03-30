# Preventing unintentional staging or commiting of files
### 1.  Save a file with desired patterns as .gitignore with either direct string matches or wildcard globs
-  _logs/
-  *.notes
-  pattern*/_
### 2.  system wide ignore pattern for all local repositorie
_git config --global core.excludesfile [file]_

# OpenSourceSW_Lecture_Note_6

### Two ways of Version Control

- changes vs snapshots
  - changes saves only the changed part of the file for each version
  - Snapshots save the changed parts of the file and the contents of the original file as a single file for each version. → Git uses this method.

### Three states in Git

- Modified
- Staged
- comitted

---

### Git config

: The initial setup you need to do only once when installing Git per computer!

### Git configurations are stored in three levels:

**(1)System level** : --system option. Affects all uses and repositories on the system.

**(2)Global level** : -global option. Affects all repositories of a current user.

**(3)Local level** : --local option. Specific to the current repository.

---

### Git command

```c
- git init // You only need to do it once for each folder you want to version control.

- git add [file_name] // A collection of files to be committed.

- git status // Checks which files are grouped to commit.

- git add . // Collects all files in a folder. Except for files in gitignore.

- git rm -cached [file_name] // It excludes the files collected by add again.

- git commit -m “commit message” // Committing a version for push to github.

- git log // Shows committed versions.

- git branch // Check the local branch.
```

> # Revisions and the Cloud

## Version control systems
- a version control system allows people to manage different versions of a file or files -- communicate about versions, revert to previous versions, compare versions, and more easily fix mistakes.
- a *distributed version control system* (DVCS) allows for redundancy because there is no single point of failure

## Git commands
- `git clone URL` = clones a Git repository from the specified URL
- `git clone URL DIRECTORY` = clones a Git repository to a specific directory (rather than creating a directory that takes on the repository's name)
---
- `git status` = checks state of files
- `git add FILENAME` = tracks and stages the specified file
- `git add *` = tracks and stages all files in the current repository
- `git commit -m "MESSAGE"` = commits all staged files and associates the commit with the specified message
- `git push LOCAL-BRANCH REMOTE-REPOSITORY` = pushes changes from the specified local branch to the specified remote repository
---
- `git stash` = temporarily removes and hides changes
- `git stash apply` = retrieves the hidden changes
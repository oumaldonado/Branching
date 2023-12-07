# Git Branching Cheat Sheet

## Basic Commands 
* 'git init' - initialize local git repo
* 'git add . ' - adds files to be committed 
* 'git commit -m' - adds message about changes
- git status
show modified files in working directory, staged for your next commit

- git add [file]
add a file as it looks now to your next commit (stage)

- git reset [file]
unstage a file while retaining the changes in working directory

- git diff
diff of what is changed but not staged

- git diff --staged
diff of what is staged but not yet commited

- git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot
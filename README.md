# Git Branching Cheat Sheet

 ## Overview 

 Summart of common git commands

 stuff added by me 
 more main stuff
 blah 
1. checkout and pull main 
```bash

git checkout main
git pull origin main 
```
 1. checkout new branch from up-to-date main
```

git checkout -b someFeature

```

1. work committing each complete task, until feature is complete

1. ```
git add 
git commit -,"complete feature"
git pull origin main 


```
* if auto merge merge succeeds, save and quit from 'vi' editor:
* if 'CONFLICT', fix conflicts in all files removing merge markers and commit 
``` bash

git add 
git commit -m "fixed merge conflict"
```

## Basic Commands 
* 'git init' - initialize local git repo

* 'git add . ' - adds files to be committed 

* 'git commit -m' - adds message about changes

* 'git log --oneline' - list of commit history, compact foramt 

* 'git status ' - show state of local working repo'

* 'git config -l' - list local git configuration

* 'git reset' [file]
unstage a file while retaining the changes in working directory

* 'git diff'
diff of what is changed but not staged

* 'git diff --staged'
diff of what is staged but not yet commited

* 'git branch' - list local branches
* 'git help' - show synopsis of git commands

## Remote Commands

* 'git remote add origin URL ' - set 'origin ' as alias for remote




dlsdfasdfasdfasdfas
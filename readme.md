- git clean -f index.html //Remove new file that was addition like untracked
- git reset HEAD //After git add . commit case would like reset modified committed file just use command
- git update-index --assume-unchanged xxxx.extension file Changes not staged for commit modified ignore from git
- You can get the files back with git update-index --no-assume-unchanged 
## get fetch changes from external repository to local repo

- git fetch
- git merge origin/master
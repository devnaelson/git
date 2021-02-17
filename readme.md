- git clean -f index.html; //Remove new file that was addition like untracked
- git reset HEAD; After git add . commit case would like reset modified committed file just use command
- git update-index --assume-unchanged xxxx.extension; file Changes not staged for commit modified ignore from git
- git update-index --no-assume-unchanged xxx; You can get the files back with

## Get fetch changes from external repository to local repo.
- git pull; most used, contains fetch and merge under one
- git fetch
- git merge origin/master


## Possible errors

```nginx

error: Your local changes to the following files would be overwritten by merge:{
    solution commands [
        git checkout HEAD^  xxxx,
        git pull 

    ]
}

```

```nginx
git checkout --orphan <name_you_choose_for_orphan_branch> //create branch without copy of another branch
get reset        
git add fileName // specific files
git commit
Then you can run your
git push <remote-name> <branch-name>

Apply merge with master
git checkout master
git merge dev
git push
```

```nginx
git branch -D branch //local
git push origin --delete branch //repository
```

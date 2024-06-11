## GIT

## GET STARTED
```git
git --version

git init

git config user.name "test"

```
## NEW FILES
````git
git status

git add index.html

git add -A 
````

## COMMIT
````git
git commit -m "first commit"

git status --short
````
## HELP

```git
git status -help

git help --all
```

## BRANCH

```git
git branch new-branch

git branch

git checkout nem-branch

git checkout -b other-branch
```

## BRANCH MERGE
````git
git merge other-branch

git branch -d other-branch
````

## REMOTE 
````git
git remote add origin https://github.com/x/y.git

git fetch origin

git merge origin/master

git pull origin

git push origin

git branch -a

git branch -r
````

## CLONE

````git
git clone https://abc.com/x/y.git

git clone https://abc.com/x/y.git newlife

git remote rename origin upstream
````

## .GITIGNORE

```git
*.temp

temp/

temp?.log

*.log
!main.log
```

## REMOTE ADD SSH
```git
git remote add ssh-origin git@abc.com:x/y.git

git remote set-url origin git@abc.com:x/y.git
```

## REVERT
```git
git log --oneline

git revert HEAD

git revert HEAD --no-edit

git revert HEAD~1
```

## RESET
```git
git reset abc1234
```
## AMEND
```git
gir commit --amend -m "Updated index"
```


``` bash
git --version

# Configure Git
git config --global user.name "Your Name"
git config --global user.email "you@email.com"
git config --global --list

# initialize git 
git init

# check status 
git status

git add file.txt
git add .

git commit -m "Initial commit"

# git commit -m "Initial commit"
git log
git log --oneline

# Check File Differences
git diff
git diff --staged

# Remove files
git rm file.txt
# renae files
git mv old.txt new.txt

# Branching 
git branch feature-login
git checkout 



git checkout -b feature-login


git branch

# Merging 
git checkout main
git merge feature-login

# delete brsanch 
git checkout main
git merge feature-login

# reset files
git reset file.txt

# amend last commit 
git commit --amend

# hard reset 
git reset --hard <commit_id>

# xonnect local repo to github 
git remote add origin https://github.com/user/repo.git
git branch -M main
git push -u origin main

# clone 
git clone https://github.com/user/repo.git

# pull latest change 
git pull origin main

# fecth pull 
git fetch
git merge


# pull request flow
git checkout -b feature-api

git add .
git commit -m "Add API feature"
git push origin feature-api

# gi stash 
git stash

# restore stash 
git stash pop

# list starch 
git stash list

# creaet tag 
git tag v1.0
git push origin v1.0

# tag annotation 
git tag -a v1.1 -m "Release v1.1"

# rebase 
git rebase main

git rebase -i HEAD~3

# cherry pick 
git cherry-pick <commit_id>

# sqaurese 
git rebase -i HEAD~5


# must used flows 
git init
git status
git add .
git commit -m ""
git log --oneline
git branch
git checkout -b
git merge
git pull
git push
git stash
git rebase

```


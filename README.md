# GitDemo
It is a demo Repository.
# Other Commands :
mkdir fileName // used to create new directory
ls -la // used to inner file in macOs or linux
ls -Force  or Get-ChildItem -Force //  used to inner file in windows

Commands are :-
git --version
Configuring GIT :
git config --global user.name "Udayan Mal"
git config --global user.email "abc@gmail.com"
git config --list

git status

# Basic Commands :
git clone <- some link->
git status
git add file_name  // eg : git add index.html
git add . // use to add all files
git commit -m "some message" // eg : git commit -m "Add new files"
git push origin main
git init // create new repo

git remote add orgin <-link-> // to add new repo from local system
git remote -v // to verify remote
git branch  // to check branch
git branch -M main // to rename branch
git push origin main
git push -u origin main // after used don't to need write 'origin main'
git commit -am "added dot"  // add & commit

git pull origin main // used to fetch and download content from a remote repo and immediately update the local repo to match that content.

# Branch Commands :
git branch // to check branch
git branch -M main  // to rename branch
git checkout <- branch name ->  // to navigate
git checkout -b <- to create new branch ->
git branch -d <- to delete branch ->
git push --set-upstream origin <- branch name ->

git log // to check all changes  - > enter q to quit

# Merging Commands :
git diff <- branch name -> // to compare commits, branches, files & more
git merge <- branch name -> // to merge 2 branches
        OR
Create a PR (Pull Request)

# Fixing Mistakes

Case 1: staged changes

git reset <- file name ->
git reset

Case 2: commited changes (for one commit)

git reset HEAD~1

Case 3: commited changes (for many commits)

git reset <- commit hash ->
git reset --hard <- commit hash ->

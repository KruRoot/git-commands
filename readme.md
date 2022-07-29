# How to work with Git


![git_logo](logo.png)


git add . or git add %file_name% - adding after saving file before commit

git commit -m '%commit_name%' or git commit -am '%commit_name%' for add+commit - for commits

git commit --amend -m ‘%commit_name%’ - to change a last commit if didn't send to remote repo yet

git log or git log -p or git log —graph or git log --oneline  - for logs

git log HEAD^^ or git log HEAD~%number% - show log from &number& commit from HEAD

git checkout %commit_number% - for looking prev commit

git checkout master - move to main branch

git checkout -b %btanch_name% - create a branch and move there

git branch - list of branches

git branch %branch_name% - add branch

git branch -d %branch_name% - delete branch

git merge %another_branch% - to merge branches, from %another_branch% to current branch, git merge --abort - abort

git diff - different with last commit

git diff %commit_number% - different with &commit_number&

git diff --staged - different between git add

git clone address - clone repo

git remote add origin address - set a remote address as origin

git branch -M master - set a main branch as master

git push -u origin master - push to origin address

git push - push local repo to remote repo if already set


file .gitignore - inside this file write all untracked files, after that add .gitignore to git and commit
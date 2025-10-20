Track with yuour name
git config --global user.name 'Adorts-Adurah'
git config --global user.email 'mail.durallite@gmail.com'

Git Repository
git init

Check the project files status
git status

You have to add firl to stage before commit it
git add readme.md

commit is like snapshot to remember the copy of it when and what time

git commit -m 'Add readme.md file'

for all file 

git add ./

Ti check all our process
git log


how to restore the files
git checkout <commit id>

you need to swich to main 
git checkout main
git checkout -f main

change branch name to main

git branch -M main



to work with git remote repository

git remote add origin https://github.com/adorts-adurah/mastering_git.git

to put use
git push -u origin main


to create a new branch 

git branch <branch-name>

to swicth to new branch 

git checkout <branch-name>

to go back to main
git checkout main

shortcut

create and swicth to branch
git checkout -b feature-brnach

create branch and move to the t==branch and set the source the parent branch

git branch new-branch-name source-branch



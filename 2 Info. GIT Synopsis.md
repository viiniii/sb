 #### Learn Git In 15 Minutes
https://www.youtube.com/watch?v=USjZcfj8yxE

#### To identify yourself with GIT
git config --global user.name "Your Name"
git config --global user.email " your@email.com "


#### Initializing a repository
git init


#### getting information about status of the repository
git status


#### adding the files to the staging area to be ready to be committed and tracked
git add filename.c filename2.js
git add .

#### making commits
git commit -m 'commit title' -m "Commit message"

#### showing all the commits and other
git log

#### going back to a commit
git checkout "commiy-hash"

#### showing all the branches
git branch

#### Creating a new branch
git branch 'new-branch-name'

#### going to the desired branch
git branch 'branch-name'

#### merging branches
git merge 'branch-name'

#### deleting a branch
git branch -d 'branch-name'

 #### generating a key locally using the SSH key Gen  command
ssh-keygen -t rsa -b 4096 -C "email@example.com"



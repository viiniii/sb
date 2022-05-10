# Learn Git In 15 Minutes #youtube
https://www.youtube.com/watch?v=USjZcfj8yxE 

To identify yourself with GIT
git config --global user.name "Your Name"
git config --global user.email " your@email.com "

Initializing a repository
git init

Getting information about status of the repository
git status

Adding the files to the staging area to be ready to be committed and tracked
git add filename.c filename2.js
git add .

Making commits
git commit -m 'commit title' -m "Commit message"

Showing all the commits and other
git log

Going back to a commit
git checkout "commiy-hash"

Showing all the branches
git branch

Creating a new branch
git branch 'new-branch-name'

Going to the desired branch
git branch 'branch-name'

Merging branches
git merge 'branch-name'

Deleting a branch
git branch -d 'branch-name'

Generating a key locally using the SSH key Gen  command
ssh-keygen -t rsa -b 4096 -C "email@example.com"

Showing remote servers you have configured
git remote -v


# Git and GitHub for Beginners - Crash Course #youtube 
https://www.youtube.com/watch?v=RGOj5yH7evk 

Adding remote repository
git remote add origin git@github.com:viiniii/romb.git

To push the current branch and set the remote as upstream, use:
git push --set-upstream origin master

# Getting Git on a Server
https://git-scm.com/book/it/v2/Git-on-the-Server-Getting-Git-on-a-Server#r_git_on_the_server

git clone --bare my_project my_project.git


pscp id_rsa.pub ubuntu@141.144.247.167:/home/ubuntu


# Git Command Cheat Sheet

##### Cloning your remote directory

##### Checking that status of your local repository

<<<<<<< HEAD
##### Pulling down all branches in a remote repo, not just the default branch
        git fetch --all

=======
>>>>>>> master
##### Creating a new branch for you to work on

##### See all branches in your remote repository
		git branch -a

##### Moving onto a branch

##### Deleting a branch
		git branch -d <branch name>

<<<<<<< HEAD
##### Moving your changes to the staging area
        git add <file name>

##### Committing your changes
        git commit -m '<commit message here>'

##### Pushing your commit to the remote repository
        git push origin <branch name>

##### Creating a branch and moving onto it.
        git checkout -b <new branch name>

##### Merging changes from another branch, to your current branch
        git merge <branch you want to merge with your current branch>

##### Pulling remote changes into your local repo
        git pull origin <branch name>
=======
##### Moving files while preserving git history
		git mv <source> <destination>

>>>>>>> master

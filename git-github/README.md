# A version control system (VCS)
tracks changes to a file or set of files over time

## Git vs GitHub
Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories.

Git Commands: Working With Local Repositories
git init
The command git init is used to create an empty Git repository. 
git add
Add command is used after checking the status of the files, to add those files to the staging area.

git commit
The commit command makes sure that the changes are saved to the local repository.
The command "git commit –m <message>" allows you to describe everyone and help them understand what has happened.
git status
The git status command tells the current state of the repository.


git config
The git config command is used initially to configure the user.name and user.email. This specifies what email id and username will be used from a local repository.


git config --global user.name “any user name”
git config --global user.email <email id>


git branch
The git branch command is used to determine what branch the local repository is on.
The command enables adding and deleting a branch.
# Create a new branch
  git branch <branch_name>
# List all remote or local branches
  git branch -a
# Delete a branch
  git branch -d <branch_name>


git checkout
The git checkout command is used to switch branches, whenever the work is to be started on a different branch.


# Checkout an existing branch
  git checkout <branch_name>
# Checkout and create a new branch with that name
  git checkout -b <new_branch>


git merge
The git merge command is used to integrate the branches together. The command combines the changes from one branch to another branch. 
It is used to merge the changes in the staging branch to the stable branch.
  ''git merge <branch_name>''


git remote 
The git remote command is used to create, view, and delete connections to other repositories. 

git clone
The git clone command is used to create a local working copy of an existing remote repository.

git pull 
The git pull command is used to fetch and merge changes from the remote repository to the local repository.


''git pull <branch_name> <remote URL>''


git push
The command git push is used to transfer the commits or pushing the content from the local repository to the remote repository.


''git push -u origin master''




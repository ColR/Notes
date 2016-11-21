#Git Notes#
git init - creates a working directory for the project using the current directory.

git init dir - creates a directory and uses it as the working directory for the repository.

git status - lists the status of the working directory

git add *filename* - adds the *filename* to the staging area

git add . - adds all files in the working directory to the staging area.

git diff *filename* - reports the difference between *filename* in the working directory and *filename* in the staging area.

git commit -m "commit message" - permenantly moves changes in the staging area to the repository.

git log - prints a log of the previous commits.

git show HEAD - shows the HEAD of the most recent commit. {sometimes -- is used as equivalent of HEAD}

git checkout HEAD *filename* - restores *filename* to its state befor the most recent commit.

git reset HEAD *filename* - removes *flename* from the staging area and restores *filename* to its state before the most recent commit.

git reset SHA - resets all files to their state at the SHA commit (SHA = first 7 characters of the commit).

git branch - identifies the current branch

git branch *new_branch* - creates a new branch called *new_branch*.

git checkout *branch_name* - switches to a different branch.

git merge *branch_name* - merges *branch_name* with the major branch.

git -d *branch_name* - deletes *branch_name*

git clone *remote_location* *clone_name* - clones a repository at a remote location (url, filepath, etc) on the local machine. Local git repository is *clone_name*

git remote -v lists the projects remotes

git fetch - downloads changes made on the remote repoitiry to the local origin/master branch (different from the local master)

git push ORIGIN *local-branch-name* - pushes local changes back to the remote repository.

# VITMAS_Task0_21BCE2700

**GIT COMMANDS**

# Git Config
$ git config--global user.name [name]
$ git config--global user.email [email]
It is used to add user's name and email address with user commit

# Git init
$ git init [repository name]
It is used to create a new repository.

# Git remote add origin
$ git remote add origin [url]
It is used to specify remote repository from local repository.

# Git clone 
$ git clone [url]
It is used to download a repository.

# Git add
$ git add [file]
It is used to add a file to the staging area.
$ git add*
It is used to add one or more files to the staging area.

# git commit
$ git commit -m [message to be displayed]
It is used to record snapshots permanently in the version history.

# git diff
$ git diff
It is used to find the differences between files which have not been staged yet.
$ git diff--staged
It is used to find the differences between files in the staging area and the latest version present.
$ git diff [first branch]...[second branch]
It is used to find the differences between two branches.

# git log
$ git log
It is used to show the version history for the current branch.
$ git log--follow[file]
It is used to show the version history of the file including changes in the name.

# git show
$ git show [commit]
It is used to show the metadata and content changes of the specified commit.

# git reset
$ git reset [file]
It is used to unstage the file but it preserves the file contents.
$ git reset [commit]
It is used to undo all the commits after the specified commit and preserves the changes locally.
$ git reset --hard [commit]
It is used to discard all history and goes back to the specified commit.

# git status
$ git status
It is used to show all the files that have to be committed.

# git rm
$ git rm[file]
It is used to delete the file from your working directory and stages the deletion.

# git fetch
$ git fetch
It is used to download all history from the remote tracking branches.

# git merge
$ git merge[branch name]
It is used to merge specified branche's history into the current branch.

# git push
$ git push [variable name] master
It is used to send the committed changes of master branch to your remote repository.
$ git push --all [variable name]
It is used to send all branches to your remote repository.
$ git push [variable name] [branch]
It is used to send the branch commits to your remote repository.
$ git push [variable name]:[branch name]
It is used to delete a branch on your remote repository.

# git pull
$ git pull [repository link]
It is used to fetch and merge changes on the remote server to your working directory.

# git branch
$ git branch
It is used to list all branches in the current repository.
$ git branch [branch name]
It is used to create a new branch with the specified branch name.
$ git branch -d [branch name]
It is used to delete the specified branch.

# git switch
$ git switch -c [branch name]
It is used to switch to the specified branch and updates the working directory.

# git tag
$ git tag [commitID]
It is used to give tags to the specified commit.

# git stash
$ git stash save
It temporarily saves all the modified tracked files.
$ git stash pop
It is used to restore the most recently stashed files.
$ git stash list
It is used to show all the stashed changesets.
$ git stash drop
It is used to discard the most recently stashed changeset.

# git checkout
$ git checkout [branch name]
It is used to switch from one branch to the other.
$ git checkout -b [branch name]
It is used to create a new branch and also switches to it.

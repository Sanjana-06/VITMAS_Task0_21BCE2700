# VITMAS_Task0_21BCE2700

**GIT COMMANDS**

# git Config
`$ git config--global user.name [name]`<br/>
`$ git config--global user.email [email]`<br/>
It is used to add user's name and email address with user commit

# git init
`$ git init [repository name]`<br/>
It is used to create a new repository.

# git remote add origin
`$ git remote add origin [url]` <br/>
It is used to specify remote repository from local repository.

# git clone 
`$ git clone [url]`<br/>
It is used to download a repository.

# git add
`$ git add [file]` <br/>
It is used to add a file to the staging area <br/>
`$ git add* <br/>`
It is used to add one or more files to the staging area.

# git commit
`$ git commit -m [message to be displayed]` <br/>
It is used to record snapshots permanently in the version history.

# git diff
`$ git diff` <br/>
It is used to find the differences between files which have not been staged yet.<br/>
`$ git diff--staged` <br/>
It is used to find the differences between files in the staging area and the latest version present <br/>
`$ git diff [first branch]...[second branch]` <br/>
It is used to find the differences between two branches <br/>

# git log
`$ git log` <br/>
It is used to show the version history for the current branch <br/>
`$ git log--follow[file]` <br/>
It is used to show the version history of the file including changes in the name <br/>

# git show
'$ git show [commit] <br/>'
It is used to show the metadata and content changes of the specified commit<br/>

# git reset
`$ git reset [file]`<br/>
It is used to unstage the file but it preserves the file contents <br/>
`$ git reset [commit]` <br/>
It is used to undo all the commits after the specified commit and preserves the changes locally <br/>
`$ git reset --hard [commit]` <br/>
It is used to discard all history and goes back to the specified commit <br/>

# git status
`$ git status` <br/>
It is used to show all the files that have to be committed <br/>

# git rm
`$ git rm[file]` <br/>
It is used to delete the file from your working directory and stages the deletion <br/>

# git fetch
`$ git fetch` <br/>
It is used to download all history from the remote tracking branches <br/>

# git merge
`$ git merge[branch name]` <br/>
It is used to merge specified branche's history into the current branch <br/>

# git push
`$ git push [variable name] master` <br/>
It is used to send the committed changes of master branch to your remote repository <br/>
`$ git push --all [variable name]` <br/>
It is used to send all branches to your remote repository <br/>
`$ git push [variable name] [branch]` <br/>
It is used to send the branch commits to your remote repository <br/>
`$ git push [variable name]:[branch name]` <br/>
It is used to delete a branch on your remote repository <br/>

# git pull
`$ git pull [repository link]` <br/>
It is used to fetch and merge changes on the remote server to your working directory <br/>

# git branch
`$ git branch` <br/>
It is used to list all branches in the current repository <br/>
`$ git branch [branch name]` <br/>
It is used to create a new branch with the specified branch name <br/>
`$ git branch -d [branch name]` <br/>
It is used to delete the specified branch <br/>

# git switch
`$ git switch -c [branch name]` <br/>
It is used to switch to the specified branch and updates the working directory <br/>

# git tag
`$ git tag [commitID]` <br/>
It is used to give tags to the specified commit <br/>

# git stash
`$ git stash save `<br/>
It temporarily saves all the modified tracked file s<br/>
`$ git stash pop `<br/>
It is used to restore the most recently stashed file <br/>
`$ git stash list` <br/>
It is used to show all the stashed changesets <br/>
`$ git stash drop` <br/>
It is used to discard the most recently stashed changeset <br/>

# git checkout
`$ git checkout [branch name]` <br/>
It is used to switch from one branch to the other <br/>
`$ git checkout -b [branch name]` <br/>
It is used to create a new branch and also switches to it <br/>

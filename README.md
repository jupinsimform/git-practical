# Git And Github

## Branching

        The git branch command lets you create, list, rename, and delete branches. It doesn't let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.

![git branch workflow](https://miro.medium.com/max/552/1*PiduCtSA7kMwdPiMZo1nHw.jpeg)

| Command        | Description          
| ------------- |:-------------:
|git branch |	List branches (the asterisk denotes the current branch)
|git branch -a |	List all branches (local and remote)
|git branch [branch name] |Create a new branch
|git branch -d [branch name] |Delete a branch
|git push origin --delete [branch name]	| Delete a remote branch
|git checkout -b [branch name]	| Create a new branch and switch to it
|git branch -m [old branch name] [new branch name]|	Rename a local branch
|git checkout [branch name]| Switch to a branch
|git checkout - |	Switch to the branch last checked out
|git checkout -- [file-name.txt] | Discard changes to a file
|git branch --merged | Shows the merged branches
|git branch --no-merged| Shows the unmerged branches





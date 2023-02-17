# Git And Github

## Merging

        Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. 

![git merge](https://wac-cdn.atlassian.com/dam/jcr:c6db91c1-1343-4d45-8c93-bdba910b9506/02%20Branch-1%20kopiera.png?cdnVersion=789)

| Command        | Description         
| ------------- |:-------------:
|git merge bugfix | Merges the bugfix branch into the current branch
|git merge --no-ff bugfix | Creates a merge commit even if FF is possible
|git merge --squash bugfix | Performs a squash merge
|git merge --abort | Aborts the merge
|git branch --merged | Shows the merged branches
|git branch --no-merged | Shows the unmerged branches




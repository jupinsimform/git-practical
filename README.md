# Git And Github

## Stashing
        The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy.Save un-commited work and safe from destuptive operation.

![git stash](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRSfgxcRWmL5etIiIFieAK_YwEmXaWtJsxitTEaxCDaPdrKcXz2TPoLQMSmksBw_Cyh-M&usqp=CAU)

| Command        | Description           
| ------------- |:-------------:
|git stash push -m “New tax rules”| Creates a new stash
|git stash list | Lists all the stashes
|git stash show stash@{1} | Shows the given stash
|git stash show 1 | shortcut for stash@{1}
|git stash apply 1| Applies the given stash to the working \dir
|git stash drop 1 | Deletes the given stash
|git stash clear | Deletes all the stashes


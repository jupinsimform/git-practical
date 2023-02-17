# Git And Github

## Undoing commits
| Command        | Description
| ------------- |:-------------:
|git reset --soft HEAD^  | Removes the last commit, keeps changed staged
|git reset --mixed HEAD^  | Unstages the changes as well
|git reset --hard HEAD^  | Discards local changes

## Reverting commits
| Command        | Description
| ------------- |:-------------:
|git revert 72856ea  | Reverts the given commit
|git revert HEAD~3..  | Reverts the last three commits

## change the last commit message
| Command        | Description
| ------------- |:-------------:
|git commit --amend | change the commit message
|git rebase -i HEAD~n | change commit message of previous n commit

## Viewing the history of a file
| Command        | Description
| ------------- |:-------------:
|git log| Full history
|git log --oneline| Summary
|git log --reverse| Lists the commits from the oldest to the newest
|git log -3  |  Shows the last 3 entries
|git log hash1..hash2  |  Range of commits
|git log file.txt | Shows the commits that touched file.txt
|git log --stat file.txt | Shows statistics (the number of changes) for file.txt
|git log --patch file.txt | Shows the patches (changes) applied to file.txt
|git log file.txt| Shows the commits that touched file.txt
|git log --stat file.txt | Shows statistics (the number of changes) for file.txt
|git log --patch file.txt | Shows the patches (changes) applied to file.txt

## Comparing commits
| Command        | Description
| ------------- |:-------------:
|git diff HEAD~2 HEAD | Shows the changes between two commits
|git diff HEAD~2 HEAD file.txt | Changes to file.txt only

## Viewing a commit
| Command        | Description
| ------------- |:-------------:
|git show 921a2ff | Shows the given commit
|git show HEAD | Shows the last commit
|git show HEAD~2 | Two steps before the last commit
|git show HEAD:file.js | Shows the version of file.js stored in the last commit
|git show HEAD~2:file1.txt |Shows the version of file stored in this commit
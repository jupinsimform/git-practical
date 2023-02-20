# Git And Github

## Pushing into remote repository
        The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.

## Pull form remote repository
        The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

| Tables        | Are           
| ------------- |:-------------:
|git push origin [branch name]|	Push a branch to your remote repository
|git push -u origin [branch name] |Push changes to remote repository (and remember the branch)
|git push |	Push changes to remote repository (remembered branch)
|git push origin --delete [branch name]	| Delete a remote branch
|git pull |Update local repository to the newest commit
|git pull origin [branch name]	| Pull changes from remote repository
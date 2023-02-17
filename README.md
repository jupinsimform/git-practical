# Git And Github

## Initialize
To create a new repo, you'll use the git init command. git init is a one-time command you use during the initial setup of a new repo. Executing this command will create a new .git subdirectory in your current working directory. This will also create a new main branch.


| Command        | Description         
| ------------- |:-------------:
|git init | create or initialize new Repo.
|git add file1.js           | Stages a single file
|git add file1.js file2.js  | Stages multiple files
|git add *.js               | Stages with a pattern
|git add .                  | Stages the current directory and all its content
|git commit -m “Message” | Commits with a one-line message
|git commit              | Opens the default editor to type a long message
|git status       | Full status
|git status -s    | Short status
|git clone url | Cloning a repository
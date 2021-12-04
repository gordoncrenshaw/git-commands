# Git Commands

These are the common git commands I used while coding.  

* git checkout -b "<branch_name>" - creates a new branch.
* git add <filename> - adds a single file containing code changes to the current branch.
* git add -A - adds all files containing code changes to the current branch.
* git rm <filename> - removes the deleted file from the project within the branch.
* git commit -m "<comment>" - commits the files added to the current branch.
* git push - pushes the changed files to the code server.   On the initial push, a "git push" 
command containing all necessary parameters will be provided which should be executed.  Once
executed, a http URL to the commits maybe returned where the pull request can be created.
* git status - retrieves the current state of git.
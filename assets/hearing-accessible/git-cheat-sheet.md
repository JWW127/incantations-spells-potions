# Git Cheat Sheet

`$ git status`
-- show which files have changes and are/aren't in staging area
`$ git add [file/files]`
-- add files to staging area
`$ git rm --cached [file/files]`
-- remove tracked files that have not been committed yet
`$ git commit -m "message about changes"`
-- add files in staging to git history with a message "message about changes"
`$ git log`
-- show git log history including: git-hash, user, date, message
`$ git log --oneline`
-- show minimalized log history with only the hash, message, branch changes
`$ git show git-hash`
-- show the commit associated with "git-hash" including comment and diffs(changes)
`$ git diff unstaged-file`
-- show the changes for a file that is yet to be staged or committed
`$ git commit --amend -m "new better message"`
-- amend the previous commit's message with "new better message"
`$ git push`
-- command to forward LOCAL changes REMOTE(github) repo
`$ git pull`
-- command to implement REMOTE(github) changes on LOCAL machine
`$ git branch`
-- show current branch on LOCAL machine
`$ git branch -r`
-- show REMOTE branches
`$ git branch -a`
-- show all branches LOCAL and REMOTE(github)
`$ git branch new-branch-name`
-- creates a new branch with the name "new-branch-name"
`$ git checkout branch-name`
-- switch current working branch to a branch named "branch-name"
`$ git checkout -`
-- switch working branch to previous working branch
`$ git push -u origin branch-name`
-- add a new branch with name "branch-name" to REMOTE(github) repository
`$ git checkout -b new-branch-name`
-- create a new branch named "new-branch-name" and checkout to newly created branch
`$ git branch -d name-of-branch-to-delete`
-- delete a branch with name "name-of-branch-to-delete"
`$ git pull -r origin main`
-- try to update historical LOCAL with new REMOTE, then add new LOCAL changes to the updated historical LOCAL
`$ git push -f`
-- force LOCAL changes to REMOTE(github)

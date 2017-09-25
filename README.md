# git_tools

- `git_add_upstream [upstream name]`
- `git_squash 2`  Squashes the last two commits
- `git_push` Pushes the current branch
- `git_commit <fileName>` searches for a filename and commits it, next prompt is for the commit message
- `gupdate` fetches the 'upstream' remote (git remote -v) and does a pull --rebase against it.
- `git_new_branch_commit <branch_name> <file(s)>` Creates a new branch, commits the files specified to that branch, then returns to the original branch. List the file name only for the commit, path for it is found searching from the current folder



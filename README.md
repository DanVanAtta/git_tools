# git_tools

Shell helper scripts to make working with git easier.

## Installation

- Clone this repository.
- Add the cloned folder to your path


## Commands

- `gup` => git pull --rebase orgin master   (consolidates and color codes output)
- `git_squash 2`  Squashes the last 'n' commits together
- `git_back` =>  git reset HEAD~1    "Pops" the last commit
- `git_back n` =>  git reset HEAD~n    "Pops" the last n commits
- `git_forward` => git commit . -m "<git commit message from the last git_back>"   Use this to commit current and use the same commit message as the last commit popped via "git_back"
- `git_squash_last` => `git add .; git commit . -m "." && git_squash 2`
- `git_branch_log`  Shows a list of all branches and the time of last commit to those branches


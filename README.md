# git-commands
Assorted git commands. Most (all) require bash

* git_backport: creates a new branch named from the current branch but applied to another base branch and cherry-picks the last commit on to it. Useful for single-commit backports
* git_branch_rm: removes a branch both locally and remotely on the user's fork
* git_repush: force pushes the current branch to the user's fork
* git_pull_request: creates a GitHub pull request for the current branch against the original repository
* git_interactive_checkout: Shows a menu which allows you to select from the most recent branches

To create a new branch, use the command `git branch <branch_name>`
To checkout a branch, use the command `git checkout <branch_name>`

Git does not commit to the new branch automatically. It is necessary to move to this new branch, or check out to it.
We can check out to any branch, but also we can checkout to any commit. To do so, use `git checkout <commit_hash>` or
`git checkout <branch_name~upward_commits>`. For example, if I want 2 commits above the head commit: `git checkout master~2`
This is called "detaching the head". head is where you are (which commit you are)

## Pushing
If we want our work to be available to other people in the same project, we push
The command is git push <repo_name> <branch_name>. Example: `git push origin feature_1`
This copies all of the new commits into the cloud repository

## Pulling
this downloads the cloud repository to the local repository
### Pull
`git pull` -> suitable when working with only one branch. 
git pull gets the new commits and merges them with our local repo

### Fetch
`git fetch` is the same as a pull, but it doesn't merge the changes into our local repository.
So, it just gets the commits from the cloud and stores them in the .git folder. You can merge all or some of them
You can even seehow the new commits are going to affect the local repo if you merge them

### Problem w/ Pull
The problem comes when using multiple branches.
It is better to use **git fetch** and **git merge** instead of **git pull**.
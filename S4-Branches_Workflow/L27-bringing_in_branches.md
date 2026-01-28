Two scenarios where this is needed:
1 - if we're working in that branch with other people, we might wanna make changes to that and push then
2 - someone finished a branch work and we want to merge it to our local repo

## Scenario 1
when you fetch the new branch, it is added to your .git folder with the name repo_name/branch_name. Example: origin/feature_2
to create a local branch from the pulled branch and check out to it, you need to enter the command:
git checkout -b desired_branch_name pulled_branch_name
In this example: `git checkout -b feature_new origing/feature_2` -> this new local branch feature_new now tracks remote feature_2

## Scneario 2
you can now merge it to your current branch (`git merge branch_name`)> In the example: `git merge origin/feature_2`
merge command will merge the informed branch into the checked out branch as long as the checked out branch does not have any modified file.
Two possible scenarios
- Reverting change before pushing it to the remote - easy. You cand do whatever you want
- Reverting change after pushing it to the remote (someone might have done some work) - hard. unless you're pushing to a branch only you is working, never push before testing. You can commit (locally) as you want, but do not push.

Before pushing, you're allowed to permanently delete commits. Deleting a commit and you cannot bring it back.
We can delete one or various commit with *git reset <commit>*. This will delete all commits up to and including the referenced commit.
Remeber relative referencig of commits (HEAD^, HEAD~3)

After pushing it, someone might have worked with the code you pushed to the remote
You **shouldn't delete commits irreversibly** just in case someone used them!

What we can do is revert the commits, which creates a new commit that undoes what former did. Nothing is deleted.
We use *git revert <commit>*


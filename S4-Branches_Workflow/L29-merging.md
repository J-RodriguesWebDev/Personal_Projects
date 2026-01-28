first thing to do is to check out to the branch which will receive the other branch to be merged.
That mean, if you want to bring content from feature_2 branch to master, you need to checkou out to master first.

There is fast-forward merge and true merge types
Fast-forward: the branch to be merged is an extension of the receiving branch. In this case, easy peasy. changes are brought and head is placed to the commit created to that merge. No conflicts

True merge: there are changes in the same file and in the same line between branches creating a conflict that needs to be solved.

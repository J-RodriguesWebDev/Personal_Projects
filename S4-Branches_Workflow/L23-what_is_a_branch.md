Initially there is no commits and nothing is added to our local repository
Then we add some files
Then we commit them
Somewhere inside th .git folder, the commit gets stored (along withdiffs and what files were modified, by whom, etc.)

If we make changes, and add them and commit them, we don't get a new file. The new commit is alos added onto the same file.
So now, the file that stored the original commit now references **two different commits** (and all their details)
The file which has these different commits is called a branch.
diff is the differences between one file and another.
`diff file1 file2 -u` -> this returns the differences between file 1 and file 2

in order to add a file to the staging area: git add file_name
`git add file1.md` -> adds file1.md to staging area

in order to add all files to the staging area: git add file_name
`git add *` -> adds all files from the directory to staging area

in order to remove a file from the staging area: git rm --cached file_name
`git rm --cached file1.md` -> removes file1.md from staging area
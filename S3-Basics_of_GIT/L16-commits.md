to commit a file (moving from staging to the repository), run git commit -m "*message*"
`git commit -m "this is a commit"` commits the files in staging area with the given message

if .gitignore file is not created, it is just a matter of creating a new file in directory root with this name

to config git core text editor: git config --global core.editor *editor*
`git config --global core.editor vscode` -> Sets VS Code as core editor
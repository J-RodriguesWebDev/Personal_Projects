## Adding a Remote
A remote is a copy of your Git repository that isn't local to your computer
Other people can access it if you grant permission

We need to add a remote before being able to use it: git remote add repo_name repo_url
`git remote add (origin) <repo url>` -> origin is the common name when only one repo exists
You need to create a project in the repo first (bitbucket, github). Otherwise, there is no URL to add

## Cloning a Remote
Cloning is bring the online repo to your computer. Can be done instead of git init.
If we clone a Bitbucket project, it gets automatically added as a remote
In the console, type `git clone <repo_url>`
This will bring all the commits and files in the repo


Firstly check by `git remote add origin <SOME-URL>/<SOME-REPOSITORY-NAME>.git` command whether it showing this `fatal: remote origin already exists.` error or not.

#### If it is showing the error then follow these steps:
- If you want to be sure that remote called `origin` exists then use `git remote` command
- If you want more detail over that use `git remote -v` command
#### We can now resolve the issue in many ways like:
1. You can just remove the existing remote via `git remote remove origin`
2. Or Update the existing remote URL via `git remote set-url <REMOTE-NAME> <NEW-URL>`

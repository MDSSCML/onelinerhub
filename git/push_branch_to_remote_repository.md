# How to create a local branch in remote repository

first you should create a branch `locally`
```bash
git push --set-upstream origin branch_name 
```

- --set-upstream - track new upstream branch with git
- origin - your remote repository name (most of the time is origin)
- branch_name - local branch you want to push to remote repository
# Videos From 1 To 5

- What is git 
- What is github
- Why we need them
- Some Words We'll hear

## some commands for git

```
git clone <repo link>
git status
git add <filename>
git restore --staged <file_name>
git reset HEAD <file_name>
git commit -m "your message"
git push <branchname> <remotename>
git branch
```

- we use `git clone` to clone the repo from the remote to local
- we use `git status` to show the state of the working dir
- we use `git add` to transfer file from the working dir to the staging area
- we use `git restore` to remove the file from the staging area
- we use `git reset` for the same reason as `git restore`
- we use `git commit` to transfer the file from the staging area to the local repo
    we use `-m` to write the message of the commit
- we use `git push` to push the commits into the remote repo
- we use `git branch`to know all the branches in the local as you will use more than one branch

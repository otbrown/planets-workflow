# Useful Git Commands

## Remotes
- Fetch all branches from remote: `git fetch <remote-name>`
- Set upstream branch: `git branch -u <remote-name>/<branch-name> <branch-name>`
- Create a branch from remote and switch to it: `git checkout -b <branch-name> <remote-name>/<branch-name>`
  - In Git >= 1.6.6 should just be able to do `git checkout <branch-name>` if there is only one remote. 

## Branches
- Create new branch: `git branch <branch-name>`
- See local branches: `git branch -v`
- See remote branches: `git branch -r`
- See all branches (local and remote): `git branch -a`
- Switch to branch: `git checkout <branch-name>`
- Delete local branch: `git branch -d <branch-name>`
- Force delete local branch: `git branch -D <branch-name>`

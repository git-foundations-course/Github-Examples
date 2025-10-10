## Git hidden folder
There is a hidden folder called `.git` which tells us that our project is a git repo.

If we want to create a git repo in a new project we should create a new folder and initialize that repo using the command
`git init`.

## Cloning 
We can clone in three ways:
HTTPS,SSH and Github CLI

## HTTPS 

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```
```sh
git clone https://github.com/git-foundations-course/Github-Examples.git
```

## Opening README.md from terminal
`code README.md`
If after running the command `git status` we see that some files are untracked but we want all of them to be tracked  we can run the command `git add all`. 
## Commits
`git commit` used to commit code 
## Branches

## Remotes

## Stashing

## Merging

## Add
Add is used to stage changes that will be included in the commit.
## Reset
Reset allows us to undo local changes to the state of a Git repo `git reset`.
> git reset will revert a git add

## Configuration file

The gitconfig file stores important local or global configurations for git such as email, name, editor, etc. 
```sh
git config --global user.name "John Doe"
 
```
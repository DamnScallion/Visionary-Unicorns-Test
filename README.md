# Visionary-Unicorns-Test
Just for testing some CV tools perform

## Useful git commands:

### Git clone
git clone <https://name-of-the-repository-link>

### Git branch
###### Creating a new branch:
git branch <branch-name>
###### Viewing branches:
git branch or git branch --list
###### Deleting a branch:
git branch -d <branch-name>

### Git add
###### To add everything at once:
git add .

### Git commit
git commit -m "commit message"

### Git pull
git pull <remote>

### Git push
git push <remote> <branch-name>

## Git Sample Usage:
###### Pull updated source code from remote branch <main> and merge it with you local branch code
git pull origin main
###### Add all locally changed files ready for commit
git add .
###### Save all changed files as a checkpoint ready for push
git commit -m 'feature: yolo bbox attributes deconstruction'
###### Push these changed files to a remote repository at <main> branch
git push origin main

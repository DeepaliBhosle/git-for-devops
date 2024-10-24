## Basic Git Commands
- **Initialize a new Git repository**  
  `git init`

- **Clone an existing repository**  
  `git clone <repository-url>`

## Staging and Committing
- **Add files to staging**  
  `git add <file>`  
  `git add .` (to add all files)

- **Commit changes**  
  `git commit -m "commit message"`

## Viewing Changes
- **Show the status of the repository**  
  `git status`

- **View commit history**  
  `git log`

- **View changes in the working directory**  
  `git diff`

## Branching
- **List all branches**  
  `git branch`

- **Create a new branch**  
  `git branch <branch-name>`

- **Switch to a branch**  
  `git checkout <branch-name>`

- **Create and switch to a new branch**  
  `git checkout -b <branch-name>`

## Merging
- **Merge a branch into the current branch**  
  `git merge <branch-name>`

## Remote Repositories
- **Add a remote repository**  
  `git remote add <name> <repository-url>`

- **Fetch changes from a remote repository**  
  `git fetch <name>`

- **Push changes to a remote repository**  
  `git push <name> <branch-name>`

- **Pull changes from a remote repository**  
  `git pull <name> <branch-name>`

## Undoing Changes
- **Unstage a file**  
  `git reset <file>`

- **Remove a file from the staging area without deleting it**  
  `git rm --cached <file>`

- **Restore a deleted file**  
  `git restore <file>`

## Tagging
- **Create a new tag**  
  `git tag <tag-name>`

- **List all tags**  
  `git tag`

- **Push tags to remote**  
  `git push <name> --tags`

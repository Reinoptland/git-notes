# Using git branches & PR

1. Make a folder: `mkdir folder-name`
2. cd into the folder: `cd folder-name`
3. Start a git repo: `git init`

## Making a commit

1. Made a file, notes.md
2. Wrote some notes (code)
3. Openened the vs-code git integration
4. Staged the changes (+) for the files you want to commit
5. Wrote a message in the input field
6. Hit the checkmark (✓) commit button

## How to see a log of your commits

1. Open a terminal in the same folder where your git repo is
2. In the terminal use `git log` command
3. You should see a list of commits, scroll or us up down keys to look at the list
4. If you want to exit use `:q`

## Adding a remote

On github

1. Go to github
2. Click the green "New" button
3. Give your repo a name
4. Click create

In your terminal you use the following commands to link your local git to the git repository on github:

1. `git remote add origin <git url>`
2. Check if the remote was added with: `git remote -v`

## Pushing your master or main branch

1. Rename our branch to main: `git branch -M main`
2. Push our branch to github: `git push -u origin main`
3. Go to github, refresh and check if your files are there

## Don't push to main

Unless

- Selfstudy
- Working alone
- Emergency

## Creating a new branch

1. Create a new branch and switch to it with `git checkout -b <brachname>`
2. Feel free to add new commits to this branch

## Switching between branches

1. Switching back to main `git checkout main`

note: Some code might dissapear or appear

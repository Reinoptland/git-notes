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

## Pushing your new branch

1. In the terminal use `git push origin <branch name you are on>`
2. Go to github and verify that the new branch is there

## Making a pullrequest

1. Go to github
2. Click the green button "Compare and Pullrequest"
3. Other go to pullrequest and make a pullrequest manually
4. Write a little summary for your colleague
5. Click "Create Pullrequest"
6. Ask your colleague to review -> they will merge the pullrequest into main
7. Or they might give you feedback and you will need to push changes again
8. You can check by switch to main on github and inspecting the files

## Pulling the changes

Your main branch on your machine is now behind
You need to update it by pulling the changes from github

1. Switch to the main branch
2. Use `git pull origin main` to pull the changes
3. Inspect the files and see that you are up to date

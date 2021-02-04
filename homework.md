# Homework 02-04-2021

## Git and Github Part One

### Initial Steps

- Create a new folder called git-homework
- Create a file inside that folder called index.js
- Initialize git
- Push to github

### Branches / Merging

- Go back to the terminal
- Create a new branch called branchOne
- On line one of your index.js file add a console.log('Hi')
- Push this branch up to github
- Merge that branch into your master branch on github
- Go back to the terminal
- Switch back to the master branch
- Pull down the latest code
- Make sure you get rid of all branches online and locally except the master branch

### Branches / Merging Part Two

- Create a new branch called branchTwo
- On line two of your index.js file declare a variable called name and assign it your name as a string
- Commit and Add your code
- Switch back to the master branch
- Merge this branch into your master branch
- Push your new code up to GitHub
- Make sure you get rid of all branches online and locally except the master branch

### Stash / Branches / Merging

- Create a new branch called stash-practice
- On line three add a second console.log() to your index.js file
- Stash your changes and swap back over to the master branch
- Add a new file called new-file.py
- Add a print('hello') to this file
- Add, commit and push that up to github
- Swap back to your stash-practice branch
- Bring back your stashed changes
- Don't forget to clear your stash
- Finsh your console log by logging 'it works'
- Add, commit and push that up to github
- Merge the stash-practice to your master branch on GitHub
- Make sure to pull all the changes to the master branch locally
- Make sure you get rid of all branches online and locally except the master branch

### Merge Conflict

- On Github open index.js and change line ones code to console.log('Hi from Online')
- Create a new branch locally called onlineMergeConflict
- Inside your index.js file change line ones code to console.log('Hi from local')
- Push your code online
- Go through the steps of merging that branch into master on GitHub. You will have a conflict.
- After fixing the conflict, make sure the local and online master branch have the same code
- Make sure you get rid of all branches online and locally except the master branch

### Merge Conflict Part Two

- Locally Create a new branch called localMergeConflict
- Open your new-file.py file and change line ones code to print('Hi from local')
- Commit your changes but DON'T PUSH
- On Github open new-file.py and change line ones code to print('Hi from Online')
- Locally checkout the master branch and pull down the new changes
- Merge your localMergeConflict branch into your master branch
- You will run into a merge conflict... fix the issues
- After fixing the conflict, make sure the local and online master branch have the same code
- Make sure you get rid of all branches online and locally except the master branch

### Revert A Single File Back

- Inside your master branch
- Revert the index.js file back to the initial commit

### Helpful Git Commands

```
$ git init
$ git status
$ git add .
$ git commit -m "your commit msg"
$ git push
$ git pull
$ git fetch
$ git branch
$ git checkout -b branchName
$ git checkout branchName
$ git merge branchName
$ git branch -d branchName
$ git stash
$ git stash apply
$ git stash list
$ git stash clear
$ git log
$ git checkout commitId fileName.extension
```

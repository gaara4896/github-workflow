# Git workflow

### Initialize repository

1. Initialize your local repository

  `git init`

1. Create a README.md and edit it

  `touch README.md`

  `vim README.md` or `nano README.md`

   or

   `echo "# YourRepoName" >> README.md`

1. Create .gitignore to ignore files that should not be included in repository, eg .class or .bin

  `touch .gitignore`

  `vim .gitignore` or `nano README.md`

1. Create an empty repository *SHOULD NOT INCLUDE .gitignore or README.md* on Github

1. Add remote and initial commit

  `git remote add origin https://github.com/yourid/reponame`

  `git add -A`

  `git commit -m "Initial Commit"`

### To Contribute

1. To contribute, please make a fork on your repository main line

1. Clone your github repository

  `git clone https://github.com/yourid/reponame`

1. Create a new branch to work and checkout

  `git checkout -B branch-name`

1. Commit your new file into branch

  `git add -A`

  `git commit -m "Commit Message"`

1. Push the update into your Github repository

  `git push -u origin branch-name`

  or
  
  `git push`

1. Make a pull request to master branch and wait for everyone consent

1. Resolve conflict if any

1. (Optional) Delete branch if necessary

  `git branch -d branch-name`
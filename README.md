# Git workflow

### Initialize repository

*_If you are using Windows, download Git [here](https://git-scm.com/downloads)_*

*_If you are using macOS, Git is already included_*

*_If you are using Ubuntu/Debian, use `sudo apt install git`_*

#### 1. Initialize your local repository

  _For Linux/Mac/Windows_

  `cd` to your project folder and then
  
  `git init`

#### 2. Create a README.md and briefly describe your project

  _For Linux/Mac/Windows_

  `echo [# YourRepoName] >> README.md`
  
#### 3. Create .gitignore and add files that should not be included in the repository (eg. node_modules/ or .gradle/)

  _For Linux/Mac_
  
  `vim .gitignore` or `nano .gitignore`
  
  _For Windows_
  
  `notepad .gitignore`

#### 4. Create an empty repository on GitHub. *Important:* Uncheck _Initialize this repository with a README_

#### 5. Add remote and initial commit

  _For Linux/Mac/Windows_
  
  `git remote add origin https://github.com/[your github id]/[your repo name]`

  `git add -A`

  `git commit -m "Initial Commit"`

---------

### To Contribute

1. Clone the GitHub repository to your computer

  `git clone https://github.com/[github id]/[repository name]`

1. Create a new branch and checkout

  `git checkout -B [branch-name]`

1. Commit your edits into your branch

  `git add -A`

  `git commit -m "[Commit Message]"`

1. Push the update into your Github repository
  
  `git push`

1. Make a pull request to master branch on GitHub

1. Resolve any conflicts

1. (Optional) Delete your branch

  `git branch -d [branch-name]`

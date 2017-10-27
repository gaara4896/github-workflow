# Git workflow

### Initialize repository

*If you are using Windows, download Git [here](https://git-scm.com/downloads)*

#### 1. Initialize your local repository

  _For Linux/Mac/Windows_

  `cd` to your project folder and then
  
  `git init`

#### 1. Create a README.md and edit it

  _For Linux/Mac_

  `echo "# [YourRepoName]" >> README.md`
  
  _For Windows_
  
  `echo "# [YourRepoName]" >> README.md`
  
#### 2. Create .gitignore to ignore files that should not be included in repository, eg .class or .bin

  _For Linux/Mac_
  
  `vim .gitignore` or `nano .gitignore`
  
  _For Windows_
  
  `notepad .gitignore`

#### 3. Create an empty repository on GitHub. *Important:* Uncheck _Initialize this repository with a README_

#### 4. Add remote and initial commit

  _For Linux/Mac/Windows_
  
  `git remote add origin https://github.com/[your github id]/[your repo name]`

  `git add -A`

  `git commit -m "Initial Commit"`

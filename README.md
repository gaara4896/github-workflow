# Git workflow

### Initialize repository

*If you are using Windows, download Git [here](https://git-scm.com/downloads)*

1. Initialize your local repository

  `cd` to your project folder and then
  
  `git init`

1. Create a README.md and edit it

  *For Linux/Mac*

  `echo "# [YourRepoName]" >> README.md`
  
  *For Windows*
  
  `echo "# [YourRepoName]" >> README.md`
  
2. Create .gitignore to ignore files that should not be included in repository, eg .class or .bin

  *For Linux/Mac*
  
  `vim .gitignore` or `nano .gitignore`
  
  *For Windows*
  
  `notepad .gitignore`

3. Create an empty repository on GitHub. *Important:* Uncheck _Initialize this repository with a README_

4. Add remote and initial commit

  *For Linux/Mac/Windows*
  
  `git remote add origin https://github.com/[your github id]/[your repo name]`

  `git add -A`

  `git commit -m "Initial Commit"`

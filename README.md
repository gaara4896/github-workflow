# Git workflow

### Initialize repository

##### Windows

download Git [here](https://git-scm.com/downloads)*

##### Linux

- Deb based

   `sudo apt-get install git`

- RPM Family

   `sudo yum install git`

- Fedora

   `sudo dnf install git`

- Arch

   `sudo pacman -S git`

#### 1. Initialize your local repository

  _For Linux/Mac/Windows_

  `cd` to your project folder and then
  
  `git init`

#### 2. Create a README.md and edit it

  _For Linux/Mac_

  `echo [# YourRepoName] >> README.md`
  
  _For Windows_
  
  `echo [# YourRepoName] >> README.md`
  
#### 3. Create .gitignore to ignore files that should not be included in repository, eg .class or .bin

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

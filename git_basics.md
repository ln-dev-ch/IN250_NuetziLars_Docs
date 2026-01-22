
## Git Basics

#### Create new Repo in Github
1. Go to [https://github.com/]
2. Click "Create repository" on the left
3. Set Owner, Name and Description
4. Leave rest "as it is"
5. Click "Create repo"


#### Clone remote repo to local
1. Open Terminal in VSCode
2. Navigate to target local folder
3. Use git clone to get repo to local folder:
`git clone https://github.com/ln-dev-ch/IN250_NuetziLars_Docs.git`
4. The repo address can be found on the github repo page


#### Add file to commit
1. copy file to local git repo
2. navigate into repo
3. Use git add to add the file to next commit
`git add .\markdown_basics.md`

#### Commit changes
1. Use git commit to commit changes locally
`git commit -m "Initial Commit"`

#### Add gitignore
1. Use new-item to create gitignore file
`new-item .gitignore`
2. Add content to file 
3. Add to staging area with git add
4. Add new commit with comment

#### Create second local repo
1. Create new folder
2. Navigate into it
3. Use git init
`git init`

#### Add remote origin
1. Use git remote add origin to set initial origin url
`git remote add origin https://github.com/ln-dev-ch/IN250_NuetziLars_Docs.git`
2. Verify remote settings
`git remote` - for list of remote repos
`git remote show origin` - show links of remote repo origin

#### Pull from origin
1. try pulling
`git pull origin`
2. get error message - no branch

#### Push original repo
1. Switch to original repo
2. Use git push and provide remote-name and branch-name
`git push origin main`
3. Pushes the local repo to remote

#### Pull to secon repo
1. Switch to second repo
2. Use git pull again
`git pull origin main`
3. success

### Why use git?
Use version control for shared software development
Enable visibility: Who changed what and when?
Enable rollbacks & branching

Use "git commit git push" because else your local precious changes are lost





## Git Basic Merge
Get the current main from remote
`git pull origin main`

Switch to main branch
`git checkout main`

Create new branch
`git checkout -b feature-branch-name`

Work on changes

Add changed files to staging
`git add .\git_merging.md`

Commit Changes
`git commit -m "Added basic merging doc"`

Switch to main branch again
`git checkout main`

Merge feature branch into main
`git merge feature-branch-name`

If needed add --no-ff to Merge:
`git merge --no-ff feature-branch-name`
## Git Branching Practice

### Basic `git` commands

* `git init` - create a new local repo
* `git add .` - add current working directory to git index
* `git commit -m "message"`  commit changes to local repo

### Basic Branching
* `git branch branchName` - create local branch named `BranchName`
* `git checkout branchName` move to branch `branchName`
* `git branch` - display local branch
`git push -u origin testBranch`

`git checkout -b new branch` - create an check out branch `new branch`.

### Merging
* Add and commit local branch.
* Pish local branch to remote.
* Pull master from remote to other branches
```bash
git checkout newBranch
git pull origin master
```

* Resolve merge conflicts
* Commit and push local branches

```bash
git add .
git commit -m 'mergin master with branch'
git push origin newBranch
```

* On github, create pull request
* Teammates merge pull request into master.

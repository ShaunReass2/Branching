## Git Cheat Sheet

***************  Brief reference of various git commands  ******************
    ***************  Also practice with Git branching  ******************


* `git init` - initialize a local git Repository in working directory
* `git status` - show stat of local Repository
* `git log` - list commit history
* `git log -- oneline` - compact commit hisotry
* `git add` - stage current directory in git index
* `git commit -m "msg"` - commit work to local Repository with commit message "msg"
* `git config -l` - shows all of git's settings

### Branching

* `git branch` - list local branches
* `git branch newBranch` - create local branch
* `git checkout newBranch` - move to branch newBranch

* `git pull origin main` - pull in and merge all branches

* `git diff sha` - show diffs between current commit and commit id `sha`
* `git diff oneBranch otherBranch` - show diffs between 'oneBranch' and `otherBranch`

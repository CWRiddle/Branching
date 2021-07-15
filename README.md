### Git Cheat Sheet

* 'git init' - Initialize a local git repo in working directory
* 'git status' - show state of local repo
* 'git log' - list commit history
* 'git log --oneline' - Compact commit history
* 'git config -l' - does something...
* 'git add .' - stage current directory in git index
* 'git commit -m "msg"' - commit work to local repo with commit message "msg"

### Branching
* 'git branch' - list local branches
* 'git branch newBranch' - create local branch (replace newBranch with name of new branch to be created)
* 'git checkout newBranch' - Move to branch 'newBranch'

### Remote Repos
* `git remote add alias url` - add `alias` as name for remote repo `url` in project configuration
* `git push alias aBranch` - push local commits to remote repo `alias`'s branch `aBranch`
* `git pull alias aBranch` - pull remote `aBranch` from `alias` into current local branch

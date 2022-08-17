## Git and Git Branching Cheat Sheet

Categories of git commands and practicing with branching.
### Basic commands
* `git init` - initialize current directory with repository
* `git add .` - add all new or changed files in the current directory to git index, staging them for commit
* `git commit -m "some message"` - commit staged changes to local repository

### Info commands
* `git status` - show the status of current working directory
* `git log` - list commmit history
* `git log --oneline` - list commit history (compact)
* `git config -l` - list local git configuration settings

### Branch commands
* `git branch` - list local branches highlight current branch
* `git branch branchName` - create branch `branchName`
* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b otherBranch` - switch to branch `otherBranch` creating it if it does not exist

### Other commands
* `git help` - list git subcommands and options
* `git config --help` - show options for `git config`

# Basic Git commands

* `git init <directory>` - Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository. 
* `git clone <repo>` - Clone repo located at `<repo>` onto local machine.
* `git config` - Set Git configuration such as username and email address.
* `git add <directory>` - Stage all changes in `<directory>` for the next commit.
* `git commit -m "<message>"` - Commit the staged snapshot, but instead of launching a text editor, use `<message>` as the commit message.
* `git status` - List which files are staged, unstaged, and untracked.
* `git log` - Display the entire commit history using the default format.
* `git diff` - Show unstaged changes between your index and working directory.
* `git reset <file>` - Remove <file> from the staging area, but leave the working directory unchanged. This unstages a file without overwriting any changes.
* `git commit --amend` - Replace the last commit with the staged changes and last commit combined. Use with nothing staged to edit the last commit’s message.
* `git rebase <base>` - Rebase the current branch onto `<base>`. `<base>` can be a commit ID, a branch name, a tag, or a relative reference to HEAD.
* `git reflog` - Show a log of changes to the local repository’s HEAD.
* `git branch` - List all of the branches in your repo. Add a `<branch>` argument to create a new branch with the name `<branch>`.
* `git checkout -b <branch>` - Create and check out a new branch named `<branch>` . Drop the -b flag to checkout an existing branch.
* `git merge <branch>` - Merge `<branch>` into the current branch.
* `git remote add <name> <url>` - Create a new connection to a remote repo using `<url>`
* `git fetch <remote> <branch>` - Fetches a specific `<branch>`, from the repo.
* `git pull <remote>` - Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.
* `git push <remote> <branch>` - Push the branch to `<remote>` , along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist. 

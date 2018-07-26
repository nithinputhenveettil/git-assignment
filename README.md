##Basics codes in Git

* `git init <directory>`
    * Create empty Git repo in specified directory.
* `git clone <repo>`
    Clone repo located at <repo> onto local machine.
* `git config user.name <name>`
    * Define author name to be used for all commits in current repo.
* `git add`
    * Stage all changes in <directory> for the next commit.
* `git commit -m "<message>"`
    * Commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.
* `git status`
    * List which files are staged, unstaged, and untracked.
* `git log`
    * Display the entire commit history using the default format.
* `git diff`
    * Show unstaged changes between your index and working directory.
* `git reset <file>`
    * Remove <file> from the staging area, but leave the working directory unchanged.
* `git commit --amend`
    * Replace the last commit with the staged changes and last commit
combined.
* `git rebase <base>`
    Rebase the current branch onto <base> . <base> can be a commit ID,a branch name, a tag, or a relative reference to HEAD .
* `git reflog`
    * Define author name to be used for all commits in current repo.
* `git branch`
    * List all of the branches in your repo.
* `git pull <remote>`
    * Fetch the specified remote’s copy of current branch and immediately
merge it into the local copy.
* `git checkout -b <branch>`
    * Create and check out a new branch named <branch> .

######END

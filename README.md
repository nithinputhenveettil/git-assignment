## Basic Git Commands

# Config

```
# Setting System Username/Email
git config --system user.name "Mohammed Sherif"
git config --system user.email "sherif@qburst.com"

# Setting Global Username/Email
git config --global user.name "Mohammed Sherif"
git config --global user.email "sherif@qburst.com"

# Setting Local Username/Email
git config [--local] user.name "Mohammed Sherif"
git config [--global] user.email "sherif@qburst.com"
```

# Creating Projects

```
# Creating an empty GIT repository
git init

# Clone a Repo from URL
git clone <url>
```

# Staging and Committing

```
# Staging file
git add <file-name>

# Committing to a repository
git commit -m "Commit Message"

# Show working tree status
git status

# Show changes between commits
git diff <commit>

# Reset current HEAD to a the specified commit
git reset --hard <commit>

# Remove files from the working tree
git rm <file>
```

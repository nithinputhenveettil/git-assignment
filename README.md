# SAMPLE PROJECT
This is a sample project to learn about Git.

## BASIC Git COMMANDS

* git config --global user.email	:Configure the author name and email address to be used with commits.
* git init			:Configure a folder to be a Git repository
* git clone /path/to/repository	:Create a working copy of a local repository
* git clone username@host:/path/to/repository	:For a remote server, use
* git add *			:Add one or more files to staging 
* git commit -m "Commit message"	:Commit changes to head 
* git push origin master		:Send changes to the master branch of your remote repository
* git remote add origin <server>	:If you haven't connected your local repository to a remote server, add the server to be able to push to it.
* git checkout -b <branchname>	:Create a new branch and switch to it
* git pull			:Fetch and merge changes on the remote server to your working directory
* git merge <branchname>		:To merge a different branch into your active branch
* git diff			:View all the merge conflicts
* git checkout -- <filename>	:If you mess up, you can replace the changes in your working tree with the last content in head
* git reset --hard origin/master	:drop all your local changes and commits, fetch the latest history from the server and point your local master branch	
* git grep "abc"			:Search the working directory for abc

### Contributing
Pull requests are welcome

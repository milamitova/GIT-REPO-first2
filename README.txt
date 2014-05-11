$ mkdir ~/Hello-World
# Creates a directory for your project called "Hello-World" in your user directory

$ cd ~/Hello-World
# Changes the current working directory to your newly created directory

$ git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/Hello-World/.git/

$ touch README
# Creates a file called "README" in your Hello-World directory

$ git remote add origin https://github.com/milamitova/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the "master" branch to GitHub
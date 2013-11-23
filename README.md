glowing-badass
==============
mkdir ~/Hello-World
# Creates a directory for your project called "Hello-World" in your user directory

cd ~/Hello-World
# Changes the current working directory to your newly created directory

git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/Hello-World/.git/

touch README
# Creates a file called "README" in your Hello-World directory

git add README
# Stages your README file, adding it to the list of files to be committed

git commit -m 'first commit'
# Commits your files, adding the message "first commit"

git remote add origin https://github.com/tammytwotone/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository

git push origin master
# Sends your commits in the "master" branch to GitHub

git clone https://github.com/username/Spoon-Knife.git
# Clones your fork of the repository into the current directory in terminal





git clone https://github.com/glowing-badass/Spoon-Knife.git
# Clones your fork of the repository into the current directory in terminal

cd Spoon-Knife
# Changes the active directory in the prompt to the newly cloned "Spoon-Knife" directory
git remote add upstream https://github.com/octocat/Spoon-Knife.git
# Assigns the original repository to a remote called "upstream"
git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files

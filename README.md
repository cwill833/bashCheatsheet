# Bash command referance

## Git controls

**to start a repository**  
*git init*

**to clone the repository with the fork link**  
*git clone (enter fork url with no ())*

**to get updates from original(remote) repo**  
*git remote add upstream (enter original repo https with no ())*

**to update your local repo with remote repo**  
*git pull upstream master

**once changes are made to local repo,**   
**need to add these changes**  
*git add -A*
    * this adds all changes from folder

*git add fileName
    * will only add selected file

**if you do not want to unstage files**  
*git reset -A*
    * this unstaged all changes in folder

*git reset fileName*
    * this will unstange the selected file

**once you add changes you need to commit**  
**changes with**  
*git commit -m "insert message here"*

**fianlly push to remote repo**  
*git push origin master*





# Github cheatsheet

This repo is dedicated to all my learning for git and github 

## To initialize the repo
git init  

## to add files in the repo
git add for all files (.)   

## to check status 
git status  

## to create a file in the dir
touch < filename.extension >  

## to create snapshot 
git commit -m "message"  

## to check update logs 
git log  

## to revert to commit 
git revert commit id  

## to check the available branch
git branch   
gren light denots the active branch  

## to create a new branch
git branch "branchname"  

## to change the branch
git checkout -b branchname  

## to delete the branch
git branch -d branchname  

## To merge the branch
git merge branchname  
(You should be in the destination branch to get files from source branch)   

## To delete the branch
git branch -d branchname  

## To add the remote repo
git remote add origin repourl  

## to push the code to the online repo 
git push -u origin branchname  

## to delete the remote branch 
git push origin -d branchname  

## to revert to the prev changes 
git reset --hard HEAD~step \  
git reset --hard <commitid>  

# Open source contribution

## to clone or download the remote repo into your local repo 
git clone <remoteurl>

## to fork the remote repo of other dev to your 
click on fork button on the right side of the repo 

## to add original author's repo 
git remote add upstream <original author's repo link>

## to get updates from author's repo to local repo
git pull upstream <branchname> 
if not added then it pulls all branches

## After pushing your local to the remote 
Create a pull request to the original repo author.
Clearly add the comment and details of have codes have you updated 



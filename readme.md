# To initialize the repo
git init

# to add files in the repo
git add for all files (.) 

# to check status 
git status 

#to create a file in the dir
touch <filename.extenstion>

# to create snapshot 
git commit -m "message"

# to check update logs 
git log 

# to revert to commit 
git revert commit id 

# to check the available branch
git branch 
gren light denots the active branch

# to create a new branch
git branch "branchname"

# to change the branch
git checkout -b branchname

# to delete the branch
git branch -d branchname

# To merge the branch
git merge branchname
(You should be in the destination branch to get files from source branch) 

# To delete the branch
git branch -d branchname

# To add the remote repo
git remote add origin repourl

# to push the code to the online repo 
git push -u origin branchname



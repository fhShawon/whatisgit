# whatisgit
learning about git and github

cloned this repo to local machine using 
added ssh keys

# Download git
https://git-scm.com
https://gitforwindows.org

# Configuring git
```bash
git config --global user.name "Your Name"
git config --global user.email "Your@Email" [same as github if you want to use that]
git config --global core.editor "NameOfYourFavouriteEditor"
```

```bash
git clone <repo-link>
ls -la #shows all the files including hidden ones
git status #to know what changes have been made
git add file_name #to update the files that will be committed
git add . #to add all files to be commited
git commit -m "message" -m "description" #message is must to commit
git commit -a -m "message"
git commit -am "message" #only works for modified file, not newly created files
git push #push to github
git push origin master #specify branch
git push -u origin master #specify default branch u=upstream
git pull #pull updated github repo to local machine

git init #initialize git in any local folder
git remote add origin github_link #add github repo to local folder
git remote -v #check connected github repo

git branch #check the branches
git checkout branch_name #switch to branch
git checkout -b branch_name #create new branch
git branch -m branch_name #rename branch
git merge
git diff #see differences between branches
git branch -d branch_name #delete branch, but only from local git, not from github as we are working inside a branch
git push origin -d branch_name #delete branch from github

git reset #undo changes which is done before committing
git reset HEAD~1 #undo changes after already commited
git log #show commit logs
git reset commit_hash_from_log #unstage changes, just the opoosite of add, the code is there in file but not in git
git reset --hard commit_hash_from_log #go back in time, the file changes as well as the git

#add ssh key to github profile
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add <private_key_file>


```

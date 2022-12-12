```bash
git clone <repo-link>
ls -la #shows all the files including hidden ones
git status #to know what changes have been made
git add file_name #to update the files that will be committed
git add . #to add all files to be commited
git commit -m "message" -m "description" #message is must to commit
git push #push to github
git push origin master #specify branch
git push -u origin master #specify default branch u=upstream

git init #initialize git in any local folder
git remote add origin github_link #add github repo to local folder
git remote -v #check connected github repo

git branch #check the branches
git checkout branch_name #move to branch
git checkout -b branch_name #create new branch

#add ssh key to github profile
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add <private_key_file>


```
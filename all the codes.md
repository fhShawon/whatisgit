```bash
git clone <repo-link>
ls -la #shows all the files including hidden ones
git status #to know what changes have been made
git add <file> #to update what will be committed
git add . #to add all files to be commited
git commit -m "message" -m "description" #message is must to commit
git push #push to github

#add ssh key to github profile
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add <private_key_file>




```
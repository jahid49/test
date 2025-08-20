Git & Github


git init

git status 
git add <filename>
git add *
git add .
git add --all
git commit -m "Commit message"

git commit
git push origin master
git remote add origin <server>


git config user.name "Jahid" 
git config user.email “jahidcse9b@gmail.com”

git log
git log --oneline
git checkout 9817783   
git checkout main

git branch branch_name
git branch
git checkout branch_name
git checkout -b newbranch
git merge branch_name
git branch -d branch_name
git push origin branch_name

#ssh key
ssh-keygen -t rsa -b 4096 -C "jahidcse9b@gmail.com"
eval "$(ssh-agent -s)"
open ~/.ssh/config
ssh-add ~/.ssh/id_rsa
ssh -T
Host github.com
  IgnoreUnknown UseKeychain



git push origin master
git push origin branch_name
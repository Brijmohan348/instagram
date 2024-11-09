or create a new repository on the command line
echo "# instagram" >> README.md

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Brijmohan348/instagram.git
git push -u origin main


remote wala problem
…or push an existing repository from the command line
git remote add origin git@github.com:Brijmohan348/instagram.git
solution
git branch -M main
git push -u origin main

error: remote origin already exists.
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Brijmohan348/first.git in terminal
 git remote
  git remote remove origin
  or 
  git remote set-url origin git@github.com:Brijmohan348/first.git

   error: No such remote 'origin is output start from   reate a new repository
'




problem of  git config or rc refspec main does not match an
Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'avhis@LAPTOP-7E56KF92.(none)')
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Brijmohan348/first.git'

solution
git config user.email "avhisekjaiswal29@gmail.com"
git config user.name "Brijmohan348"

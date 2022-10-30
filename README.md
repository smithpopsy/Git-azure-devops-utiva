# Git-azure-devops-utiva
utiva cloud developers Git lessons 
## Introduction on how to push from local environment to github 
Downloaded Gitbash (https://git-scm.com/downloads)
# configure gitbash 
git config --global user.name "name". 
  git config --global user.email "email"
# working with the configured environment 
mkdir website 
  cd website 
git init 
touch .index.html 
# clone your github repository 
git remote add origin Url (this should be the URl from your created repo and use HTTPS)
# push to Github 
git  add index.html
git commit -m "description"
git push origin master 

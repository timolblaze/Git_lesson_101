# Skill_schule_Git_lesson_101  
## Training to introduce the cohort on how to push from their local environment to Github  
- Downloaded Gitbash (https://git-scm.com/downloads)
## Configure Gitbash  
- git config --global.user.name "tblaze"
- git config --global.user.email "uchennamartins32@gmail.com"
## Prepare the configured environment  
- mkdir website
- cd website
- git init
- touch index.html  
## Clone your GitHub repository  
- git remote add origin <url> (this should be the url from your created repo-use https)
## Push to GitHub  
- git status (To check git status of your as regards to the staging area)
- git add index.html
- git commit -m "Create index.html"
- git push origin master
  





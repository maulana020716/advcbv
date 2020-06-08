first push to new repo :
git init
git add . 
git commit -m "first commit"
git remote add origin [url]
git push -u origin master

pushing changes to repo :
git add . 
git commit -m "changes"
git push origin master

if error, try cloning first :
git init
git clone [url]
(some changes) 
git add . 
git commit -m "changes"
git remote add origin [url]
git push origin master

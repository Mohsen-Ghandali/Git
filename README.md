# Git
Git

-npm install -g git
-npm install git
-npm install git --save




---------add user and email --------------
git config -g user.name "mohsen ghandali"
git config -g user.email "mohsen.2527.gh@gmail.com"





----Create Local Repositori----------------------
(in the file project)-->
-git -init



----Conect project from Github to VS-Code (RepositorieName and FolderName must be the same) ---------------------
1-Create a Repositori in Github an copy URL repositori
2-(in the file project)-->
git remote add origin https://((URL-Address Repositorie)).git
git branch -M main
git pull --rebase origin main
git push -u origin main




----Conect project from VS-Code to Github (FolderName and  RepositorieName must be the same)  ---------------------
1-Create a Repositori in Github an copy URL repositori
2-(in the file project)-->
git init
git add README.md
git remote add origin https://((URL-Address Repositorie)).git
git commit -m "first commit"
git branch -M main
git push -u origin main

or

1-Create a Repositori in Github an copy URL repositori
2-(in the file project)-->
git init
git remote add origin https://((URL-Address Repositorie)).git
git branch -M main
git add .
git commit -m "first commit"
git push --set-upstream origin create-search-box


----add to stage--------------
-git add index.html

or 

-git add .        (git add --all)
 




----remove from stage---------
-git restore --staged index.html

or

-git restore --staged .        (git restore --staged --all)





----back to last version-----
-git restore . 





----remove all file in changes and new file--------
-git clean -f





-------status-----------------
-git status   





---------commit-----------------
-git commit -m "write a massage about commit"





---------commit status------------
-git log






----------push of Github----------
-git push






---------download from Github--------
-git clone "Link URL"





----------------ignore---------------------
create a file in the root with ".gitignore" name
and write address ignore file.
for example: /db





----------download the latest changes(up to date)---------
-git pull





---------create branch-------------------
-git branch nameBranch main
for example: git create-header main





---------go to brach-----------------
-git switch nameBranch
for example: git switch create-header 

or

-git checkout nameBranch 
for example: git checkout create-header




---------create branch and go to branch-------------------
-git checkout -b nameBranch main
for example: git checkout -b create-header main





-----------show a branch status -------------
-git branch




--------To update from main Github-website to main local(coputer)-------
-git pull origin main




-------------for first time push branch in Github--------------
((First time))
-git push --set-upstream origin nameBranch
for example: git push --set-upstream origin create-header 

((Next time))
-git push





-------go to Githgub-Website and click the "Compare & pull request"--------





-------And then in the Github-Website select to "compare":nameBranch to "bas":main--------





-------Finally, click on the "Create pull request"---------




------After pulling one main,write -git pull in CMD--------
-git pull



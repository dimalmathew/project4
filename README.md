# project4




































































mkdir g
git --version
git config --list
git config --global user.name "Dimal"
git config --global user.email "Dimal"
ls -la

git add .
git status
git reset 1.txt
git commit -m "1.txt created"
git log --oneline
git log --author "Dimal"
git rev-parse --verify HEAD
git diff
git rm 2.txt
git mv 1.txt 11.txt
git commit --amend    - To edit the recent commit


git branch
git branch feature1
git checkout feature1
git diff master feature2
git branch -m feature2 feature22
git branch -d feature1
git merge feature22
git reset HEAD~
git reveret abs567ddnghgjkkd243

git remote -v
git remote add origin https://github.com/dimalmathew/p1.git
git remote remove origin
git push -u origin master --allow-unrelated-histories
git pull origin feature1

git stash save "2.txt updated but not saved"
git stash list
git stash show stash@{0}
git stash show -p stash@{0}
git stash pop stash@{0}
git stash apply
git stash drop stash@{0}
git stash clear

# git-assignment3

Below Commands are user for this assignments.

git pull origin main --allow-unrelated-histories
touch main.txt
git status
git add .
git commit -m "added main.txt files"
git status
git push origin main
git branch -a
git checkout Develop
touch develop.txt
git add .
git commit -m "added develop.txt file"
git push
git checkout F1
touch f1.txt
git add .
git commit -m "added f1.txt file"
git push
git checkout f2
touch f2.txt
git add .
git commit -m "added f2.txt file"
git push
git checkout main
git branch -d f2
git branch -a
git push origin --delete f2

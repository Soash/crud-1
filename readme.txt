git config --global user.name soash
git config --global user.email soash2002@gmail.com

git init
git commit -m "commit"

ps
cd
cd folder_name
cd ..
ls -a
ls -lart
mkdir folder_name
rmdir folder_name
touch file_name.txt
touch folder/file.txt
clear

git status
git add index.html
git add folder_name/file_name.txt
git add -A >> to stage all
git add . >> to stage all in a current folder
git reset
git reset --hard
git rm --cached <file>...  >> to unstage
git restore --staged <file>... >> to unstage


git checkout file_name.txt >> restore txt
git checkout -f >> restore file

git log
git log -p -1 >> see last edit
git diff
git diff --staged

git rm file_name.txt -f

touch .gitignore
git branch
git branch branch_name >> create new branch
git switch branch_name

git merge branch_name -m "comment"

vim >> i Initial commit enter.key esc.key :wq enter.key
q to exit

https://www.youtube.com/watch?v=6DczjqG9HbA
https://youtu.be/M-qSAdWFs9c
git config --global user.name "Yuan Becera"
git config --global user.email "295711086+yuanjaerhobecera-beep@users.noreply.github.com"

git init

git add index.html
git commit -m "Create initial HTML webpage"

git branch no-style
git switch -c main

git add .
git commit -m "Add CSS styling and JavaScript functionality"

git remote add origin https://github.com/yuanjaerhobecera-beep/Yuan-Jaerho-C.-Becera-DCIT-26.git

git remote -v

git push -u origin main --force

git switch no-style

git commit --amend --reset-author --no-edit

git push -u origin no-style --force

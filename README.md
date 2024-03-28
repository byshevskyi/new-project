first text

git init new-project
cd new-project
git config --global user.name "name"
git config --global user.email "email@email.com"
git config --global init.defaultBranch "main"
create file README.md
git add README.md
git commit -m "first commit"
git branch development
git switch development
vim README.md
git commit README.md -m "second commit"
git merge development

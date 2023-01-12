echo "# livepreview" >> README.md
git init
git add README.md
mkdir docs
touch docs/.gitignore
git add docs/.gitignore
git commit -m "first commit"
git remote add origin https://github.com/NafMn/livepreview.git
git push -u origin master

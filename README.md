echo "# tailwind-docs-example" >> README.md
git init
git add README.md
mkdir docs
touch docs/.gitignore
git add docs/.gitignore
git commit -m "first commit"
git remote add origin git@github.com:frankdejonge/tailwind-docs-example.git
git push -u origin master

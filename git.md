# git

echo "# temp" >> README.md
git init
git add README.md
git commit -m "repo init"
<!-- git branch -M main -->
git remote add origin https://github.com/MintArchit/[[repo-name]].git
git push -u origin main

# gh

gh repo create wiki --public --source=. --remote=upstream

# git

echo "# temp" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MintArchit/temp.git
git push -u origin main

# gh

 gh repo create wiki --public --source=. --remote=upstream

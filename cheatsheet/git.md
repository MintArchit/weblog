__git__

# most used alias

ga              git add
gapa            git add -p
gc              git commit -v
gc -m "..."     git commit -v -m "..."
gp              git push
gd              git diff
gds             git diff --staged
grh             git reset

## combo
psh             git add . && git commit -m "$0"

# init repo
echo "# temp" >> README.md
git init
git add README.md
git commit -m "repo init"
<!-- git branch -M main -->
git remote add origin https://github.com/MintArchit/[[repo-name]].git
git push -u origin main

# cmds
add -p			stage code changes per line
commit -m ""	commit staged changes
push			upload local changes
diff			show all unstaged changes
diff --staged	show all staged changes

__gh__

gh repo create wiki --public --source=. --remote=upstream

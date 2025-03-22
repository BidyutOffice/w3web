# GIT & GITHUB

<!-- git bash after ins git (one time) -->
git config --global user.name "your name"
git config --global user.email "your email"

<!-- stages -->
untracked -> add -> (modify -> add) ->  commit
commit -> modify -> add -> commit

<!-- git init -->
git init
git add file.name/  . for all files
git commit -m "message"

<!-- if changes -->
git add file.name/  . for all files
git commit -m "message"

<!-- local to remote (all files should be commited) -->
git branch -M main
git remote add origin "git uri"
git push -u origin main

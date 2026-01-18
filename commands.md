Basic cammands in git
```bash
git init
git clone <repo-url>

git status
git log
git log --oneline
git diff
git diff --staged

git add file.txt
git add .
git commit -m "commit message"

git branch
git branch new-branch
git checkout branch-name
git switch branch-name
git switch -c new-branch
git branch -m new-name
git branch -m old-name new-name
git branch -d branch-name
git branch -D branch-name
git push origin --delete branch-name

git merge branch-name
git rebase main

git remote -v
git remote add origin <repo-url>
git remote set-url origin <new-url>
git remote remove origin

git push origin main
git pull origin main
git fetch

git reset file.txt
git revert commit-id
git stash
git stash pop

git cherry-pick commit-id

git rm file.txt
git mv old.txt new.txt

HEAD
.gitignore

git help
git help commit
```

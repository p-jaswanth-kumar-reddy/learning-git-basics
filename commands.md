## Git Commands (Learned & Practiced)

### Repository Setup
git init
git clone <repo-url>

### Check Status & History
git status
git log
git log --oneline
git diff
git diff --staged

### Add & Commit Changes
git add file.txt
git add .
git commit -m "commit message"

### Branch Management
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

### Merging & Rebasing
git merge branch-name
git rebase main

### Merge Conflict Resolution
git status
git add file.txt
git commit -m "Resolved merge conflict"

### Remote Repository (GitHub)
git remote -v
git remote add origin <repo-url>
git remote set-url origin <new-url>
git remote remove origin

### Push, Pull & Fetch
git push origin main
git pull origin main
git fetch

### Undo Commands
git reset file.txt
git revert commit-id
git stash
git stash pop

### Selective Commit
git cherry-pick commit-id

### File Operations
git rm file.txt
git mv old.txt new.txt

### Important Concepts
.gitignore

### Help
git help
git help commit

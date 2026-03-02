🔹 1. Repository Setup
git init → Initialize a new repository
git clone <repo_url> → Clone a remote repository

🔹 2. Basic Workflow (Daily Use)
git status → Check working directory status
git add <file> → Stage specific file
git add . → Stage all changes
git commit -m "message" → Commit staged changes
git commit -am "message" → Add & commit (tracked files only)
git log → Show commit history
git log --oneline --graph --all → Compact visual history
git diff → Show unstaged changes
git diff --staged → Show staged changes

🔹 3. Branching (VERY IMPORTANT)
git branch → List branches
git branch <branch_name> → Create new branch
git checkout <branch_name> → Switch branch
git checkout -b <branch_name> → Create & switch
git switch <branch_name> → Modern way to switch
git switch -c <branch_name> → Create & switch (modern)
git merge <branch_name> → Merge branch into current branch
git rebase <branch_name> → Reapply commits on top of another branch

🔹 4. Remote Repository (DevOps Must-Know)
git remote -v → Show remote URLs
git remote add origin <repo_url> → Add remote
git fetch → Download changes (no merge)
git pull → Fetch + merge
git push → Push to remote
git push -u origin <branch> → Push & set upstream
git push --force → Force push (⚠ use carefully)

🔹 5. Undo / Fix Mistakes
git restore <file> → Discard unstaged changes
git restore --staged <file> → Unstage file
git reset --soft <commit> → Move HEAD (keep staged changes)
git reset --mixed <commit> → Keep working directory
git reset --hard <commit> → Delete everything after commit ⚠
git revert <commit> → Create new commit to undo
git stash → Temporarily save changes
git stash pop → Reapply stashed changes

🔹 6. Inspection & Debugging
git show <commit> → Show commit details
git blame <file> → See who changed each line
git reflog → Show reference history (life saver 🔥)

🔹 7. Tags (For Releases)
git tag → List tags
git tag <tag_name> → Create tag
git push origin <tag_name> → Push t

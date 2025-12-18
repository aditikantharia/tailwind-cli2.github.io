git command:

Setup & Config
• git --version → Check Git version
• git config --global user.name "Name" → Set username
• git config --global user.email "email" → Set email
• git config --list → View configuration

Repository
• git init → Initialize repository
• git clone → Clone repository

Basic Workflow
• git status → Check status
• git add . → Stage all files
• git commit -m "msg" → Commit changes
• git push origin main → Push to GitHub

Branching
• git branch → List branches
• git checkout -b branch → Create & switch branch
• git merge branch → Merge branch
• git branch -d branch → Delete branch

Undo & Fix
• git reset file → Unstage file
• git checkout -- file → Discard changes
• git revert commit-id → Safe undo

Stash
• git stash → Save work temporarily
• git stash pop → Restore stash
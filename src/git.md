# Git Commands
  
git clone https://github.com/kdua13/git_commands.git

# Commit a change
git add .
git commit - m "message text"
git push

# Reset to a previous commit id
git reset --hard <commit id>
git push --force

# Configure profile credentials
git config --global credential.helper store

# Push local git repo to new created git repo, run on local git folder
git init
git add .
git commit -m "Initial commit"

## 1. Rename your default branch to 'main' (matches GitHub's default)
git branch -M main

## 2. Add the remote GitHub URL (paste the link you copied)
git remote add origin <PASTE_YOUR_GITHUB_URL>

## 3. Push your repository to GitHub
git push -u origin main

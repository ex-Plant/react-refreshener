1. HOW TO CHANGE LAST COMMIT MESSAGE
- git commit --amend -m "new message"

2. HOW TO STOP TRACKING FILES

- add file to git ignore
- git rm --cached 'filename'



Method 1: Starting in Terminal

Create project directory

mkdir my-new-project
cd my-new-project

Initialize Git

git init

Create initial files

echo "# My Project" > README.md

Stage and commit

git add .
git commit -m "Initial commit"

Create GitHub repository


Go to GitHub → + → New repository
Name it, don't initialize with README/gitignore
Copy provided remote add command


Link local repo to GitHub

git remote add origin https://github.com/yourusername/my-new-project.git
git branch -M main
git push -u origin main
Method 2: Starting on GitHub

GitHub → + → New repository


Name project
Choose public/private
Optionally add README, .gitignore, license


Clone to local machine

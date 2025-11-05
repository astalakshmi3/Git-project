 # Git-project

 This is my first Git and GitHub project.

 # Description

 In this project, I wrote down the Git commands I used to create and modify files step by step.


# Task 1

Initialize and Connect a Repository

# 1. Initialize a new local repository

git init

Creates a new Git repository in my project folder.

# 2. Create files and make the first commit

echo # Workshop 1 > README.md
echo Some notes > notes.txt
git add README.md notes.txt
git commit -m "Initial commit: add README and notes"

Adds the files to staging and saves the first commit.

# 3. Connect to GitHub and push

git branch -M main
git remote add origin https://github.com/astalakshmi3/workshop1.git
git push -u origin main

Links my local repo to my GitHub repository and uploads it.

# 4. Track the file

echo "Added project goals" >> README.md
git add README.md
git commit -m "Docs: update README with project goals"
git push

Practiced making meaningful commits and pushing changes.

# 5. Create a .gitignore

echo node_modules/ > .gitignore
echo .env >> .gitignore
git add .gitignore
git commit -m "Chore: add .gitignore"
git push

Ensures unnecessary files are ignored by Git."# Git-project" 

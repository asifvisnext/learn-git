# Clone a GitHub repository
git clone <repository-url>

# Pull the latest changes from the remote main branch
git pull origin main

# Check the status of the working directory and staging area
git status

# View the changes made (difference between working directory and last commit)
git diff

# Add files to the staging area
git add <filename>            # To add a specific file
git add .                     # To add all changes

# Commit the staged changes with a message
git commit -m "Your commit message"

# Push local commits to the remote main branch
git push origin main

# Switch to another branch
git checkout <branch-name>

# Create a new branch
git branch feature/login

# OR create and switch to a new branch at the same time
git checkout -b feature/login

# Merge another branch into the current branch
git merge <branch-name>

# View commit history (who did what and when)
git log

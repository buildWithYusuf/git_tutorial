
# Git Cheatsheet

## 📌 Version Control Overview
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a developer and want to keep every version of your code/project (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use.

---

## ✨ Git Commands

### Set global username and email
```bash
git config --global user.name "<your username>"
git config --global user.email "<your email>"
```

### Initialize a Git repository
```bash
git init
```

### Clone a Git repository
```bash
git clone <repository URL>
```

### Stage files for commit
```bash
git add <filename>
# OR add all files
git add .
```

### Commit changes
```bash
git commit -m "<your commit message>"
```

### Restore or discard file changes
```bash
git restore <filename>
# OR
git checkout <filename>
```

### Check repository status
```bash
git status
```

### Branch management
```bash
# List branches
git branch

# Create and switch to a new branch
git checkout -b <branch name>

# Switch to an existing branch
git checkout <branch name>

# Delete a branch
git branch -d <branch name>
```

### Remote repository management
```bash
# Show remote URL
git remote -v

# Add a remote origin
git remote add origin <your remote git URL>

# Remove a remote origin
git remote remove origin
```

### Sync with remote repository
```bash
# Fetch remote branches
git fetch

# Push local changes to remote
git push origin <branch name>

# Pull changes from remote
git pull origin <branch name>
```

### View commit history
```bash
git log
```

---

## ✅ Push Git Cheatsheet to GitHub

### Prerequisites
- Git installed
- GitHub account
- A GitHub repository (e.g., `git-cheatsheet`)

### Steps

```bash
# Create project folder and move into it
mkdir git-cheatsheet
cd git-cheatsheet

# Move the PDF file to this folder
mv /path/to/Git_Cheatsheet.pdf ./Git_Cheatsheet.pdf

# Optional: Create README.md
echo "# Git Cheatsheet
A quick reference for Git commands and best practices." > README.md

# Initialize Git
git init

# Stage and commit files
git add .
git commit -m "Add Git Cheatsheet PDF"

# Add remote origin
git remote add origin https://github.com/your-username/git-cheatsheet.git

# Push to GitHub
git push -u origin master
```

---

## 📁 Expected Repo Structure

```
git-cheatsheet/
├── Git_Cheatsheet.pdf
└── README.md
```

---

Happy Coding! 🚀

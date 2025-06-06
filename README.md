# 🚀 Git & GitHub Command Guide

## 🔧 Git vs GitHub
- **Git** – A version control system to track code changes.
- **GitHub** – A hosting service for Git repositories (cloud-based).

---

## 🛠️ Setup Git (One-time)
```bash
git config --global user.name "Mahendra Yadav"
git config --global user.email "mahendrayadav37104@gmail.com"
git config --list       # Verify config
```

---

## 📥 Clone Repository
```bash
git clone <repo-url>     # Clone repo from GitHub
cd <folder-name>         # Enter project folder
git status               # View status of working directory
clear                    # Clear terminal
cd ..                    # Go back
ls                       # List files
ls -a                    # List all files (including hidden)
```

---

## ➕ Add & Commit Changes
```bash
git add <file>           # Stage specific file
git add .                # Stage all changes
git commit -m "message"  # Commit changes with message
```

---

## 📤 Push to GitHub
```bash
git push origin main     # Push to main branch on GitHub
```

---

## 📦 Push Local Project to GitHub (First Time)
1. Create GitHub repo (without README).
2. Run:
```bash
cd your/project/path
mkdir <folder-name>
cd <folder-name>
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repo-url>
git remote -v             # Verify remote
git push -u origin main
```

---

## 🌿 Branch Commands
```bash
git branch                # List branches
git branch -m <new-name>  # Rename current branch
git checkout <branch>     # Switch to branch
git checkout -b <name>    # Create & switch to new branch
git branch -d <branch>    # Delete branch
```

---

## 🔀 Merging Branches

### Option 1: Git CLI
```bash
git diff <branch>         # Show differences
git merge <branch>        # Merge into current branch
```

### Option 2: GitHub Pull Request
1. Push branch to GitHub.
2. Click **"Compare & Pull Request"**.
3. Review → Merge.

---

✅ You’re now ready to use Git & GitHub like a pro!

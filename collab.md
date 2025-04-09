## Git Collaboration Guide

### ✅ Initial Setup
```bash
git clone https://github.com/your-repo-url/project-folder.git
cd project-folder
```

### 🔄 Working on Your Branch
```bash
git checkout -b your-feature-branch
```

### ✅ Committing Changes
```bash
git add .
git commit -m "Your message"
git push origin your-feature-branch
```

### 🔃 Pull Request & Merge
1. Open a pull request on GitHub.
2. Request review from teammates.
3. After approval, merge to main or dev.

### 🔁 Sync With Main
```bash
git checkout main
git pull origin main
git checkout your-feature-branch
git merge main
```

### ❗ Handling Conflicts
Resolve and then:
```bash
git add .
git commit -m "Resolved conflict"
```

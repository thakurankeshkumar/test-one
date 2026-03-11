# Test-One Repository

This repository is for testing Git commands and practices.

## Basic Git Commands

### Initialize a Repository
```bash
git init
```

### Clone a Repository
```bash
git clone <repository-url>
```

### Check Status
```bash
git status
```

### Add Files to Staging
```bash
git add <file-name>
# or add all files
git add .
```

### Commit Changes
```bash
git commit -m "Your commit message"
```

### Push to Remote
```bash
git push origin <branch-name>
```

### Pull from Remote
```bash
git pull origin <branch-name>
```

### Create a Branch
```bash
git branch <branch-name>
```

### Switch to a Branch
```bash
git checkout <branch-name>
# or create and switch
git checkout -b <branch-name>
```

### Merge Branches
```bash
git merge <branch-name>
```

### View Commit History
```bash
git log
# or one line
git log --oneline
```

### Undo Changes
```bash
# unstage a file
git reset <file-name>
# discard changes in working directory
git checkout -- <file-name>
# undo last commit (keeping changes)
git reset --soft HEAD~1
```

## Advanced Commands

### Rebase
```bash
git rebase <branch-name>
```

### Stash Changes
```bash
git stash
git stash pop
```

### Remote Management
```bash
git remote -v
git remote add origin <url>
```

This README provides a quick reference for common Git commands and in future we can update this file so that it may help you.

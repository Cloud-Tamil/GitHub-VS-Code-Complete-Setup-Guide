# 🚀 GitHub + VS Code Complete Setup Guide

This repository contains a complete beginner-to-advanced guide for connecting a local project with GitHub using Visual Studio Code and Git.

---

# 📌 Prerequisites

Before starting, install the following software:

## 1. Install Visual Studio Code

Download:
https://code.visualstudio.com/

---

## 2. Install Git

Download:
https://git-scm.com/

Verify installation:

```bash
git --version
```

---

# 📂 Project Structure

Example project structure:

```text
project/
│
├── app/
├── docker/
├── kubernetes/
├── terraform/
├── scripts/
├── README.md
└── .gitignore
```

---

# 🔧 Configure Git

Set your Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Check configuration:

```bash
git config --list
```

---

# 🔗 Connect GitHub with VS Code

## Step 1: Open VS Code

Open your project folder.

---

## Step 2: Sign in to GitHub

Inside VS Code:

* Click Accounts icon
* Click "Sign in with GitHub"

Authorize GitHub access in browser.

---

# 📥 Clone GitHub Repository to Local

## Method 1: Using VS Code

### Step 1

Copy GitHub repository URL:

```bash
https://github.com/username/project-name.git
```

---

### Step 2

Open VS Code

Press:

```text
Ctrl + Shift + P
```

Search:

```text
Git: Clone
```

Paste repository URL.

Choose folder location.

Click:

```text
Open Repository
```

---

# 📤 Push Local Project to GitHub

---

## Step 1: Open Project Folder

Open terminal inside VS Code:

```text
Ctrl + `
```

---

## Step 2: Initialize Git

```bash
git init
```

---

## Step 3: Add Files

```bash
git add .
```

---

## Step 4: Commit Files

```bash
git commit -m "Initial commit"
```

---

# 🌐 Create GitHub Repository

Go to:

https://github.com/new

Create repository.

DO NOT initialize README file.

---

# 🔗 Connect Local Project to GitHub Repository

Copy repository URL:

```bash
https://github.com/username/project-name.git
```

Add remote origin:

```bash
git remote add origin https://github.com/username/project-name.git
```

Verify remote:

```bash
git remote -v
```

---

# 🚀 Push Code to GitHub

Rename branch:

```bash
git branch -M main
```

Push code:

```bash
git push -u origin main
```

---

# 🔄 Pull Latest Code from GitHub

```bash
git pull origin main
```

---

# 📌 Daily Git Workflow

## Check Status

```bash
git status
```

---

## Add Changes

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "Updated project"
```

---

## Push Changes

```bash
git push origin main
```

---

# 🔥 Common Git Errors & Solutions

---

## Error:

```bash
fatal: not a git repository
```

### Solution:

```bash
git init
```

---

## Error:

```bash
remote origin already exists
```

### Solution:

Remove old remote:

```bash
git remote remove origin
```

Add again:

```bash
git remote add origin REPO_URL
```

---

## Error:

```bash
Authentication failed
```

### Solution:

* Login GitHub in VS Code
* Use Personal Access Token (PAT)

---

# 🔐 GitHub Authentication

GitHub no longer supports password authentication.

Use:

* GitHub Sign-In via VS Code
  OR
* Personal Access Token (PAT)

Generate PAT:
https://github.com/settings/tokens

---

# 📄 Create .gitignore File

Create `.gitignore` file:

```gitignore
node_modules/
.env
*.log
terraform.tfstate
.terraform/
__pycache__/
```

This prevents unnecessary files from uploading.

---

# 🛠 Recommended VS Code Extensions

Install these extensions:

* GitHub Pull Requests & Issues
* GitLens
* Docker
* YAML
* Kubernetes

---

# 📚 Useful Git Commands

## Check remote repository

```bash
git remote -v
```

---

## Check branches

```bash
git branch
```

---

## Create new branch

```bash
git checkout -b dev
```

---

## Switch branch

```bash
git checkout main
```

---

## Delete branch

```bash
git branch -d branch-name
```

---

# ☁️ Recommended Learning Path

1. Git
2. GitHub
3. Linux
4. Docker
5. Kubernetes
6. Terraform
7. CI/CD
8. Google Cloud / AWS
9. Monitoring

---

# 📘 Official Documentation

## Git

https://git-scm.com/doc

---

## GitHub Docs

https://docs.github.com/

---

## VS Code Git Integration

https://code.visualstudio.com/docs/sourcecontrol/overview

---

# ✅ Author

Created for DevOps & Cloud Learning 🚀

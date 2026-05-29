# 🚀 My-First-Project

This repository contains the complete setup process for connecting a local project to GitHub using Git and Visual Studio Code.

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

Verify Git installation:

```bash
git --version
```

---

# 📂 Project Setup

Create a project folder:

```text
My-First-Project/
│
├── README.md
├── app/
├── scripts/
├── docker/
├── kubernetes/
└── terraform/
```

---

# 🔧 Configure Git

Set your Git username and email:

```bash
git config --global user.name "Cloud-Tamil"
git config --global user.email "your-email@gmail.com"
```

Verify configuration:

```bash
git config --list
```

---

# 🚀 Initialize Git Repository

Open terminal inside Visual Studio Code.

Run:

```bash
git init
```

---

# 📄 Create README File

Create README.md file:

```bash
echo "# My-First-Project" >> README.md
```

---

# 📥 Add Files to Git

```bash
git add README.md
```

OR add all files:

```bash
git add .
```

---

# ✅ Commit Files

```bash
git commit -m "first commit"
```

---

# 🌐 Create GitHub Repository

Go to:

https://github.com/new

Repository Name:

```text
My-First-Project
```

⚠️ Important:

Do NOT initialize:

* README
* .gitignore
* License

Click:

```text
Create Repository
```

---

# 🔗 Connect Local Repository to GitHub

Add remote origin:

```bash
git remote add origin https://github.com/Cloud-Tamil/My-First-Project.git
```

Verify remote:

```bash
git remote -v
```

---

# 🌿 Rename Branch to Main

```bash
git branch -M main
```

---

# 🚀 Push Code to GitHub

```bash
git push -u origin main
```

---

# 🔐 GitHub Authentication

GitHub no longer supports password authentication.

Use:

* GitHub Sign-In
  OR
* Personal Access Token (PAT)

Generate PAT:

https://github.com/settings/tokens

---

# 🔄 Daily Git Workflow

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
git commit -m "updated project"
```

---

## Push Changes

```bash
git push origin main
```

---

# 📌 Useful Git Commands

## Check Remote Repository

```bash
git remote -v
```

---

## Check Branches

```bash
git branch
```

---

## Create New Branch

```bash
git checkout -b dev
```

---

## Switch Branch

```bash
git checkout main
```

---

## Pull Latest Changes

```bash
git pull origin main
```

---

# 🔥 Common Git Errors & Solutions

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
git remote add origin https://github.com/Cloud-Tamil/My-First-Project.git
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

# 📄 Recommended .gitignore

Create `.gitignore` file:

```gitignore
node_modules/
.env
*.log
terraform.tfstate
.terraform/
__pycache__/
```

---

# 🛠 Recommended VS Code Extensions

* GitHub Pull Requests & Issues
* GitLens
* Docker
* YAML
* Kubernetes
* Terraform

---

# ☁️ Recommended Learning Path

1. Git
2. GitHub
3. Linux
4. Docker
5. Kubernetes
6. Terraform
7. CI/CD
8. AWS / Google Cloud
9. Monitoring

---

# 📚 Official Documentation

## Git Documentation

https://git-scm.com/doc

---

## GitHub Documentation

https://docs.github.com/

---

## VS Code Git Integration

https://code.visualstudio.com/docs/sourcecontrol/overview

---

# ✅ Repository URL

https://github.com/Cloud-Tamil/My-First-Project

---

# 👨‍💻 Author

Created by Cloud-Tamil 🚀

# 🚀 DevOps Version-Controlled Project using Git & GitHub

![Git](https://img.shields.io/badge/Git-VersionControl-blue?logo=git)
![GitHub](https://img.shields.io/badge/Hosted_on-GitHub-black?logo=github)
![PRs](https://img.shields.io/badge/Pull_Requests-Used-brightgreen?logo=githubactions)
![Tag](https://img.shields.io/badge/Version-v1.0-orange?logo=semver)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Objective

This project demonstrates how to manage a **DevOps folder structure** using **Git best practices** in a real-world style.  
Everything from repo initialization to tagging has been done professionally using feature and dev branches, pull requests, and proper commits.

---

## 🗂️ Folder Structure

```
devops-practice-lab/
├── ansible/
├── docker/
├── jenkins/
├── kubernetes/
├── terraform/
├── .gitignore
└── README.md
```

---

> 📌 **Note:** Folders and files are intentionally left empty.  
> This task's primary focus was on **setting up a version-controlled DevOps structure** using Git — not on adding tool-specific configs yet.

---

## 🧠 Git Workflow Followed

Below are the steps followed with screenshots included to show each milestone clearly.

---

### 📍 1. Initialize Repository & First Push to GitHub

- `git init`
- `git add .`
- `git remote add origin <your_repo_url>`
- `git commit -m "Initial commit"`
- `git branch -M main`
- `git push -u origin main`

📸 **Screenshot:**
> ![Step 1 - Git Init & Push](<Screenshot 2025-04-11 141624-1.png>)

---


### 📍 2. Created `dev` Branch & Pushed to GitHub

- `git checkout -b dev`           
- `git push -u origin dev`

📸 **Screenshot:**
> ![Step 2 - Dev Branch](<Screenshot 2025-04-11 141757-1.png>)

---

### 📍 3. Created `feature/init-structure` Branch

- `git checkout -b feature/init-structure`
- `git push -u origin feature/init-structure`

📸 **Screenshot:**
> ![Step 3 - Feature Branch](<Screenshot 2025-04-11 141947-1.png>)

---

### 📍 4. Added `.gitignore` and `README.md` from `feature/init-structure`

- `touch .gitignore README.md`
- Updated content
- `git add .`
- `git commit -m "Added base README and .gitignore"`
- `git push`

📸 **Screenshot:**
> ![Step 4 - Files Added](<Screenshot 2025-04-11 142326-1.png>)

---

### 📍 5. Created Pull Request: `feature/init-structure` → `dev`

📸 **Screenshots:**
> ![Step 5 - PR to Dev](<Screenshot 2025-04-11 143638-2.png>)
> ![Step 5 - Review the PR](<Screenshot 2025-04-11 143708-1.png>) 
> ![Step 5 - Merge](<Screenshot 2025-04-11 143744-1.png>)

---

### 📍 6. Merged `dev` to `main` via Pull Request

📸 **Screenshots:**
> ![Step 6 - PR to Main](<Screenshot 2025-04-11 143952-1.png>)
> ![Step 6 - Review](<Screenshot 2025-04-11 144037-1.png>) 
> ![Step 6 - Merge](<Screenshot 2025-04-11 144051-1.png>)

---

### 📍 7. Added Tag `v1.0` from `main` Branch

- `git tag v1.0 -m "Initial version"`
- `git push origin v1.0`

📸 **Screenshots:**
> ![Step 7 - Tag v1.0](<Screenshot 2025-04-11 144436-1.png>)  
> ![Step 7 - Check v1.0](<Screenshot 2025-04-11 144509-1.png>)

---

### 📍 8. Final View

📸 **Screenshot:**
> ![Final Repo View](<Screenshot 2025-04-11 144552-2.png>)

---

## ✅ Summary

This project taught me how to:
- Use feature branching model
- Work with pull requests for safe code merging
- Maintain clean Git history
- Add proper documentation and versioning

---

> 💬 _"Well-structured Git practice is the first step to becoming a DevOps pro."_

## 🌟 Key Takeaways

This project provided hands-on experience with essential Git and GitHub workflows, emphasizing professional practices in version control. Here's what was achieved:

### 🔑 Skills Gained
- **Feature Branching Model:** Organized development with isolated feature branches.
- **Pull Requests:** Ensured safe and collaborative code integration.
- **Versioning:** Tagged releases for clear version tracking.
- **Documentation:** Maintained a clean and informative README for project clarity.

### 🚀 Why It Matters
Mastering Git workflows is foundational for any DevOps professional. This project simulated real-world scenarios, preparing for collaborative and scalable development environments.

---

> 💡 _"Version control is not just a tool—it's a discipline that ensures the integrity and scalability of your projects."_


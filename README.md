# Git Workflow & Test Case Design Assignment

This repository contains the practical implementation of **Question 1: Git & GitHub Workflow** for the Software Engineering / DevOps Assignment.

**Repository URL:** [https://github.com/inland-taipen/git-workflow-assignment](https://github.com/inland-taipen/git-workflow-assignment)  
**Author:** Anika Tripathi  
**Roll No:** 2024eb02496  

---

## 1. Project Overview & Workflow Demonstrated
1. **Local Repository Setup**:
   - Initialized Git locally (`git init -b main`) without creating the remote first.
   - Created core project files: `index.html` and `about.html`.
2. **Git Workflow & Branching**:
   - Initial commit on `main`.
   - Updated `index.html` and recorded a second commit.
   - Created and checked out a new feature branch: `feature`.
   - Implemented team section changes in `about.html` and committed to `feature`.
   - Switched back to `main` and merged `feature` with an explicit merge commit (`--no-ff`).
3. **Ignore Patterns (.gitignore)**:
   - Configured `.gitignore` to exclude `*.log` files and temporary folders (`temp/`).
   - Verified ignore behavior using `git status --ignored`.
4. **Undo Operations**:
   - Demonstrated commit rollback using `git reset HEAD~1`, preserving working tree modifications while removing the unneeded snapshot.
5. **GitHub Integration**:
   - Linked local repository to this public GitHub remote and pushed all branches (`main`, `feature`).
6. **Command Documentation**:
   - Documented all commands with line-by-line explanations in `git_commands.txt`.

---

## 2. Repository Contents
- `index.html` - Homepage structure with hero and footer sections.
- `about.html` - Team showcase merged from the `feature` branch.
- `.gitignore` - Ignore rules for logs and temporary build artifacts.
- `git_commands.txt` - Exhaustive command reference with explanations.

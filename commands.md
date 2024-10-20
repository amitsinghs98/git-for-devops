# Git Commands Cheat Sheet

## 1. Initialize Git Repository
```bash
git init
```
Initializes a new Git repository in the current directory.

---

## 2. Creating Files
```bash
touch nibbi.txt nibba.txt
```
Creates new files named `nibbi.txt` and `nibba.txt`.

---

## 3. Add Files to Staging Area
```bash
git add .
```
Adds all new and modified files to the staging area.

---

## 4. Commit Changes
```bash
git commit -m "your message"
```
Commits changes in the staging area to the repository with a commit message.

---

## 5. Check Status of the Repository
```bash
git status
```
Shows the current status of files in the working directory and staging area.

---

## 6. Remove a File
```bash
rm nibbi.txt
```
Deletes a file named `nibbi.txt`.

---

## 7. Restore a File
```bash
git restore nibbi.txt
```
Restores a file from the previous commit.

---

## 8. View Commit History
```bash
git log
```
Displays the commit history for the repository.

---

## 9. Create a New Branch
```bash
git checkout -b "branch-name"
```
Creates and switches to a new branch.

---

## 10. Switch Between Branches
```bash
git checkout master
```
Switches to the `master` branch.

---

## 11. Configure Git User Information
```bash
git config --global user.name "yourusername"
git config --global user.email "youremail@example.com"
```
Sets global Git configuration for username and email.

---

## 12. View Current Branches
```bash
git branch
```
Lists all branches in the repository.

---

## 13. Add Files to Specific Branch
```bash
git add devfile.txt
git commit -m "add dev"
```
Adds and commits a specific file to the branch.

---

## 14. Clear Terminal
```bash
clear
```
Clears the terminal screen.

---

## 15. Checkout to an Existing Branch
```bash
git checkout dev
```
Switches to the `dev` branch.

---

## 16. Remove a Branch
```bash
git branch -d branch-name
```
Deletes a specific branch from the repository.
```

# Most Used Git Commands

## 1. Initialize a New Git Repository
`git init`  
Initializes a new Git repository in the current directory. This command sets up the `.git` directory to start tracking changes.

## 2. Check the Status of Your Repository
`git status`  
Displays the state of the working directory and the staging area. It shows which files are staged, which files are not staged, and which files aren’t being tracked by Git.

## 3. Add Files to Staging Area
`git add <file-name>`  
Adds the specified file to the staging area, preparing it to be committed. If you want to add all files at once, you can use `git add .`.

## 4. Commit Changes
`git commit -m "commit message"`  
Records a snapshot of the project in the repository. The `-m` flag allows you to add a commit message directly in the command line.

## 5. View Commit History
`git log`  
Shows the commit history in reverse chronological order. You can view each commit’s hash, author, date, and commit message.

## 6. Create a New Branch
`git checkout -b <branch-name>`  
Creates a new branch and switches to it. This is useful when you want to work on a feature separately from the main branch.

## 7. Switch Between Branches
`git checkout <branch-name>`  
Switches to the specified branch in your repository. This command is essential for managing multiple branches in a project.

## 8. Merge Branches
`git merge <branch-name>`  
Combines changes from the specified branch into the current branch. You would use this command after finishing a feature in a separate branch and want to integrate it back into the main branch.

## 9. Clone a Repository
`git clone <repository-url>`  
Copies a remote Git repository onto your local machine. This is used when you want to start working on a project that already exists on a remote platform like GitHub.

## 10. Push Changes to Remote Repository
`git push origin <branch-name>`  
Uploads your local commits to the remote repository. It’s typically used after committing changes to push them to platforms like GitHub or GitLab.

## 11. Pull Changes from Remote Repository
`git pull`  
Fetches the latest changes from the remote repository and merges them into your local branch. It’s useful to keep your branch up to date with the latest changes from other contributors.

## 12. Remove Files from Staging Area
`git reset <file-name>`  
Removes a file from the staging area, but keeps the changes in your working directory. This is helpful when you add a file to staging by mistake.

## 13. Remove a File from the Repository
`git rm <file-name>`  
Deletes a file from your working directory and stages the deletion for the next commit.

## 14. Stash Uncommitted Changes
`git stash`  
Temporarily saves changes that aren’t ready to be committed yet. You can later retrieve these changes using `git stash pop`.

## 15. View Differences Between Commits or Branches
`git diff`  
Shows changes between your working directory and the staging area, or between commits. This is useful to see what changes have been made before committing them.

## 16. Set Global Configuration for Git
`git config --global user.name "Your Name"`  
`git config --global user.email "youremail@example.com"`  
Configures your username and email address globally for all your repositories. This ensures that your commits are associated with your correct Git identity.

## 17. Create and Apply Tags
`git tag <tag-name>`  
Tags a specific commit with a meaningful name (e.g., `v1.0` for a release version). You can use `git push origin --tags` to push tags to a remote repository.

## 18. Delete a Branch
`git branch -d <branch-name>`  
Deletes a specified branch from your local repository. You should ensure that the branch is merged before deleting it.

## 19. Check Remote URLs
`git remote -v`  
Shows the remote repository URLs that are being tracked. Use this to verify that you’re pushing and pulling from the correct remote repository.

## 20. Fetch Changes from Remote
`git fetch`  
Downloads objects and refs from the remote repository but doesn’t merge them. This is used to see what others have pushed to the repository without applying the changes yet.

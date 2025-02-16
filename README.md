### create a new repository on the command line
```
echo "# AzureBlobStorage" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/biplobpustcse/AzureBlobStorage.git
git push -u origin main
```
### 1. Basic Setup
#### git config: Set global or local configuration.
```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
### 2. Cloning and Fetching
#### git clone: Clone a remote repository.
```
git clone <repository-url>
```
#### git fetch: Fetch updates from the remote without merging.
```
git fetch origin
```
### 3. Branch Management
#### git branch: List, create, or delete branches.
```
git branch          # List branches
git branch <name>   # Create a new branch
git branch -d <name> # Delete a branch
```
### Committing and Pushing
#### Stage and commit changes:
#### Check the status of your repository:
```
git status
```
#### add all files changes
```
git add .
git commit -m "Your commit message"
```
#### add one file change
```
git add example.txt //current directory
git add folder/subfolder/example.txt //subdirectory, provide the relative path
git commit -m "Your commit message"
```
#### git checkout (deprecated in favor of switch):
```
git checkout <branch-name>  # Switch to a branch
git checkout -b <branch-name>  # Create and switch to a branch
```
#### git switch: A modern alternative to checkout for switching branches.
```
git switch <branch-name>
git switch -c <branch-name>  # Create and switch
```
### 4. Synchronizing with Remote
#### git pull: Fetch and merge updates from the remote repository.
```
git pull origin <branch>
```
#### git push: Push local changes to the remote repository.
```
git push origin <branch>
```
### 5. Merging and Rebasing
#### git merge: Merge one branch into another.
```
git checkout main
git merge <feature-branch>
```
#### git rebase: Reapply commits on top of another branch.
```
git checkout <feature-branch>
git rebase main
```
### 6. Resolving Conflicts
#### git status: Check the current status of your repository.
```
git status
```
#### git diff: View the changes causing the conflict.
```
git diff
```
#### git mergetool: Use a merge tool to resolve conflicts.
```
git mergetool
```
#### After resolving conflicts, stage changes:
```
git add <conflicted-file>
git rebase --continue  # Or git merge --continue
```
### git remote: Manage remote repositories.
```
git remote add origin <url>
git remote -v
```




<div>
    <h3>&hellip;or create a new repository on the command line</h3>
    <div>
        
<pre>echo &quot;# test&quot; &gt;&gt; README.md
git init
git add README.md
git commit -m &quot;first commit&quot;
git branch -M main
git remote add origin https://github.com/Eng-Biplob/test.git
git push -u origin main</pre>
</div>
<div>
    <h3>&hellip;or push an existing repository from the command line</h3>
<div>
        
<pre>git remote add origin https://github.com/Eng-Biplob/test.git
git branch -M main
git push -u origin main</pre>

</div>
<hr>
# Git-Cheat-Sheet
<br>
<a href="https://github.com/Eng-Biplob/Git-Cheat-Sheet/blob/main/git-cheat-sheet.docx?raw=true" target="_blank">View</a>
<br>
<a href="https://github.com/Eng-Biplob/Git-Cheat-Sheet/blob/main/git-cheat-sheet.pdf" target="_blank">View PDF.</a>




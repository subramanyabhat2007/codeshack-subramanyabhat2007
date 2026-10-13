# Git Workflow: Create a Branch, Edit, Commit, and Push
### Step 1: Create a new branch

Create a separate branch to work on a feature without directly modifying the `main` branch.

```bash
git switch -c feature/my-update
```

### Step 2: Edit a file

Open a file in the repository, such as `README.md`, and add or modify some content. Save the file.

### Step 3: Check the changes

Check which files have been modified.

```bash
git status
```

To view the exact changes, run:

```bash
git diff
```

### Step 4: Stage the changes

Add the modified file to the staging area.

```bash
git add README.md
```

To stage all modified and new files, you can use `git add .` instead.

### Step 5: Commit the changes

Save the staged changes as a commit with a descriptive message.

```bash
git commit -m "docs: update README"
```

### Step 6: Push the branch to GitHub

Upload the branch and its commits to the remote repository.

```bash
git push -u origin feature/my-update
```

The `-u` option links the local branch to the remote branch, making future pushes easier.

### Step 7: Verify the result

Check the recent commits:

```bash
git log --oneline
```

Open the repository on GitHub and confirm that your branch and commit are visible.

### Summary

**Create branch → Edit file → Check changes → `git add` → `git commit` → `git push`**

This workflow allows me to work independently on a feature branch and upload my changes to GitHub without committing directly to `main`.

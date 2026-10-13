# Git Command Notes

## 1. git init

Initializes a new Git repository in the current directory.

Example:

```bash
git init
```

Use this when starting version control for a new project.

## 2. git clone

Creates a local copy of an existing repository.

Example:

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

Use this when you want to download a repository from GitHub and work on it locally.

## 3. git status

Shows the current state of the working directory and staging area.

Example:

```bash
git status
```

Use this to check which files are modified, staged, or untracked.

## 4. git add

Stages changes for the next commit.

Example:

```bash
git add README.md
```

To stage all changes in the current directory:

```bash
git add .
```

Staging allows you to choose which changes will be included in a commit.

## 5. git commit

Records staged changes in the repository history.

Example:

```bash
git commit -m "Add project README"
```

A good commit message briefly describes the change being recorded.

## 6. git log

Displays the commit history.

Example:

```bash
git log
```

For a compact history:

```bash
git log --oneline
```

Use this to inspect previous commits.

## 7. git diff

Shows differences between file versions.

Example:

```bash
git diff
```

This shows unstaged changes compared with the index.

To inspect staged changes:

```bash
git diff --staged
```

## 8. git branch

Lists branches or creates a new branch.

Example:

```bash
git branch
```

Create a branch:

```bash
git branch feature-notes
```

Branches let you work on changes independently.

## 9. git switch

Switches to another branch.

Example:

```bash
git switch feature-notes
```

Create and switch to a new branch:

```bash
git switch -c feature-notes
```

## 10. git push

Uploads local commits to a remote repository.

Example:

```bash
git push -u origin main
```

The `-u` option sets the upstream branch for future pushes.

## 11. git pull

Fetches remote changes and integrates them into the current branch.

Example:

```bash
git pull origin main
```

Use this to update your local branch with changes from the remote repository.

## 12. git fetch

Downloads information about remote changes without integrating them into the current branch.

Example:

```bash
git fetch origin
```

You can inspect the fetched changes before deciding to merge or rebase them.

## 13. git merge

Integrates changes from one branch into the current branch.

Example:

```bash
git merge feature-notes
```

This merges the specified branch into the branch you currently have checked out.

## 14. git remote

Manages remote repository connections.

Example:

```bash
git remote -v
```

This displays the remote names and their URLs.

## 15. git restore

Discards unstaged changes in a file.

Example:

```bash
git restore README.md
```


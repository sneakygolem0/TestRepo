# Git — README

A brief overview of Git and how to get started.

## What is Git?
Git is a distributed version control system (VCS) for tracking changes in source code and coordinating work among multiple people. It stores snapshots of a project, supports branching and merging, and works locally and remotely.

## Why use Git?
- Keeps a history of changes.
- Enables collaboration and parallel development.
- Lightweight branching and safe experimentation.
- Works offline and syncs with remote repositories.

## Basic concepts
- Repository (repo): project storage (local or remote).
- Commit: a recorded snapshot of changes.
- Staging area (index): files prepared for the next commit.
- Branch: independent line of development.
- Remote: a copy of the repo hosted elsewhere (e.g., GitHub).

## Common commands
```bash
# initialize a repo
git init

# clone a remote repo
git clone <url>

# check status and history
git status
git log --oneline

# stage and commit changes
git add <file>
git commit -m "message"

# branches and switching
git branch
git checkout <branch>
git checkout -b <new-branch>

# update and share
git pull
git push

# merge another branch
git merge <branch>
```

## Getting started
1. Install Git (https://git-scm.com).
2. Configure identity:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"
    ```
3. Create or clone a repository, then use add/commit/push as you work.

## Tips
- Commit early and often with clear messages.
- Use branches for features and pull requests for reviews.
- Read diffs before committing: `git diff` and `git diff --staged`.

That's a quick reference to get started with Git.
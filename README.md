# Command Line & Git Basics

## Command Line Commands

These are essential terminal commands for navigating and managing files and folders in a project:

| Command | Description |
|--------|-------------|
| `pwd` | Present Working Directory – shows your current directory |
| `ls` | Lists contents of the current directory |
| `cd <directory>` | Change directory – move into a folder |
| `clear` | Clears the terminal screen (shortcut: `Ctrl + L`) |
| `mkdir <foldername>` | Creates a new folder |
| `code .` | Opens the current directory in Visual Studio Code |
| `touch <filename>` | Creates a new file in the current directory |

---

## Git Repository Setup

To initialize and link a Git repository:

| Command | Description |
|--------|-------------|
| `git init` | Initializes a new Git repository in the current folder |
| `git remote add origin <git-url>` | Connects your repo to a remote GitHub repository |
| `git remote -v` | Verifies the remote origin connection |

---

## Making a Git Commit & Pushing to GitHub

Follow these steps to commit changes and push them to GitHub:

| Command | Description |
|--------|-------------|
| `git add .` | Stages all changes in the current directory for commit |
| `git commit -m "your message here"` | Commits changes with a message |
| `git push origin main` | Pushes the changes to the `main` branch on GitHub |

---

## Cloning a Repository

| Command | Description |
|--------|-------------|
| `git clone <git-url>` | Creates a local copy of a remote repository |

---

## Checking Status and History

| Command | Description |
|--------|-------------|
| `git status` | Shows current changes and staging info |
| `git log` | Shows commit history |

---

## Working with Branches

| Command | Description |
|--------|-------------|
| `git branch` | Lists all branches |
| `git checkout -b <branch-name>` | Creates and switches to a new branch |
| `git checkout <branch-name>` | Switches to an existing branch |
| `git merge <branch-name>` | Merges a branch into the current one |


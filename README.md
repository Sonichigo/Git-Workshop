# Git-Workshop

Welcome to the Git Workshop! This workshop is designed to introduce you to Git, a distributed version control system that helps manage and track changes in your code.


## Table of Contents

1. [Introduction to Git](#introduction-to-git)
2. [Installation](#installation)
3. [Getting Started with Git](#getting-started-with-git)
   - [Initializing a Repository](#initializing-a-repository)
   - [Cloning a Repository](#cloning-a-repository)
4. [Basic Git Commands](#basic-git-commands)
   - [Checking Status](#checking-status)
   - [Adding Files](#adding-files)
   - [Committing Changes](#committing-changes)
   - [Pushing Changes](#pushing-changes)
   - [Pulling Changes](#pulling-changes)
5. [Branching and Merging](#branching-and-merging)
   - [Creating a Branch](#creating-a-branch)
   - [Switching Branches](#switching-branches)
   - [Merging Branches](#merging-branches)
6. [Working with Remote Repositories](#working-with-remote-repositories)
   - [Adding a Remote](#adding-a-remote)
   - [Fetching and Pulling](#fetching-and-pulling)
   - [Pushing to Remote](#pushing-to-remote)
7. [Advanced Git Commands](#advanced-git-commands)
   - [Stashing Changes](#stashing-changes)
   - [Rebasing](#rebasing)
8. [Best Practices](#best-practices)
9. [Resources](#resources)
10. [Q&A](#qa)

## Introduction to Git

Git is a distributed version control system created by Linus Torvalds in 2005. It allows multiple developers to work on a project simultaneously, track changes, and collaborate effectively. Git is widely used in the software development industry and is a fundamental tool for version control.

## Installation

### Windows

Download the Git installer from the [official Git website](https://git-scm.com/downloads) and follow the installation instructions.

### macOS

Install Git using Homebrew:
```bash
brew install git
```

### Linux

Install Git using the package manager:
```bash
sudo apt-get install git        # Debian/Ubuntu
sudo yum install git            # Fedora
```

## Getting Started with Git

### Initializing a Repository

To create a new Git repository:
```bash
git init
```

### Cloning a Repository

To clone an existing repository:
```bash
git clone <repository-url>
```

## Basic Git Commands

### Checking Status

To check the status of your working directory and staging area:
```bash
git status
```

### Adding Files

To add files to the staging area:
```bash
git add <file-name>
```

To add all files:
```bash
git add .
```

### Committing Changes

To commit changes with a message:
```bash
git commit -m "Your commit message"
```

### Pushing Changes

To push changes to the remote repository:
```bash
git push origin <branch-name>
```

### Pulling Changes

To pull changes from the remote repository:
```bash
git pull origin <branch-name>
```

## Branching and Merging

### Creating a Branch

To create a new branch:
```bash
git branch <branch-name>
```

### Switching Branches

To switch to a different branch:
```bash
git checkout <branch-name>
```

### Merging Branches

To merge a branch into the current branch:
```bash
git merge <branch-name>
```

## Working with Remote Repositories

### Adding a Remote

To add a remote repository:
```bash
git remote add origin <remote-url>
```

### Fetching and Pulling

To fetch changes from the remote repository:
```bash
git fetch origin
```

To pull changes from the remote repository:
```bash
git pull origin <branch-name>
```

### Pushing to Remote

To push changes to the remote repository:
```bash
git push origin <branch-name>
```

## Advanced Git Commands

### Stashing Changes

To stash changes:
```bash
git stash
```

To apply stashed changes:
```bash
git stash apply
```

### Rebasing

To rebase your current branch onto another branch:
```bash
git rebase <branch-name>
```

To pickup, squash, or reset your commmits :

```
git rebase HEAD~<No of Commits> -i

## force push

git push --force
```

## Best Practices

- Commit often with meaningful messages.
- Use branches for new features or bug fixes.
- Keep your branch history clean by rebasing and squashing commits.
- Regularly push your changes to remote repositories.
- Review code and collaborate using pull requests.

## Resources

- [Pro Git Book](https://git-scm.com/book/en/v2)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
- [GitHub Learning Lab](https://lab.github.com/)

## Q&A

Feel free to ask any questions during the workshop. Happy coding!

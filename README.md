# Git Basics: A Quick Guide

## Introduction

Git is a distributed version control system that helps you track changes in your code, collaborate with others, and manage your project's history. This guide covers the basic Git commands and concepts.

## Getting Started

### 1. Installing Git

Before using Git, make sure it's installed on your machine. You can download it from [here](https://git-scm.com/downloads).

### 2. Configuring Git

After installation, configure your name and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Creating a New Repository

### 3.Initializing a Repository

```bash
    git init
```

### 3.Adding Files

```bash
    git add <filename>
    git add .
```

### 4.Committing Changes

```bash
    git commit -m "<commit message>"
```

### 5. Push the Change to server

```bash
    git push origin <branch name>
```

## Working with Branches

### 1. Creating a Branch

Create a new branch for a feature or bug fix:

```bash
git branch <feature-branch>
```

### 2. Switching Branches

Switch to the new branch:

```bash
git checkout feature-branch
```

### 3. Merging Branches

Merge changes back into the main branch:

```bash
git checkout main
git merge feature-branch
```

## Collaboration

### 1. Cloning a Repository

Clone a remote repository to your local machine:

```bash
git clone https://github.com/username/repo.git
```

### 2. Pulling Changes

Update your local repository with remote changes:

```bash
git pull origin main
```

### 3. Pushing Changes

Push your local changes to the remote repository:

```bash
git push origin main
```

### Additional Commands

- `git status`: Check the status of your repository.
- `git log`: View commit history.
- `git diff`: Show changes between commits.

https://www.figma.com/file/jEqOupFgUT4MSdxuv8ZBFH/Restaurants?node-id=1%3A3&mode=dev

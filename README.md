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

### 3.Initializing a Repository

```bash
    git init
```

### 3.Adding Files

```bash
    git add <filename>
    git add .
```

### 4.Committing  Changes

```bash
    git commit -m "<commit message>"
```

### 5. Push the Change to server
```bash
    git push origin <branch name>
``` 
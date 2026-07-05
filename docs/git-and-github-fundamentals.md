# Git and GitHub Fundamentals

**Version:** 0.1
**Status:** Living Document

## Purpose

This document records the Git and GitHub concepts learned while building this repository.

The objective is not to memorize commands, but to understand what each command changes inside the version-control system.

## Git and GitHub

**Git** is a version-control system that records the history of a project. It works locally on the developer's computer and does not require an internet connection.

**GitHub** is an online platform that hosts Git repositories. It allows projects to be published, shared, reviewed, and synchronized between different computers.

Although they are commonly used together, Git and GitHub are different tools:

- Git manages the history of the project.
- GitHub stores and publishes a remote version of the repository.
## The Three Main Areas

Git manages changes through three main areas:

### 1. Working Tree

The working tree contains the files that are currently visible and editable inside the project folder.

When a file is created or modified in VS Code, the change initially exists only in the working tree.

### 2. Staging Area

The staging area, also called the **index**, contains the exact version of the changes selected for the next commit.

The command:

```bash  
git add <file>
```
 

copies the current state of a file into the staging area. Git does not inspect or approve its quality; the developer decides that the change is ready to be included.

### 3. Repository History

The repository history contains the commits that have already been recorded.

Each commit represents a snapshot of the staged changes at a specific moment in the development of the project.
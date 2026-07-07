# Git and GitHub Fundamentals

**Version:** 0.1

**Status:** Living Document

---

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
The Staging Area allows the developer to decide precisely which modifications will become part of the next official version of the project.


### 3. Repository History

The repository history contains the commits that have already been recorded.

Each commit represents a snapshot of the staged changes at a specific moment in the development of the project.



### The Git Workflow

Every change follows the same workflow inside Git.

```text
Working Tree
      │
      ▼
git add
      │
      ▼
Staging Area (Index)
      │
      ▼
git commit
      │
      ▼
Local Repository
      │
      ▼
git push
      │
      ▼
Remote Repository (GitHub)
```

Understanding this workflow is far more important than memorizing Git commands.

Each command simply moves the project from one stage to the next.



## Engineering Analogies

### Working Tree

Imagine an engineering workbench.

Blueprints are open, measurements are changing, and components are constantly being adjusted.

Nothing is official yet.

The Working Tree represents this stage of development.



### Staging Area

Imagine the final inspection table before releasing a manufactured part.

Only the approved version is allowed to continue to production.

The Staging Area serves the same purpose by selecting exactly which changes will become part of the next official revision.



### Commit

Imagine reaching an important checkpoint in a videogame.

Saving your progress allows you to continue later or return to that exact moment if something goes wrong.

A Git commit works in a very similar way, except that it saves the complete state of the project instead of the game's progress.



### Repository

Think of a repository as the complete engineering archive of a project.

Instead of storing only the latest version, it preserves the entire development history, allowing every official revision to remain available.



### GitHub

GitHub can be compared to the official archive shared by an engineering team.

While Git manages the project's history locally, GitHub stores a synchronized remote copy that can be shared, backed up, and accessed from different computers.



## Best Practices

Before creating a commit, ask yourself three questions:

- Do all modified files belong to the same logical idea?
- Am I satisfied with the current state of the project?
- Does the commit message clearly describe the change?

If the answer to all three questions is **yes**, the project is usually ready for a commit.



### Common Mistakes

- Creating commits that contain multiple unrelated changes.
- Forgetting to review the project using `git status`.
- Using `git push --force` without understanding its consequences.
- Treating Git as cloud storage instead of a version-control system.



## Commands Covered

| Command | Purpose |
|----------|---------|
| `git clone` | Create a local copy of an existing repository. |
| `git status` | Display the current state of the project. |
| `git add` | Move changes from the Working Tree to the Staging Area. |
| `git commit` | Record an official snapshot of the staged changes. |
| `git commit --amend` | Replace the most recent commit before continuing development. |
| `git push` | Synchronize the local repository with GitHub. |
| `git push --force-with-lease` | Safely replace the remote history when intentionally rewriting commits. |
| `git log` | Display the project's commit history. |



## Coverage Checklist

## Core Concepts

- [x] Git
- [x] GitHub
- [x] Repository
- [x] Working Tree
- [x] Staging Area
- [x] Repository History
- [x] Local Repository
- [x] Remote Repository
- [x] Commit
- [x] Commit History

### Commands

- [x] git clone
- [x] git status
- [x] git add
- [x] git commit
- [x] git commit --amend
- [x] git push
- [x] git push --force-with-lease
- [x] git log

### Future Topics

- [ ] Branches
- [ ] Merge
- [ ] Rebase
- [ ] Cherry-pick
- [ ] Tags
- [ ] .gitignore
- [ ] Pull Requests
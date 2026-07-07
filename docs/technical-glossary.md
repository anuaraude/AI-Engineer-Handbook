# Technical Glossary

**Version:** 0.2  
**Status:** Living Document

---

## About this document

This glossary contains the technical concepts learned throughout the AI Engineer Handbook.

Its purpose is not to memorize definitions, but to build a personal knowledge base that evolves with experience.

The mastery rating represents my current confidence in understanding, explaining, and applying each concept without external assistance.

The objective is continuous improvement, not perfection.

---

## Mastery Scale

⭐☆☆☆☆

I have heard the concept before.

⭐⭐☆☆☆

I understand the basic idea.

⭐⭐⭐☆☆

I can explain it without external help.

⭐⭐⭐⭐☆

I can apply it confidently in engineering problems.

⭐⭐⭐⭐⭐

I understand the concept deeply enough to teach it and connect it with other disciplines.

---

# A

## Algorithm

**Category:** Concept  
**Mastery:** ⭐⭐☆☆☆


### Definition

An algorithm is a finite sequence of logical steps designed to solve a problem or accomplish a specific task.


### Why does it exist?

Computers cannot improvise.

Every operation must be described as an ordered sequence of instructions.

Algorithms provide that sequence.

### Engineering Analogy

An algorithm is equivalent to a standard operating procedure (SOP) used in engineering.

For example, the procedure for calibrating a pressure sensor is an algorithm: each step has a defined order, and changing that order may produce incorrect results.

### Real-World Example

Making coffee can be described as an algorithm:

1. Heat water.
2. Grind coffee beans.
3. Place the filter.
4. Pour the water.
5. Serve.

Changing the order changes the result.

### Related Concepts

- Program
- Function
- Logic
- Flowchart

### Personal Notes

Algorithms are not exclusive to programming.

I have been using algorithms throughout my engineering career without calling them that.

### First Learned

Week 0

---

# C

## Commit

**Category:** Version Control  
**Mastery:** ⭐⭐⭐☆☆


### Definition

A commit is an official snapshot that records a meaningful state of a project within its version history.

Rather than simply saving files, a commit preserves a complete idea or logical unit of work, making it possible to understand how the project evolved over time.


### Why does it exist?

Software development is a continuous process.

Without checkpoints, mistakes could permanently overwrite previous work and it would become difficult to understand when or why changes were introduced.

A commit exists to record important milestones in a project's evolution, allowing developers to safely review, compare, restore, and continue their work.


### Engineering Analogy

Imagine approving Revision 12 of an engineering drawing.

Once signed and archived, that revision becomes an official reference for the project.

Future modifications will build upon it, but Revision 12 will always remain available for consultation if needed.

A Git commit serves exactly the same purpose.


### Real-World Example

After completing the first version of the Git Fundamentals document, the engineer creates a commit with the message:

> Add Git and GitHub fundamentals guide

That commit permanently records the completion of a meaningful milestone instead of simply saving unfinished work.


### Related Concepts

- Git
- Repository
- Version Control
- History
- Snapshot
- Staging Area


### Personal Notes

At first, I believed a commit was simply a way of saving changes.

Now I understand that a commit represents a conscious engineering decision.

It marks the completion of a meaningful piece of work that deserves to become part of the project's permanent history.

From now on, before creating a commit, I ask myself:

"Is this idea complete enough to become part of the project's history?"


### First Learned

Week 0

---

# E

## Engineer

**Category:** Profession  
**Mastery:** ⭐⭐⭐⭐☆

### Definition

An engineer is a professional who applies scientific and technical knowledge to design, analyze, improve, and maintain systems that solve real-world problems.

### Why does it exist?

Technology alone does not solve problems.

Engineering exists to transform scientific knowledge into reliable, efficient, safe, and maintainable solutions.

### Engineering Analogy

An engineer is not defined by the tools they use.

Just as a mechanical engineer can work with CAD software, CNC machines, or finite element analysis, an AI engineer may use Python, PyTorch, or Git.

The tools change.

Engineering thinking remains.

### Real-World Example

Two people may know exactly the same Python syntax.

One writes code that only works.

The other designs software that can still be maintained five years later.

Both are programmers.

Only one is thinking like an engineer.

### Related Concepts

- System
- Architecture
- Design
- Optimization
- Problem Solving

### Personal Notes

My goal is not to become someone who knows Python.

My goal is to become an engineer capable of applying Artificial Intelligence to solve complex engineering problems.

### First Learned

Week 0

---

# G

## Git

**Category:** Tool  
**Mastery:** ⭐⭐⭐☆☆


### Definition

Git is a distributed version control system that records, organizes, and manages the complete history of a software project.

Rather than storing only files, Git preserves the evolution of a project by recording every meaningful change over time.


### Why does it exist?

Software projects continuously evolve.

Git exists to make those changes traceable, reversible, and organized, allowing developers to work safely without losing previous work.

It also enables multiple engineers to collaborate on the same project while maintaining a reliable project history.


### Engineering Analogy

Imagine an engineering logbook that records every approved modification made to an aircraft during its entire development.

Instead of replacing previous revisions, every important change is documented and remains available for future reference.

Git performs the same function for software projects.


### Real-World Example

A development team is building an autonomous drone.

Every improvement, bug fix, and new feature is recorded using Git.

Months later, the team can review exactly when each modification was introduced and recover previous versions if necessary.


### Related Concepts

- Version Control
- Repository
- GitHub
- Commit
- Branch
- History


### Personal Notes

Before learning Git, I thought it was simply a tool for uploading projects to GitHub.

Now I understand that Git is responsible for managing the project's complete history, while GitHub is simply one place where that history can be shared.


### First Learned

Week 0

---

## GitHub

**Category:** Platform  
**Mastery:** ⭐⭐⭐☆☆


### Definition

GitHub is a cloud-based platform that hosts Git repositories, allowing software projects to be stored, synchronized, shared, and collaboratively developed.

While Git manages a project's history locally, GitHub extends that history beyond a single computer.


### Why does it exist?

Modern software is rarely developed by one person on one computer.

GitHub exists to provide a centralized platform where repositories can be backed up, shared, reviewed, and collaboratively maintained.

It also serves as a public record of a project's evolution.


### Engineering Analogy

Imagine the official engineering archive of a company.

Every approved design, revision, and technical document is stored in a central location where authorized engineers can review, update, and collaborate on the project.

GitHub serves the same purpose for software development.


### Real-World Example

An AI engineering team develops a computer vision model.

Each engineer works locally using Git, but the project's official repository is hosted on GitHub.

This allows every team member to synchronize their work, review contributions, and maintain a single source of truth for the project.


### Related Concepts

- Git
- Repository
- Version Control
- Remote Repository
- Commit
- Branch


### Personal Notes

Before learning Git, I thought GitHub was simply a website where programmers uploaded code.

Now I understand that GitHub is a collaboration platform that allows software projects to be shared, documented, backed up, and continuously improved.

It is also becoming my public engineering portfolio.


### First Learned

Week 0

---

# R

## Repository

**Category:** Software Engineering  
**Mastery:** ⭐⭐⭐☆☆


### Definition

A repository is the organized collection that stores a project's files, history, and evolution in a single place.

Rather than containing only the latest version of a project, a repository preserves every meaningful revision, making it possible to understand how the project has changed over time.


### Why does it exist?

Software projects constantly evolve.

Without a centralized place to store both the current files and their complete history, tracking changes, collaborating with others, or recovering previous versions would become extremely difficult.

A repository provides a structured environment where a project's development can be safely managed throughout its entire life cycle.


### Engineering Analogy

Imagine the technical archive of an aircraft.

It does not only contain the latest blueprint.

It stores every approved revision, engineering change, inspection report, and design update throughout the aircraft's development.

A software repository serves the same purpose.

It preserves not only the current state of the project, but also the complete engineering history behind it.


### Real-World Example

An engineering company develops a new robotic arm.

Every design revision is archived together with documentation, calculations, test results, and manufacturing changes.

Years later, engineers can understand exactly how the design evolved.

A Git repository provides this same capability for software projects.


### Related Concepts

- Version Control
- Git
- GitHub
- Commit
- Branch
- History


### Personal Notes

At first, I thought a repository was simply a folder containing project files.

Now I understand that a repository is much more than a folder.

It is the complete historical record of a project's evolution.


### First Learned

Week 0

---

# V

## Version Control

**Category:** Software Engineering  
**Mastery:** ⭐⭐⭐☆☆


### Definition

Version Control is the engineering practice of preserving the evolution of a project by recording every meaningful change over time.

Instead of storing only the latest version, it preserves the complete evolution of the project, allowing previous versions to be reviewed, restored, or compared whenever necessary.


### Why does it exist?

Projects evolve continuously.

Requirements change, bugs are discovered, new features are added, and mistakes happen.

Without Version Control, every modification risks permanently replacing previous work.

Version Control exists to preserve the project's history, making development safer, more organized, and collaborative.


### Engineering Analogy

Imagine designing an aircraft.

Each design revision is carefully documented before new modifications are introduced.

If a new design fails during testing, engineers can return to a previous revision instead of starting from scratch.

Version Control applies exactly the same principle to software development.

Every important revision becomes part of the project's history.


### Real-World Example

An engineering team develops a machine over several months.

Each approved design revision is archived before new modifications begin.

If Revision 7 introduces a structural problem, the team can compare it with Revision 6 to identify exactly what changed.

Git performs the same function for software projects.


### Related Concepts

- Git
- GitHub
- Repository
- Commit
- Branch
- History


### Personal Notes

Before learning Git, I thought Version Control was simply a way of saving files.

Now I understand that it is a methodology for preserving the complete history of a project, making it possible to understand how the project evolved and safely recover from mistakes.


### First Learned

Week 0

---

# Coverage Checklist

## Version Control

- [ ] Branch
- [x] Commit
- [x] Git
- [x] GitHub
- [ ] Markdown
- [ ] Origin
- [ ] Repository
- [ ] Staging Area
- [x] Version Control
- [ ] Working Tree

## Software Engineering

- [x] Algorithm
- [x] Engineer
- [x] Software Engineering
- [ ] Programming
- [ ] Software Crisis
- [ ] Architecture
- [ ] Documentation
- [ ] Modularity

## Python

- [ ] Variable
- [ ] Object
- [ ] Data Type
- [ ] Function
- [ ] Parameter
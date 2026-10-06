# 🚀 Task 4 — Version-Controlled DevOps Project with Git

## 📌 Project Overview

This project demonstrates Git and GitHub best practices for managing a DevOps project using version control, branching, pull requests, commits, tags, and documentation.

## 🎯 Objective

The objective of this task is to manage a DevOps project using Git best practices and understand a proper Git-based development workflow.

## 🛠️ Tools Used

- Git
- GitHub
- GitHub Pull Requests
- Markdown

## 🌳 Branching Strategy

The project uses the following branches:

- main — Stable and production-ready code
- dev — Development and integration branch
- feature/documentation — Feature development branch

## 🔄 Git Workflow

feature/documentation → Pull Request → dev → Pull Request → main

This workflow helps keep the main branch stable while allowing development and feature changes to be reviewed before merging.

## 📂 Project Structure

devops-git-project/
├── .gitignore
├── TASKS.md
└── README.md

## 1️⃣ Initialize Git Repository

The project was initialized as a Git repository using:

git init

The default branch was configured as:

git branch -M main

## 2️⃣ Create .gitignore

A .gitignore file was added to prevent unnecessary files from being tracked.

The project ignores:

- node_modules/
- .env
- *.log
- .DS_Store

## 3️⃣ Git Branches

The following branches were created:

- main
- dev
- feature/documentation

The feature branch was created using:

git switch -c feature/documentation

## 4️⃣ Git Commits

Proper commits were created during development.

Example commits:

- Add gitignore
- Add DevOps task documentation

Meaningful commit messages were used to clearly describe the changes.

## 5️⃣ Feature Branch Development

The documentation was developed in the feature branch:

feature/documentation

After completing the changes, a Pull Request was created to merge the feature branch into the dev branch.

## 6️⃣ Pull Request — Feature to Dev

Pull Request workflow:

feature/documentation → dev

The Pull Request was reviewed and merged successfully.

This demonstrates the use of Pull Requests for controlled development.

## 7️⃣ Pull Request — Dev to Main

After the changes were merged into the dev branch, another Pull Request was created:

dev → main

The Pull Request was merged successfully into the main branch.

This demonstrates a proper development-to-production workflow.

## 8️⃣ Git Tag

A version tag was created for the project:

v1.0.0

Command used:

git tag -a v1.0.0 -m "Version 1.0.0"

The tag was pushed to GitHub.

## 9️⃣ Documentation

The project tasks and Git workflow are documented in:

TASKS.md

The documentation explains the completed Git activities and branching strategy.

## 🔐 Git Best Practices Used

- Meaningful commit messages
- Separate development branch
- Feature branch workflow
- Pull Requests before merging
- Protected workflow for the main branch
- .gitignore
- Version tagging
- Markdown documentation
- GitHub remote repository

## 📊 Project Workflow

Developer
↓
Feature Branch
↓
Commit Changes
↓
Pull Request
↓
dev
↓
Pull Request
↓
main
↓
Git Tag v1.0.0

## ✅ Task Result

The DevOps project was successfully managed using Git and GitHub.

The following requirements were completed:

- Git repository initialized
- GitHub repository created
- main branch created
- dev branch created
- Feature branch created
- Proper Git commits used
- Pull Requests created and merged
- .gitignore added
- Git tag v1.0.0 created
- Project documentation added using Markdown

## 🎓 What I Learned

- Git fundamentals
- GitHub repository management
- Git branching
- Feature branch workflow
- Pull Requests
- Git merging
- Git commits
- .gitignore
- Git tags and versioning
- Markdown documentation
- DevOps version-control best practices

## 👩‍💻 Author

Kirthika

GitHub: https://github.com/kirthika25160

## 🔗 Repository

https://github.com/kirthika25160/devops-git-project

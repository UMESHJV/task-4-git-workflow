# Task 4: Git Version Control Workflow

## Project Overview
This project demonstrates Git and GitHub version control practices as part of a DevOps internship task.

## Objectives
- Initialize and manage a Git repository.
- Create and maintain multiple branches.
- Track changes using meaningful commits.
- Use GitHub pull requests to review and merge changes.
- Configure a `.gitignore` file.
- Create and manage Git tags.
- Document the workflow using Markdown.

## Tools Used
- Git
- GitHub
- Windows PowerShell
- Visual Studio Code

## Branching Strategy
- `main` — primary project branch.
- `dev` — development and integration branch.
- `feature/update-documentation` — branch used to update project documentation.

## Project Files
- `README.md` — project overview and workflow.
- `project-notes.md` — task progress documentation.
- `.gitignore` — patterns for files Git should ignore.
- `app.txt` — sample project file.

## Git Workflow
1. Initialized the repository and created the initial commit.
2. Created the `dev` and feature branches.
3. Connected the local repository to GitHub.
4. Pushed the branches to GitHub.
5. Created a pull request and merged the documentation change.
6. Synchronized `main` and `dev`.
7. Created the annotated tag `v1.0.0`.

## Useful Git Commands

```bash
git status
git branch
git switch -c feature/example
git add .
git commit -m "Describe the change"
git log --oneline --graph --all
git tag -a v1.0.0 -m "Release version 1.0.0"
git push origin v1.0.0
```

## .gitignore
The `.gitignore` file excludes log files, environment files, and the `temp/` directory from version control.

## Outcome
This project provides practical experience with Git commits, branches, pull requests, merging, tags, and Markdown documentation.
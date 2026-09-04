# Git & GitHub Problem-Statement Assignment

**Student:** Aditya Kumar Tiwari  
**URN:** 2581117  
**Section:** 3E  
**Semester:** 3  
**Faculty Mentor:** Dr. Vaishali Maheshwari  

## Assigned Problems
1. Compare File Changes
2. Develop on a Separate Branch

## Repository Structure
- `notes.txt` — used to demonstrate `git diff` across working directory, staging area, and commits.
- `login.js` — developed on `feature-login` and merged into `main`.
- `.gitignore` — ignores common OS, editor, and environment files.

## Key Commands Demonstrated

### Compare File Changes
```bash
git status
git diff
git diff --staged
git diff HEAD
git log --oneline
git diff <commit1> <commit2>
git diff <branch1> <branch2>
```

### Develop on a Separate Branch
```bash
git branch
git checkout -b feature-login
git add login.js
git commit -m "feat: add basic login function"
git checkout main
git merge feature-login
git branch -d feature-login
```

## Commit Convention
This repository uses meaningful Conventional Commit prefixes such as:
- `docs:` documentation changes
- `feat:` new functionality
- `chore:` maintenance changes

## Learning Outcomes
- Understand Git's working directory, staging area, and repository/HEAD.
- Compare unstaged, staged, committed, and branch-level changes.
- Develop independently on a feature branch.
- Merge completed work back into `main`.

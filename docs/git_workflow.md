# Git Workflow Documentation

This document describes the Git and GitHub workflow followed during the AI/ML internship project.

---

## Branching Strategy
- The `main` branch contains stable and finalized code.
- A new feature branch is created for each task or update.

Example:
git checkout -b add-llm-notes

---

## Development Workflow
1. Create a new branch from `main`.
2. Make changes and commit them locally.
3. Push the branch to GitHub.
4. Open a Pull Request (PR) to merge into `main`.
5. Review CI results and merge the PR.

---

## Pull Requests
- Pull Requests are used to review changes before merging.
- CI runs automatically on every PR.
- Only PRs with successful CI checks are merged.

---

## Code Review Checklist
- Code follows formatting standards.
- Required files are added correctly.
- CI checks are passing.
- No unnecessary changes are included.

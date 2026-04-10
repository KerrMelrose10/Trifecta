# Trifecta

Trifecta Repository for Apps

## Overview

This repository contains applications for the Trifecta project. All development follows a collaborative code review workflow to ensure code quality and team alignment.

## Getting Started

### Prerequisites

- Git installed on your local machine
- Access to this repository
- A GitHub account with appropriate permissions

## Development Workflow

### 1. Create a Feature Branch

Create a new branch for your work:

```bash
git checkout -b feature/your-feature-name
```

Use descriptive branch names that reflect the feature or fix being implemented.

### 2. Make Your Changes

Implement your changes, making logical and atomic commits:

```bash
git add .
git commit -m "Descriptive commit message"
```

Write clear, concise commit messages that explain *what* changed and *why*.

DO NOT HAVE MULTIPLE COMMITS FOR ONE PR. ONE COMMIT PER PR.

To achieve this, if you make a commit to a PR that you have changed, run git reset --soft HEAD~1

This gives you your changes back and takes away the commit. You can edit it, and put up the commit.

### 3. Commit and Push

Push your branch to the remote repository:

```bash
git push origin feature/your-feature-name
```

### 4. Submit a Pull Request

Open a Pull Request on GitHub but **DO NOT MERGE**. 

Leave the PR open for review and approval. This allows:
- Discussion and feedback
- Catching issues before they reach the main branch

Once the PR is approved by the other person, it can be merged.

## Code Review Process

- All changes must go through peer review
- Address feedback and update your PR as needed
- Wait for approval before merging
- Maintain clear communication in PR discussions

## Support

For questions or issues, use Google or something because I am useless

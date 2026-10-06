# Git Interview Questions and Answers

## 1. What is Git?
Git is a distributed version control system used to track changes in source code and collaborate with developers.

## 2. What is the difference between merge and rebase?
Git merge combines changes from one branch into another and normally creates a merge commit.

Git rebase reapplies commits on top of another branch and creates a more linear project history.

## 3. What is a Pull Request?
A Pull Request is a request to merge changes from one branch into another branch on GitHub. It allows developers to review changes before merging.

## 4. How do you resolve merge conflicts?
First use git status to identify conflicted files. Edit the affected files, remove conflict markers, keep the required changes, then use git add and git commit to complete the resolution.

## 5. What are Git tags?
Git tags are references used to mark specific commits, commonly for software releases.

Example: git tag -a v1.0.0 -m "Version 1.0.0"

## 6. What is Git workflow?
Git workflow is the process used to manage code using branches, commits, Pull Requests, reviews, merges, and releases.

The workflow used in this project is: feature -> dev -> main

## 7. Explain git stash.
Git stash temporarily saves uncommitted changes so the working directory can be cleaned without creating a commit.

Examples: git stash, git stash list, git stash pop

## 8. What is the use of .gitignore?
The .gitignore file specifies files and directories that Git should not track, such as environment files, logs, dependency folders, IDE files, and generated files.

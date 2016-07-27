# Git Notes

## Git and GitHub

Git is a version control system that tracks changes to files over time.
GitHub hosts Git repositories so they can be shared and collaborated on.

Basic workflow:

1. Make changes to files
2. Stage changes with `git add`
3. Commit them with `git commit`
4. Push them to GitHub with `git push`

## Cloning Repositories

`git clone` downloads a complete copy of a repository from GitHub to a local machine.  
This allows developers to work on the same project from different computers.

## Forking vs Cloning

Cloning copies a repository from GitHub to a local machine.

Forking creates a personal copy of someone else's repository on GitHub.  
This allows a developer to experiment or contribute without changing the original project.

## Pull Requests

A pull request proposes changes from one repository (usually a fork) to another repository.

Maintainers review the changes and decide whether to merge them into the main project.

## Branches

Branches allow developers to work on new features or fixes without affecting the main project.

Changes can later be merged back into the main branch.

## Merging

Merging combines the changes from one branch into another branch.

Developers often merge feature branches back into the main branch
once the work is complete.
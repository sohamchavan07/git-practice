# git-practice

A tiny sandbox to illustrate manual versioning vs Git.

## Files
- `story.txt`: base story text
- `story_v1`, `story_v2`: manual copies simulating versions
- `limitations.txt`: three drawbacks of manual versioning

## Try Git here
Initialize a repo and capture history:

```bash
git init
git add .
git commit -m "Initial commit: add story, versions, limitations"
```

Make a change to `story.txt`, then record it:

```bash
git add story.txt
git commit -m "Update story"
```

View history and differences:

```bash
git log --oneline
git diff HEAD~1..HEAD
```

## Feature: README update on feature-readme
This README was updated on the `feature-readme` branch to complete the assignment.



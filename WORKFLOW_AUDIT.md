# Workflow Audit

This page documents how branch, pull request, issue, and close-out fit together at HeziLiu — a tidy, end-to-end GitHub workflow as shown in the show-and-tell demo.

## Branch

Work starts on a dedicated feature branch (e.g. `feature/audit-notes`) cut from the default branch (`main`). The branch is the unit of isolation: nothing production-y gets touched until a PR moves the change.

## Pull Request

A pull request is the bridge between the feature branch and the default branch. It reviews *what* changed (patch diff), who wrote it, and why, before anything merges. The audit notes land here as a committed write-up so reviewers can read them directly.

## Issue

An issue captures *what* needs to happen (work, checklists, follow-ups). A demo issue tracks the workflow checklist, and sub-issues break that checklist into smaller, trackable pieces.

## Close-Out

Close-out is the final step: approve or request changes on the PR, merge it, then close out the parent issue. Sub-issues get resolved as their work lands; the parent issue is closed as **completed**, leaving open any follow-up work that is still in flight.

## Owner

- **Login:** HeziLiu
- **Display name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
- **Profile:** https://github.com/HeziLiu

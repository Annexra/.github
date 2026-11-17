# Contributing to Annexra projects

Thanks for helping. This is how we work in every Annexra repo. It is short, and we are friendly about it, so please do not be nervous about getting something wrong.

## How work comes to you

We usually give interns their tasks through the Annexra workspace. Pick up your task, make a new branch for it, and raise a pull request when it is ready. Even for assigned tasks, work on a branch and raise a pull request instead of pushing straight to `main`.

If you find a feature or an improvement you would like to work on, go for it: raise an issue, make a branch, build it and raise a pull request. You do not need permission to try something.

## 1. Start with an issue

For anything bigger than a tiny fix, open an issue first so we can agree on it before you spend time building it. Every issue gets a number, like `#42`. Use that number in your branch name, your commits and your pull request, so the work is always connected to the reason for it.

## 2. Work on a branch, one feature per branch

Start from the latest `main` and make a new branch named after what it does, with the issue number in it.

```bash
git checkout main
git pull
git checkout -b feat/42-calendar-day-view
```

Branch names are lowercase, use hyphens, and follow `kind/issue-number-short-name`:

| Prefix | Use it for | Example |
| --- | --- | --- |
| `feat/` | a new feature | `feat/42-resources-search` |
| `fix/` | a bug fix | `fix/57-leave-end-date-validation` |
| `docs/` | docs only | `docs/61-contributing-guide` |
| `refactor/` | cleaning up code, no behaviour change | `refactor/63-task-filters` |
| `chore/` | dependencies, config, small upkeep | `chore/70-update-dependencies` |

Name the work, not yourself (`feat/42-team-birthdays`, not `rahul-branch`). One feature per branch and one branch per pull request.

## 3. Commits

- Write a short, plain sentence that says what changed: `Add days off to the daily meeting`, `Fix the duplicate link error on resources`.
- Not `update`, `fix`, `changes`, `wip` or `final final`.
- One logical change per commit. Small commits are easier to review.
- You can mention the issue at the end, for example `Fix the duplicate link error (#57)`.

## 4. Pull requests

- Open the pull request into `main` of the project repo. The repo's README tells you if it works differently.
- Use the template and fill in every part: the issue number, what you changed and why, how to test it step by step, screenshots for anything visual, and any database changes.
- Before you open it, run the checks listed in the repo's README (usually type check, lint and build) and make sure they pass.
- Keep it small. A pull request that does one thing gets reviewed quickly.
- If we ask for changes, push more commits to the same branch and the pull request updates by itself.

## About AI

Use AI, we encourage it. It is great for learning, drafting code and getting unstuck. Just remember that AI can be confidently wrong or make things up, so run the code, test it, and make sure you understand what it does before you submit it.

One small ask: write your **branch names, commit messages, issue titles and descriptions, and pull request titles and descriptions** yourself. AI text tends to be a long, vague pile of words, and we want to understand each other easily. A short, plain sentence from you is perfect.

## Secrets

Please never commit secrets: `.env` files, API keys, passwords or service account files. Keep them in a local `.env` file that stays on your machine. If you need a key or a login for your task, ask your manager. If one slips into a commit by mistake, tell us straight away so we can change it.

## Ideas, questions, or stuck?

You are always free to suggest ideas or ask anything. Message us on WhatsApp, post in the Annexra workspace, talk to your manager, or call anyone at Annexra. No question is too small.

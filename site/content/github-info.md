# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

## Editor's note on this update

This pass could not reach `github.blog/latest` or `github.blog/changelog`
directly (no network access from the update tool), so no new dated Blog or
Changelog items are cited here this round. To keep the "recent stories"
section accurate, Mona (or a contributor with browsing access) should visit
those two pages directly and add 2-3 fresh, dated entries with links next
time this file is refreshed, per `notes/mona-notes.md`.

## Practical reminders for readers (evergreen, not tied to a specific post)

- **Pull requests**: keep them small and focused — reviewers work faster on
  changes that do one thing, and GitHub's review tools (suggested changes,
  required reviewers) work best on tightly scoped diffs.
- **GitHub Copilot**: Copilot Chat and Copilot in the CLI can explain
  unfamiliar code, draft commit messages, and suggest fixes — use `/explain`
  or `/fix` in supported IDEs to speed up code review prep.
- **GitHub Actions**: reuse workflows with `workflow_call` and pin actions to
  a commit SHA (not just a tag) for supply-chain safety; check
  `github.blog/changelog` periodically for new triggers and runner images.
- **Staying current**: subscribe to `github.blog/changelog` for shipped
  product changes and `github.blog/latest` for deeper dives and best
  practices — both are the canonical sources this site draws from.

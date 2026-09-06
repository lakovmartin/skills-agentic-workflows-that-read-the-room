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

This pass could not reach github.blog or github.blog/changelog from the
update environment (outbound network access was unavailable), so no new
dated blog/changelog items are cited below. The section below has been
refreshed with practical, stable guidance instead, and should be
revisited with fresh Blog/Changelog links next time network access is
available, per `notes/mona-notes.md`.

## Practical tips for readers

- **Pull requests**: keep PRs small and focused; use draft PRs to share
  work-in-progress and gather early feedback before requesting review.
- **GitHub Copilot**: Copilot Chat in the IDE and on github.com can
  explain unfamiliar code, suggest tests, and help draft commit messages
  — pair it with your own review before merging suggestions.
- **GitHub Copilot CLI / coding agent**: assign well-scoped issues to
  Copilot's coding agent for routine fixes (docs, small bugs, test
  additions) so maintainers can focus review time on design decisions.
- **GitHub Actions**: cache dependencies (`actions/cache`) and reuse
  workflows (`workflow_call`) to speed up CI and avoid duplicating
  pipeline logic across repositories.
- **Branch protection**: require status checks and reviews on default
  branches to keep `main` deployable at all times.

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

## Note on this update

This update was drafted without live access to github.blog/latest or
github.blog/changelog (external network access was unavailable in the
authoring environment), so no specific recent posts are cited here. A
missing-tool report was filed so a maintainer can re-run this task with
web access to pull in current Blog/Changelog stories. In the meantime, the
practical, evergreen guidance below stays accurate and useful for readers.

## Practical tips for readers

- **Pull requests**: Use draft PRs to share work-in-progress and get early
  feedback before marking a PR ready for review.
- **GitHub Copilot**: Copilot Chat in the IDE can explain unfamiliar code,
  suggest tests, and help debug — try `/explain` and `/tests` slash
  commands for quick wins.
- **GitHub Actions**: Reuse workflows across repos with `workflow_call` to
  avoid duplicating CI/CD logic.
- **Repository hygiene**: Branch protection rules plus required status
  checks keep `main` deployable and reduce accidental breakages.

Check back for a follow-up update once live Blog/Changelog access is
restored, so newly announced features can be added here with full source
links.

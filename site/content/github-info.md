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

## Recent updates worth watching (September 2026)

### Pull requests & code review

- **Refreshed repository pull requests page (public preview)** — a redesigned repo-level PR list with better filtering, a compact view, and improved search. Handy for teams triaging large PR queues.
  Source: [GitHub Changelog, Sep 10, 2026](https://github.blog/changelog/2026-09-10-refreshed-repository-pull-requests-page-in-public-preview)
- **Block pull requests with exposed secrets from merging** — repository rulesets can now stop a merge outright when a PR introduces a secret scanning alert, closing a common leak path.
  Source: [GitHub Changelog, Sep 9, 2026](https://github.blog/changelog/2026-09-09-block-pull-requests-with-exposed-secrets-from-merging)
- **AI Scan for pull request APIs (public preview)** — new REST endpoints let teams programmatically enable AI-powered code scanning on pull requests.
  Source: [GitHub Changelog, Sep 10, 2026](https://github.blog/changelog/2026-09-10-ai-scan-for-pull-request-apis-in-public-preview)

### GitHub Copilot

- **Enterprise managed permissions for Copilot agent operations** — admins can now centrally set which Copilot agent actions are blocked, require approval, or auto-proceed, giving orgs finer control over agentic work.
  Source: [GitHub Changelog, Sep 9, 2026](https://github.blog/changelog/2026-09-09-enterprise-managed-permissions-for-github-copilot-agent-operations)
- **Agentic autofix for Code Quality findings** — assign up to 25 code-quality findings to Copilot at once; it fixes, validates, and opens a pull request automatically.
  Source: [GitHub Changelog, Sep 9, 2026](https://github.blog/changelog/2026-09-09-remediate-code-quality-findings-with-agentic-autofix)
- **Run several Copilot agents at once** — a beginner-friendly walkthrough of kicking off multiple parallel Copilot agent sessions instead of working one task at a time.
  Source: [GitHub Blog, Sep 3, 2026](https://github.blog/ai-and-ml/github-copilot/github-copilot-app-for-beginners-run-several-agents-at-once/)

### GitHub Actions & security

- **Least-privilege Actions caching with `cache-mode`** — a new, now-GA setting for controlling cache read/write access in workflows, reducing cache-poisoning risk.
  Source: [GitHub Changelog, Sep 10, 2026](https://github.blog/changelog/2026-09-10-control-github-actions-cache-access-with-cache-mode)
- **CodeQL 2.27.0 adds Linux ARM64 support** — CodeQL analysis can now run on Linux ARM64 environments, widening supported runners for code scanning.
  Source: [GitHub Changelog, Sep 9, 2026](https://github.blog/changelog/2026-09-09-codeql-2-27-0-adds-support-for-linux-arm64)

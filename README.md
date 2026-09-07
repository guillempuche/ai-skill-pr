# ai-skill-pr

Turn a finished change into a reviewable, mergeable pull request. Use when asked to "open a PR", "create a pull request", "raise a PR", "PR this", or "send it for review". Drives the whole lifecycle — re-baseline on the default branch, verify end-to-end with visual proof for UI work, self-review for pattern drift and AI-code smells, commit, run the verification gates, write the PR body in a house style, work the review loop, and merge by rebase or squash. Portable across repositories — gates, CI shape, worktree handling, and companion skills are read from the repo's own config or inferred, never hardcoded. Stops at merge; deploying is a separate step.

## Install

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-pr

# Install plugin (plugin name is topic-only)
/plugin install pr@guillempuche-ai-skill-pr
```

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT

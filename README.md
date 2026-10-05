# ai-skill-pr

Take a finished branch through to a merged GitHub pull request — verify, self-review, open, work the review, merge. Use when asked to "open a PR", "raise a PR", "PR this", "send it for review", or to update or merge a PR.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-pr
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-pr

# Install plugin (plugin name is topic-only)
/plugin install pr@guillempuche-ai-skill-pr
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-pr.git --path skills/pr
```

### Manual

Copy `skills/pr` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT

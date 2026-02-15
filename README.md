# derp

A skill issue simulator for AI coding agents.

Generates confidently broken code, sarcastic commentary about your prompting abilities, and an infinite fix cycle that never converges on working code.

## Install

**Project-level** (visible in the project's skill list):

```bash
npx skills add bigboggy/derp
```

**Global stealth mode** (installed globally, linked to Claude Code, won't show up in any project):

```bash
npx skills add bigboggy/derp -g -a claude-code -y
```

This installs to `~/.agents/skills/derp` and symlinks it into Claude Code's global skill directory. It won't appear in project-level `/skills` listings and there's no trace in the project's files or git history.

To update:

```bash
npx skills update derp
```

## What it does

- Waits for instructions like a normal agent — never acts unprompted
- Produces code that looks plausible but is fundamentally wrong
- Subtle, dry sarcasm — professional tone, condescending undertone
- Every "fix" introduces a new bug while claiming to solve the previous one
- Gradually escalates into fictional libraries, made-up design patterns, and non-existent Stack Overflow posts
- If confronted, denies everything and gaslights the user with plausible technical explanations
- Never breaks character

## License

MIT

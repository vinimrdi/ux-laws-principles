# Install ux-laws-principles

Copy **only** the skill folder so `SKILL.md` is at:

```text
~/.claude/skills/ux-laws-principles/SKILL.md
```

Not nested as `.../ux-laws-principles/skills/ux-laws-principles/SKILL.md`.

## Claude Code (recommended)

```bash
npx skills add https://github.com/vinimrdi/ux-laws-principles/tree/main/skills/ux-laws-principles -g -a claude-code
```

Manual:

```bash
git clone --depth 1 https://github.com/vinimrdi/ux-laws-principles.git /tmp/ux-laws-principles
mkdir -p ~/.claude/skills
cp -R /tmp/ux-laws-principles/skills/ux-laws-principles ~/.claude/skills/ux-laws-principles
# Cursor: ~/.cursor/skills/   ·  shared: ~/.agents/skills/   ·  project: .claude/skills/
```

Verify:

```bash
test -f ~/.claude/skills/ux-laws-principles/SKILL.md && echo OK
```

## Claude.ai (web chat)

A GitHub link alone is not enough (page readers often return a summary).

1. **Review card** — paste the full contents of `skills/ux-laws-principles/SKILL.md` and save the card, or  
2. **ZIP upload** — zip the `skills/ux-laws-principles` directory so the archive root is `ux-laws-principles/SKILL.md` (and optional `references/`).

```bash
git clone --depth 1 https://github.com/vinimrdi/ux-laws-principles.git /tmp/ux-laws-principles
cd /tmp/ux-laws-principles/skills
zip -r ~/Desktop/ux-laws-principles-skill.zip ux-laws-principles
```

Upload that zip where the product asks for a skill package (`SKILL.md` at the **first level** of the folder).

## Other hosts

| Host | Path |
|------|------|
| Cursor | `~/.cursor/skills/ux-laws-principles/` |
| Generic agents | `~/.agents/skills/ux-laws-principles/` |
| Project-only | `.claude/skills/ux-laws-principles/` inside the repo |

## Version

Skill version **1.4.5**. See [CHANGELOG.md](CHANGELOG.md).

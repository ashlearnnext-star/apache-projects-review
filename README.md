# Apache Projects Review

A skill for reviewing Apache Software Foundation projects with Claude Code or any other AI CLI.

## Layout

```
skills/
  <skill-name>/SKILL.md   # place the review skill file here
```

## Usage

- **Claude Code:** copy or symlink the skill folder into `~/.claude/skills/` (all projects) or `<repo>/.claude/skills/` (one project), then ask Claude to review an Apache project.
- **Other AI CLIs:** point the tool at `SKILL.md` as its instructions or system prompt.

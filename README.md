# cc-skills

Claude Code skills for Daml 3.x development on Canton.

## Skills

| Skill | Description |
|-------|-------------|
| `daml-language` | Daml 3.x language syntax and semantics reference |
| `daml-testing` | Daml Script testing patterns and best practices |
| `daml-cli` | DPM (Digital Asset Package Manager) CLI reference |
| `daml-canton` | Canton blockchain node setup and operations |
| `daml-typescript` | TypeScript integration for Canton JSON Ledger API v2 |

## Installation

Copy the `.claude/skills/` directory into your project root:

```bash
cp -r .claude/skills/ /path/to/your/project/.claude/skills/
```

Or copy individual skills as needed.

## Structure

```
.claude/
  skills/
    daml-canton/
      SKILL.md      # Skill metadata and trigger description
      AGENTS.md     # Full reference content
    daml-cli/
      SKILL.md
      AGENTS.md
    daml-language/
      SKILL.md
      AGENTS.md
    daml-testing/
      SKILL.md
      AGENTS.md
    daml-typescript/
      SKILL.md
      AGENTS.md
```

## License

MIT

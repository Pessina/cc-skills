# cc-skills

Claude Code skills for AI-assisted development. Each skill folder can be copied directly into `~/.claude/skills/` or your project's `.claude/skills/` directory.

## Installation

Clone and copy the skills you need:

```bash
git clone git@github.com:Pessina/cc-skills.git
cd cc-skills

# Install all Daml skills
cp -r daml-* ~/.claude/skills/

# Or install a single skill
cp -r daml-language/ ~/.claude/skills/daml-language/

# Or install into a specific project
cp -r daml-* /path/to/your/project/.claude/skills/
```

## Skill Structure

Each skill follows the same layout:

```
skill-name/
  SKILL.md        # Skill metadata, triggers, and quick reference
  AGENTS.md       # Complete compiled reference for AI agents
  README.md       # Human-readable documentation
  metadata.json   # Version, author, and reference links
```

---

## Daml

Skills for Daml 3.x smart contract development on Canton.

| Skill | Description |
|-------|-------------|
| [`daml-language`](./daml-language/) | Language syntax and semantics — templates, choices, data types, Update monad, DA.Crypto.Text, interfaces, contract keys, standard library |
| [`daml-testing`](./daml-testing/) | Daml Script testing — party allocation, multi-party submissions (`actAs`/`readAs`), assertions, lifecycle patterns, debugging |
| [`daml-cli`](./daml-cli/) | DPM CLI reference — `dpm build`, `dpm test`, `dpm sandbox`, `dpm codegen-js`, `daml.yaml` configuration |
| [`daml-canton`](./daml-canton/) | Canton node operations — sandbox startup, party/user management, DAR deployment, JSON Ledger API v2, troubleshooting |
| [`daml-typescript`](./daml-typescript/) | TypeScript integration — `openapi-fetch` client, codegen-js bindings, type mappings, WebSocket streaming, Vitest patterns |

---

## License

MIT

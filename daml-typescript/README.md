# Daml TypeScript Integration

Reference for building TypeScript clients that interact with Canton via the JSON Ledger API v2.

## Structure

- `SKILL.md` - Skill metadata and trigger description
- `AGENTS.md` - Complete compiled reference for AI agents
- `metadata.json` - Version and reference metadata

## Topics Covered

- Architecture: OpenAPI client + Daml model bindings (two-layer approach)
- OpenAPI client setup with `openapi-fetch` and `openapi-typescript`
- Daml codegen-js bindings and template imports
- Type mappings (Daml to TypeScript), hex encoding conventions
- Party allocation, user creation, DAR upload from TypeScript
- Command submission (create contracts, exercise choices)
- Active contract queries with party-based filtering
- WebSocket streaming for real-time ledger updates
- Testing patterns with Vitest (RUN_ID isolation)
- Common gotchas (createArguments vs createArgument, Int as string, etc.)

## Installation

```bash
cp -r daml-typescript/ ~/.claude/skills/daml-typescript/
```

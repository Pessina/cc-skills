# Daml Testing

Reference for writing and running Daml Script tests in Daml 3.x projects.

## Structure

- `SKILL.md` - Skill metadata and trigger description
- `AGENTS.md` - Complete compiled reference for AI agents
- `metadata.json` - Version and reference metadata

## Topics Covered

- Running tests with `dpm test`
- Test module structure and naming conventions
- Party allocation (`allocateParty`, `allocatePartyWithHint`)
- Contract creation and choice exercise in tests
- Multi-party submissions with `actAs` / `readAs` (Daml 3.x pattern)
- Querying contracts (`queryContractId`, `query`, `queryFilter`)
- Assertions (`assertMsg`, `abort`)
- Expected failures (`submitMustFail`)
- Patterns: full lifecycle, refund/failure paths, crypto verification
- Test helpers and fixtures
- Debugging tips and common mistakes

## Installation

```bash
cp -r daml-testing/ ~/.claude/skills/daml-testing/
```

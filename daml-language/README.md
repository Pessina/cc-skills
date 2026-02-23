# Daml Language

Comprehensive Daml 3.x language reference for writing smart contracts on Canton.

## Structure

- `SKILL.md` - Skill metadata and trigger description
- `AGENTS.md` - Complete compiled reference for AI agents
- `metadata.json` - Version and reference metadata

## Topics Covered

- Module system and imports
- Data types (records, variants, enums, newtypes, type aliases)
- Complete type system reference with TypeScript equivalents
- Template syntax (signatory, observer, ensure, key, maintainer)
- Choice syntax (consuming, nonconsuming, preconsuming, postconsuming)
- The Update monad (create, fetch, archive, exercise, assertions)
- DA.Crypto.Text module (BytesHex, keccak256, secp256k1WithEcdsaOnly)
- Interfaces and interface instances
- Contract keys (lookupByKey, fetchByKey, exerciseByKey)
- Standard library (DA.Optional, DA.List, DA.Map, DA.Set, DA.Action, DA.Time)
- Pattern matching, guards, common patterns

## Installation

```bash
cp -r daml-language/ ~/.claude/skills/daml-language/
```

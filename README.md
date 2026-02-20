# devstackai

Standardize context for working with AI in any repository.

Creates an `.ai/` folder as the **source of truth** (context, rules, and playbooks) and then generates adapters ready for tools like:

- Cursor (`.cursorrules`)
- Claude (`CLAUDE.md`)

> Edit `.ai/*` and regenerate with `devstackai sync`.

## Installation / Quick Start

### Recommended option (without installing)
```bash
npx devstackai
```

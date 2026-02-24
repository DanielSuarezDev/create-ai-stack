# devstackai

Standardize AI collaboration context in any repository.

`devstackai` creates an `.ai/` folder as the **single source of truth** for team context, rules, and playbooks, then generates adapters for popular coding assistants.

## Why devstackai?

- Keep project instructions centralized in `.ai/`
- Avoid duplicated prompt/rule files across tools
- Sync changes quickly with one command

## Supported adapters

- Cursor (`.cursorrules`)
- Claude (`CLAUDE.md`)

> Update files in `.ai/*`, then regenerate adapters with `devstackai sync`.

## Installation / Quick Start

### Recommended option (no installation)
```bash
npx devstackai
```

## Typical workflow

1. Initialize your project context with `devstackai`
2. Edit files inside `.ai/` to define standards and instructions
3. Run `devstackai sync` whenever `.ai/` content changes

## GitHub

If this project is useful, please support it with a star ⭐ and contributions:

- Repository: [https://github.com/danielsuarez-dev/devstackai](https://github.com/danielsuarez-dev/devstackai)

## Contributing

Contributions are welcome. Open an issue to discuss improvements or submit a pull request directly.

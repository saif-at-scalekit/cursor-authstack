# Archived

This repository is archived.

Scalekit auth plugins now live in one repo: **[scalekit-inc/authstack](https://github.com/scalekit-inc/authstack)**.

Portable skills (no plugin wrapper) live in **[scalekit-inc/skills](https://github.com/scalekit-inc/skills)**.

## Install

```bash
npx @scalekit-inc/cli setup cursor
```

Two kits replace the old five plugins:

| Kit | Replaces |
|-----|----------|
| **AgentKit** | `agent-auth` |
| **SaaSKit** | `full-stack-auth`, `mcp-auth`, `modular-sso`, `modular-scim` |

Do not install from this repo. Use `scalekit-inc/authstack`.

# Cursor AuthStack Marketplace

A marketplace of authentication-focused plugins for Cursor IDE, providing skills, agents, commands, and rules for OAuth, SSO, SCIM, MCP auth, and agent security.

## Installation

Add this marketplace to Cursor:

```
/plugin marketplace add <your-repo-url>
```

## Plugins

### mcp-auth
OAuth 2.1 authorization for MCP servers. Skills for token handling, refresh flows, and scope management.

### agent-auth
Secure authentication for AI agents and services. OAuth flows designed for AI agents with token persistence and service-to-service auth.

### fsa
Full-stack web authentication setup. End-to-end auth including login pages, session management, and protected routes.

### modular-sso
Enterprise SSO integration. Support for 20+ identity providers (Okta, JumpCloud, Entra ID) with SAML/OIDC and JIT provisioning.

### modular-scim
User provisioning and directory sync. SCIM 2.0 implementation with automatic schema mapping and sync automation.

## Structure

Each plugin follows Cursor's plugin structure:
- `.cursor-plugin/plugin.json` - Plugin manifest
- `skills/` - Agent capabilities (SKILL.md files)
- `agents/` - Custom agent configurations
- `commands/` - Agent-executable commands
- `rules/` - Persistent guidance rules (.mdc files)

## Development

1. Edit plugin manifests in `plugins/*/.cursor-plugin/plugin.json`
2. Add skills in `plugins/*/skills/*/SKILL.md`
3. Add agents in `plugins/*/agents/*.md`
4. Add commands in `plugins/*/commands/*.md`
5. Add rules in `plugins/*/rules/*.mdc`

## Validation

Validate the marketplace structure:

```bash
node scripts/validate-template.mjs
```

## License

MIT

---
name: dryrun-sso
description: Test SSO configuration without making actual provider connections.
---

# Dryrun SSO

## Purpose
Validate SSO configuration against identity provider requirements without creating real connections.

## Steps
1. Validate provider metadata URLs
2. Check required fields and attributes
3. Verify callback URL format
4. Validate certificate configuration
5. Test schema mapping logic

## What this does
- Parses configuration files
- Checks for required fields
- Validates URL formats
- Verifies certificate syntax
- Does NOT contact providers

---
name: dryrun-scim
description: Test SCIM provisioning configuration without actual provider sync.
---

# Dryrun SCIM

## Purpose
Validate SCIM configuration without making real provisioning requests.

## Steps
1. Validate SCIM endpoint URLs
2. Check authentication token format
3. Verify schema mapping configuration
4. Test attribute transformation logic
5. Validate bulk operation settings

## What this does
- Parses SCIM schema definitions
- Checks required attributes
- Validates mapping expressions
- Verifies endpoint configuration
- Does NOT sync any users

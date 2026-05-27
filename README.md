# Decapod Intent Kernel

Turn human intent into gates agents can actually follow.

Decapod Intent Kernel is a paid hosted remote MCP for Decapod. It exposes Streamable HTTP tool calls, bearer-token access, public server-card metadata, usage logs, and receipt-oriented JSON for AI agent workflows.

## Public Endpoints

- Website: https://decapodkernel.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- MCP endpoint: https://decapodkernel.clauxel.com/mcp
- Server card: https://decapodkernel.clauxel.com/server-card.json
- Registry name: `com.clauxel.decapodkernel/decapodkernel-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `create_intent_contract`
- `check_agent_boundary`
- `record_completion_proof`
- `export_intent_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://decapodkernel.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- Pricing: https://decapodkernel.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27#pricing
- Server card: https://decapodkernel.clauxel.com/server-card.json
- MCP endpoint: https://decapodkernel.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.

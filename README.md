# Decapod Intent Kernel

Decapod Intent Kernel is a hosted remote MCP for Decapod.

This repository is a public documentation project for Decapod Intent Kernel. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://decapodkernel.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=decapodkernel_public_docs&utm_content=readme_home
- Pricing: https://decapodkernel.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=decapodkernel_public_docs&utm_content=readme_pricing
- Checkout: https://decapodkernel.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=decapodkernel_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://decapodkernel.clauxel.com/mcp
- Server card: https://decapodkernel.clauxel.com/server-card.json
- Registry name: `com.clauxel.decapodkernel/decapodkernel-mcp`
- Tools: `create_intent_contract`, `check_agent_boundary`, `record_completion_proof`, `export_intent_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: create_intent_contract
- MCP tool: check_agent_boundary
- MCP tool: record_completion_proof
- MCP tool: export_intent_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.

# Agent Monitor Relay MCP

Track agent runs, failures, replay evidence, and SLA receipts from one MCP.

Paid remote MCP for AI agent run monitoring, failure detection, tool-call incident replay, SLA receipts, and client status exports.

## Public Endpoints

- Website: https://agentmonitorrelay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://agentmonitorrelay.clauxel.com/mcp
- Server card: https://agentmonitorrelay.clauxel.com/server-card.json
- Registry name: `com.clauxel.agentmonitorrelay/agentmonitorrelay-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `record_agent_run`
- `detect_agent_failure`
- `replay_tool_call_incident`
- `issue_sla_receipt`
- `export_client_status`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://agentmonitorrelay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://agentmonitorrelay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://agentmonitorrelay.clauxel.com/server-card.json
- MCP endpoint: https://agentmonitorrelay.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.

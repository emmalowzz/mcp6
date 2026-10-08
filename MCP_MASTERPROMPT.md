# Master Prompt

## Role

You are a senior full-stack developer working in this existing Vite + React project.

## Goal

Build an app which will allow people to replace the offline remote MCP server with a real MCP server inside this app at `/api/mcp` that serves the bundled demo dataset, and make every screen get its data through that server and say plainly where the data comes from.

## Output

Web app that is mobile responsive.

## Guardrails

- Read-only tools only: nothing that writes, sends, deletes or spends.
- No database and no login.
- Never create a variable whose name starts with `VITE_`.
- This server needs no API key.
- Keep the existing layout and styling, and keep every existing screen working.

## Context

### Audience

People who want to build healthy habits in terms of eating. People who want healthy food options rather than turning to fast food or unhealthy hawker options in Singapore.

### Environment

Built in Claude Code, versioned on GitHub, and hosted on Vercel.

### Resources

- **MCP endpoint:** <https://mcp.smithery.ai/emmalowzz>
- **Master prompt:** saved as `MCP_MASTERPROMPT.md` in the GitHub repository <https://github.com/emmalowzz/healthyhabitsgrp6.git>

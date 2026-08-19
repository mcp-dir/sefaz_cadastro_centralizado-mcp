# Instalação detalhada

SEFAZ: Cadastro Centralizado de Contribuinte (CCC) é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_sefaz_cadastro_centralizado`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_sefaz_cadastro_centralizado` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_sefaz_cadastro_centralizado` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_sefaz_cadastro_centralizado` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.sefaz_cadastro_centralizado` (ou `servers.sefaz_cadastro_centralizado` no VS Code) do config do cliente e reinicie.

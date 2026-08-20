# Instalação detalhada

Conselho Federal de Contabilidade: Cadastro de Profissionais e Empresas é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_cfc_cadastro`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_cfc_cadastro` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_cfc_cadastro` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_cfc_cadastro` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.cfc_cadastro` (ou `servers.cfc_cadastro` no VS Code) do config do cliente e reinicie.

# ADR-004 — Backend Authority

Status: Accepted

## Decision
Backend é a autoridade para autenticação de regras comerciais, expiração, permissões, billing e ações públicas sensíveis.

## Consequences
Mobile pode operar offline, mas regras críticas nunca dependem apenas do cliente.

# ADR-002 — Offline First

Status: Accepted

## Context
Profissionais podem precisar de trabalhar sem Internet.

## Decision
SQLite local + sync queue + Fastify/PostgreSQL.

## Consequences
Melhor experiência offline, com maior complexidade de sincronização.

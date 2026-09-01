# Architecture SDD

## Monorepo
pnpm workspaces.

## Applications
- apps/mobile
- apps/api

## Packages
- packages/shared
- packages/validation
- packages/config

## Infrastructure
- Supabase/PostgreSQL
- Supabase Auth
- Supabase Storage

## Boundaries
Mobile → Fastify → PostgreSQL/Supabase.

O backend é a fronteira das regras comerciais e integrações privadas.

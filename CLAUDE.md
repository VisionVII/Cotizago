# CotizaGo — Claude Code Entry Point

## Regra principal

Antes de qualquer alteração:

1. Ler este ficheiro.
2. Ler `MASTER_CHECKLIST.md`.
3. Ler os SDDs relevantes.
4. Ler ADRs relevantes.
5. Inspecionar o estado real do repositório.
6. Definir a fase e tarefa atual.
7. Implementar apenas o escopo necessário.
8. Executar typecheck, lint e testes aplicáveis.
9. Executar auditorias aplicáveis.
10. Atualizar checklist, checkpoint e documentação.

Uma tarefa só recebe `[x]` depois de validada.

## Fonte de verdade

- Produto/arquitetura: `.sdd/`
- Decisões: `.engineering/architecture/decisions/`
- Contratos: `.engineering/contracts/`
- Auditorias: `.engineering/audits/`
- Estado de execução: `.engineering/checkpoints/`
- Progresso: `MASTER_CHECKLIST.md`
- Instruções completas: `docs/MASTER_ENGINEERING_PROMPT.md`

## Princípios

- TypeScript strict.
- Dinheiro em cêntimos inteiros.
- UUID v4.
- Offline-first no mobile.
- Backend como autoridade para regras comerciais.
- Isolamento por `company_id`.
- Service-role key apenas no backend.
- Sem complexidade prematura.
- Sem funcionalidades fora do MVP sem registo explícito.

# Zelador Digital

[![CI](https://github.com/GuilhermeCostaProenca/digital-footprint-guardian/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GuilhermeCostaProenca/digital-footprint-guardian/actions/workflows/ci.yml)

Digital product repository focused on a real market pain with portfolio-grade execution.

## Proposal
**Gerenciador da pegada online do usuario** for Usuarios com muitas contas online e foco em privacidade.

## Problem
Falta visibilidade de onde dados pessoais estao cadastrados e risco continuo por contas abandonadas.

## Target audience
Usuarios com muitas contas online e foco em privacidade

## Suggested stack
Next.js, Node API, PostgreSQL, integracoes de email e breach monitoring

## Initial MVP
- Mapeamento de contas a partir do email principal
- Painel de assinaturas e contas inativas
- Alertas de vazamentos e recomendacoes de acao
- Fluxo guiado para limpeza e encerramento de contas

## Base structure
- `README.md`: product vision and execution strategy
- `PRD.md`: functional scope and product rules
- `ARCHITECTURE.md`: initial technical design
- `BACKLOG.md`: prioritized execution backlog
- `PLAN.md`: phase-by-phase execution plan
- `.github/workflows/ci.yml`: validation pipeline

## How to start
1. Refine PRD with user and scope.
2. Confirm architecture and final stack.
3. Build core flow end-to-end.
4. Add CI, tests and operational docs.

## Main risks
Dependencia de provedores externos e confianca do usuario


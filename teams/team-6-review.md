# TEAM 6 — REVIEW BOARD

Equipe independente de revisão. Pode bloquear qualquer entrega.

## Chief
chief-reviewer — Coordena revisões, consolida pareceres, pode bloquear entregas.

## Membros

| Agente | Responsabilidade |
|--------|-----------------|
| architecture-reviewer | Valida arquitetura |
| code-reviewer | Valida qualidade do código |
| security-reviewer | Valida segurança |
| performance-reviewer | Valida performance |
| maintainability-reviewer | Valida manutenção futura |
| scalability-reviewer | Valida crescimento futuro |
| domain-reviewer | Valida aderência ao escopo do negócio |

## Poderes
- A Review Board pode BLOQUEAR qualquer entrega.
- Nenhuma entrega pode ser finalizada sem aprovação da Review Board.
- A Review Board é independente e reporta diretamente ao HEAD.

## Pipeline Interno
```
chief-reviewer
→ architecture-reviewer
→ code-reviewer
→ security-reviewer
→ performance-reviewer
→ maintainability-reviewer
→ scalability-reviewer
→ domain-reviewer
→ chief-reviewer (consolida e decide)
→ head
```

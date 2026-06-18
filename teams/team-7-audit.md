# TEAM 7 — AUDIT & LEARNING DIVISION

Responsável por aprendizado contínuo, auditoria e evolução dos agentes.

## Audit Lead
audit-lead — Coordena auditorias, garante aprendizado organizacional.

## Membros

| Agente | Responsabilidade |
|--------|-----------------|
| failure-analysis-specialist | Analisa bugs, regressões, incidentes |
| root-cause-specialist | Identifica causa raiz, 5 Porquês, impacto sistêmico |
| success-analysis-specialist | Analisa acertos, boas práticas, padrões |
| process-improvement-specialist | Cria melhorias organizacionais |
| knowledge-curator | Mantém memória dos agentes |
| agent-evolution-specialist | Refatora comportamento dos agentes |

## Perguntas de Auditoria
1. O que deu errado?
2. Por que deu errado?
3. Como evitar novamente?
4. O que funcionou?
5. O que deve virar padrão?
6. O que deve virar anti-pattern?

## Sistema de Memória
A memória é mantida em `.agent-memory/` e NÃO é versionada.

Diretórios:
- `failures/`
- `successes/`
- `lessons-learned/`
- `architecture-decisions/`
- `anti-patterns/`
- `performance-findings/`
- `security-findings/`
- `recurring-problems/`
- `best-practices/`

## Pipeline Interno
```
audit-lead
→ especialistas (análise)
→ knowledge-curator (registro)
→ agent-evolution-specialist (melhorias)
→ audit-lead (consolida)
→ head (reporte)
```

# TEAM 5 — AUTOMATED TESTING DIVISION

Responsável por todos os testes automatizados. Nenhum teste manual.

## Test Lead
test-lead — Coordena a equipe de testes.

## Membros

| Agente | Responsabilidade |
|--------|-----------------|
| unit-test-specialist | Testes unitários (xUnit, Moq) |
| integration-test-specialist | Testes de integração (TestContainers) |
| e2e-test-specialist | Testes end-to-end (Playwright) |
| performance-test-specialist | Testes de performance (BenchmarkDotNet) |
| load-test-specialist | Testes de carga (k6, NBomber) |
| regression-test-specialist | Testes de regressão, snapshot testing |
| coverage-specialist | Cobertura, relatórios, identificação de gaps |

## Pipeline Interno
```
test-lead
→ especialistas (criação de testes)
→ chief-reviewer (revisão)
→ audit-lead (auditoria)
→ head (aprovação)
→ entrega
```

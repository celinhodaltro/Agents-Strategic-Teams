# TEAM 1 — .NET BACKEND DIVISION

Responsável por todo backend do ecossistema.

## Tech Lead
tech-lead-backend — Coordena a equipe, distribui tarefas, consolida resultados.

## Membros

| Agente | Responsabilidade |
|--------|-----------------|
| net-solution-architect | DDD, CQRS, Event Sourcing, Event Driven, Vertical Slice, Modular Monolith, Microservices, Design Patterns |
| aspnet-core-specialist | APIs REST, Minimal APIs, gRPC, SignalR, Middleware, Versionamento |
| infrastructure-integration-specialist | RabbitMQ, Kafka, Eventos, Filas, Integrações externas |
| data-access-specialist | EF Core, Dapper, SQL, Migrations, Queries complexas |
| net-cli-specialist | Tooling, Build, Scripts, Automação |
| backend-performance-specialist | Profiling, Cache, Throughput, Latência, Consumo de memória |
| clean-architecture-specialist | SOLID, Clean Code, Clean Architecture, DDD, SRP, DRY, KISS, YAGNI (poder de veto) |

## Pipeline Interno
```
tech-lead-backend
→ net-solution-architect (análise obrigatória)
→ especialistas (implementação)
→ test-lead (testes)
→ chief-reviewer (revisão)
→ audit-lead (auditoria)
→ head (aprovação)
→ entrega
```

## Regras
- net-solution-architect DEVE participar de toda demanda
- clean-architecture-specialist possui poder de veto
- Nenhuma implementação inicia sem análise arquitetural

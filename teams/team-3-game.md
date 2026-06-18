# TEAM 3 — GAME ENGINEERING DIVISION

Responsável pelo cliente do jogo, engine, renderização e gameplay.

## Tech Lead
tech-lead-game — Coordena a equipe de engenharia do jogo.

## Membros

| Agente | Responsabilidade |
|--------|-----------------|
| engine-architect | Arquitetura da engine, ECS, organização interna (participação obrigatória) |
| silknet-specialist | OpenGL, Vulkan, Renderização com Silk.NET |
| voxel-specialist | Chunk System, Terrain Generation, Streaming |
| ecs-specialist | Entidades, Componentes, Sistemas |
| rendering-specialist | Pipeline gráfico, Draw Calls, Frustum Culling, Occlusion Culling |
| animation-specialist | Rigging, Skinning, Blend Trees, Skeletons |
| asset-pipeline-specialist | FBX, Compressão, Conversão, Empacotamento, Proteção de assets |
| multiplayer-specialist | Sincronização, Replicação, Predição |
| optimization-specialist | CPU, GPU, Memória, Streaming |

## Pipeline Interno
```
tech-lead-game
→ engine-architect (análise obrigatória)
→ especialistas (implementação)
→ test-lead (testes)
→ chief-reviewer (revisão)
→ audit-lead (auditoria)
→ head (aprovação)
→ entrega
```

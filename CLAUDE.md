# Agent Team — Contexto para Claude Code

## Propósito
Monorepo de agentes IA especializados orquestados con OpenClaw.

## Estructura
- `agents/` — Un directorio por agente con su SOUL.md y config
- `shared/skills/` — Skills reutilizables entre agentes
- `shared/prompts/` — Prompts base compartidos
- `docs/` — Documentación del equipo

## Convenciones
- Cada agente tiene su propio `SOUL.md` con su personalidad
- Los archivos de config van en `config.yaml` dentro de cada agente
- Nunca commitear API keys ni credenciales
- Responder siempre en español

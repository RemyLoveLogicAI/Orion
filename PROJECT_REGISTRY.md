# Orion Project Registry

Synced from the grok.me portfolio on August 26, 2026. This registry records the portfolio systems and their relationship to Orion. Descriptions are intentionally concise and capability-oriented; implementation details should be linked as each system is integrated.

| Project / system | Role | Orion relationship |
|---|---|---|
| OmniAgents | Multi-agent orchestration and coordination layer | Candidate upstream orchestration surface for Orion workflows |
| Effort Governor | Effort, scope, and execution-budget governance | Policy/control layer for prioritizing Orion work |
| poke-mesh | Mesh/connectivity layer for coordinating Poke-connected agents and services | Integration fabric for Orion participants |
| secretforge-ai | AI-assisted secret discovery and management | Security and credential-management dependency |
| RemyBot | Remy-facing assistant/bot runtime | User-facing execution surface for Orion capabilities |
| Lior | Named assistant/system in the portfolio | Companion agent or service; integration boundary to be defined |
| Hermes Council / PAI | Council-style deliberation and personal-AI coordination system | Decision and planning layer for Orion |
| Core Capability Ledger | Inventory and accounting of capabilities, tools, and system maturity | Source of truth for Orion capability coverage |

## Sync notes

- Source portfolio: grok.me portfolio named in the sync request.
- Repository: `RemyLoveLogicAI/Orion`.
- This registry is a map of systems, not a claim that all systems are vendored into this repository.
- Secrets, tokens, and private credentials are deliberately excluded.
- See `docs/projects/` for one-page records and integration boundaries.

# Cortex

Meta-agentic bootstrap kit. Self-aware system that builds itself to build your project.

## Usage

**Option A — GitHub Template (recommended)**
1. Click "Use this template" on [GitHub](https://github.com/cemphlvn/bootstrap)
2. Clone your new repo
3. `claude` → `/start`

**Option B — Manual**
```bash
git clone https://github.com/cemphlvn/bootstrap my-project
cd my-project
rm -rf .git && git init
claude
> /start
```

## Architecture

```
CLAUDE.md                    ← Orchestrator (root consciousness)
    │
    ├── plans (skill)
    ├── coordinates (skill)
    ├── criticizes (skill)
    │
    └── delegates to:
        │
        ├── meta-agent       ← Structure (bootstrap, scaffolding)
        └── [domain]-agents  ← Domain work (created at bootstrap)
```

## The Orchestrator

CLAUDE.md is not configuration. It's **consciousness**.

- **Plans** before complex work
- **Coordinates** multi-agent tasks
- **Delegates** to the right agent
- **Criticizes** after significant work
- **Reflects** on itself (observer observing the observer)

## The Loop

```
OBSERVE → ORIENT → DECIDE → ACT → REFLECT
    ↑                                  │
    └──────────────────────────────────┘
```

## Structure

```
project/
├── CLAUDE.md                 # Orchestrator
├── .claude/
│   ├── agents/
│   │   └── meta-agent.md     # structural agent
│   ├── skills/
│   │   ├── cortex/           # system principles
│   │   ├── planning/         # decomposition
│   │   ├── coordination/     # multi-agent
│   │   └── criticism/        # evaluation
│   ├── commands/
│   ├── templates/
│   ├── context.md            # project ontology
│   └── state.jsonl           # persistent memory
└── src/                      # actual project
```

## Principles

1. **Structure = Ontology** — Filesystem is knowledge graph
2. **Observer Observes Itself** — Meta-cognitive awareness
3. **Persistent State** — state.jsonl survives sessions
4. **Delegate, Don't Do** — Orchestrator thinks, agents act

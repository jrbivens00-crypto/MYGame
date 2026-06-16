# Codex — CLAUDE.md

## Project Overview
**Codex** is a first-person shooter MMORPG built in Unreal Engine, drawing heavy inspiration from Destiny 2. Players explore, shoot, loot, and progress through a shared world with RPG depth layered on top of tight FPS gunplay.

## Repository Structure
```
MYGame/
└── Codex/          # Unreal Engine 5 project
    ├── Codex.uproject
    ├── Config/     # Engine/game configuration
    └── Content/    # All UE assets (.uasset, .umap, .uproject)
```

## Tech Stack
- **Engine:** Unreal Engine 5
- **Language:** Blueprints (primary), C++ (as needed)
- **Version Control:** Git + GitHub (`github.com/jrbivens00-crypto/MYGame`)
- **Branch:** `master`

## Game Design Reference
Think Destiny 2:
- First-person shooter combat with abilities
- Shared-world multiplayer (MMO scale)
- Loot-driven progression (weapons, armor, power level)
- Missions, strikes, raids, PvP modes
- Persistent character with class identity

## Current Focus
Building the foundational project structure — establishing the core systems, folder organization, and architecture before implementing gameplay features.

## Development Context
- **Solo developer** — one person doing everything
- **Primary machine:** Windows (this machine, `C:\Users\jjbiv\MYGame`)
- **Secondary machine:** Mac (cloned repo at `~/Projects/MYGame`)
- **MCP:** GitHub MCP connected on Windows

## Priorities When Helping
1. Suggest Unreal Engine 5 best practices (not UE4 patterns)
2. Favor Blueprints over C++ unless performance demands it
3. Keep scope realistic for a solo dev — modular, iterative builds
4. Call out when something is Destiny 2-specific vs. general FPSMMO design
5. Always consider multiplayer implications early (networking, replication)

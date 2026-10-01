# Corner Coach Brain (Portable APC OKF)

The shared craft layer for RapportScore's agentic performance coach (APC): the knowledge an AI coach loads to coach communication skills on top of a user's own RapportScore measurement data.

This repository is **knowledge only**. It contains no RapportScore product code, no MCP server code, no API keys, and no customer data. Every file is Markdown.

## Start here

1. **`APC-SYSTEM-PROMPT.md`**: the mandatory system prompt for any host running this coach.
2. **`Home.md`**: the index of every note in the brain.
3. Host wiring cheat-sheets at the root: `CHATGPT.md`, `GROK.md`, `FOR-CLAUDE.md`, `FOR-CURSOR.md`, `FOR-AGENTS.md`.

## What's inside

| Folder | Contents |
|---|---|
| `measurements/` | What each deterministic conversation measurement counts and how to read it |
| `dimensions/` | The 7 Rapport Dimensions |
| `belts/` | The belt progression system (white through black) |
| `coaching/` | Session types, drills, curriculum, coaching contracts |
| `faq/` | Getting started, privacy, recording, manager visibility |
| `safety/` | Coaching promises and support in hard moments |
| `research/` | Customer-safe research depth behind the measurements |

## Runtime contract

1. Load `APC-SYSTEM-PROMPT.md` as the host's system instructions.
2. Load this brain as knowledge.
3. Connect the user's own RapportScore identity (OAuth / MCP).
4. Coach with receipts from their sessions only; never invent personal scores.

Without step 3, the coach may teach craft but must not claim personal data.

## License

Copyright (c) Rapport Score LLC. All rights reserved. Published for transparency and for loading into coaching agents used with RapportScore; no license is granted to reuse this content in other products.

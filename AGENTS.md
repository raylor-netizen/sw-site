# Straightway Site — agent context

> **AI handoff doc** — read this first when working in `apps/sw-site/`.
> Network-wide rules: [`~/Straightway-Network/CODEX.md`](../../CODEX.md) · orchestration: [`AGENTS.md`](../../AGENTS.md) · change log: [`docs/APP-DOCS-CHANGELOG.md`](../../docs/APP-DOCS-CHANGELOG.md)

## What this app does

Static marketing website for Straightway Transportation (NEMT, NJ HQ, international chapters). Single-page HTML.

## Port & launchd

| | |
|---|---|
| **Port** | — (no HTTP server) |
| **launchd labels** | (none — CLI, library, or mobile client) |
| **sw group** | — |

## Entry point

`index.html`

## Data flow

**Reads from:**
- (none)

**Writes to:**
- (none)

## Commands

```bash
sw status
Open index.html in browser; deploy via external hosting
```

## Key files

- index.html

## Related apps

- (none)

## Rules for agents

- Nested .git repo — deploy separately.


# AI Value Migration Map

Interactive treemap for selecting AI roll-up verticals at Bobroff Capital.

**Live site:** https://lisaivanchikova.github.io/rollup-methodology/

## The formula

```
S_cell = V × C × A × B
```

Each cell on the map = (NAICS sub-sector × Workflow). Color = composite score `S`. Toggle the top layer to see V, C, A, B individually.

| Block | Meaning |
|---|---|
| **V** | Value Created — what AI dislodged per year ($/year normalized) |
| **C** | Capture Share — what we pocket (not upstream gatekeeper) |
| **A** | Adoption Speed — how fast the market accepts AI (1 / years to 50%) |
| **B** | Buyability — can we actually enter (TD, OW, PD, CFD) |

Multiplication, not summation. Any weak block zeroes the score.

## Why this map

A vertical isn't "good" or "bad" — a **cell (sub-sector × workflow)** is. Insurance has Hell-Yes doc parsing AND red relationship work, both true at once. The map shows where to focus AI playbook *after* acquiring an operator.

The methodology replaces 27 S16 criteria with 5 atomic inputs per cell (LR, ΔM, π_dist, π_moat, t_50, π_buy), tied to measurable sources: BLS QCEW, Karpathy.ai/jobs, Anthropic Economic Index, PitchBook, our internal P&L Before/After AI sheet.

## Versions

- **v3.0 (2026-05-23)** — current. Treemap + 5 layer views + methodology tab.
- v2.0 — Vertical Selection NAICS rubric with S1-S7 weighted criteria (superseded)
- v1.0 — S16-derived 13-criterion checklist (superseded)

Built 2026-05-23 by Lisa Ivanchikova.

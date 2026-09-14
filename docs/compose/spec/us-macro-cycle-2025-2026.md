---
feature: us-macro-cycle-2025-2026
status: designed
updated: 2026-09-13
branch: main
commits: # filled at delivery
---

# US Macro Cycle Research: CPI, Equities, and Fed Policy (2025–2026)

## Report

## [S1] Problem

An investor learning US markets needs a clear, multi-source picture of:

1. What recent US CPI looks like across the 2025–2026 cycle (level, direction, core vs headline, drivers).
2. How major US equity indices have performed and why.
3. Whether the Fed has been hiking, cutting, or on hold — and the market-implied path.
4. A causal synthesis: why CPI, equities, and Fed policy are moving together this way.

Audience: investment beginner seeking capital preservation/growth context, not a trading desk.

## [S2] Design

### Research window
- Full cycle view from roughly mid/late 2025 through September 2026.
- Latest available CPI print as of 2026-09-13 (likely July or August 2026 data).
- Latest FOMC decision and next scheduled meeting; market-implied rate path via CME FedWatch or equivalent.

### Topics to cover
| Topic | Required content |
| --- | --- |
| CPI | Latest headline & core YoY/MoM; trajectory since 2025; key drivers (shelter, goods, services, energy); Fed 2% target gap |
| Equities | S&P 500, Nasdaq Composite/100, Dow, Russell 2000 — YTD and cycle returns; drawdowns; leadership (mega-cap tech etc.) |
| Fed | Policy rate level; 2025–2026 cut/hike/hold sequence; SEP/dot-plot signals; next meeting expectations; balance sheet stance if material |
| Synthesis | Transmission: inflation → policy path → discount rates/earnings → index performance; risks to the view |

### Sources
Prioritize primary/authoritative sources, escalating only on failure:
1. BLS CPI releases and summaries
2. Federal Reserve statements, press conferences, SEP
3. CME FedWatch / fed funds futures
4. Major financial press (Reuters, Bloomberg, WSJ, CNBC, FT) for market levels and reaction
5. Index provider or exchange data where possible

Record source URLs and data-as-of dates in the note.

### Deliverables
1. `2026-09-13.md` in the Invest repo root (matching existing dated-note convention).
2. Chat analysis that summarizes the same findings with the causal “why”.

### Style
- Beginner-friendly prose; define non-obvious terms briefly.
- Chinese-capable audience but response language is en-US unless content is bilingual notes — keep the note in English with Chinese section headers optional to match repo style (repo notes mix Chinese headers and English terms).
- No investment advice or trade recommendations; analysis of what is happening and why.

## [S3] Out of Scope

- Portfolio construction or buy/sell recommendations for the user.
- Individual stock picks.
- Non-US inflation/central banks except where they materially explain US moves.
- High-frequency trading or intraday data.
- Updating prior notes or images.

## Tasks
- [ ] T1: Draft this spec — acceptance: sections S1–S3 and tasks defined (covers: S1)
- [ ] T2: Multi-source research on CPI, indices, and Fed path — acceptance: latest levels, cycle path, and primary-source citations captured (covers: S2)
- [ ] T3: Write `2026-09-13.md` and chat analysis with causal synthesis — acceptance: note exists, covers all three topics + why, cites sources with dates (covers: S2; depends: T2)
- [ ] T4: Verify figures against sources, review for contradictions, finalize spec status — acceptance: no unresolved factual conflicts; spec status delivered (covers: S2; depends: T3)

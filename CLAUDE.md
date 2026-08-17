# CLAUDE.md — Instructions for AI Collaboration

Context and conventions for Claude (or any AI) working in this repository.

## What this repo is

A personal long COVID research knowledge base and treatment-planning document. It is:
- Not a clinical practice guideline
- Not peer-reviewed
- A working synthesis of 2025–2026 literature and mechanistic reasoning
- Used to inform (not replace) medical decisions made with a real physician

## Reading order for context

When starting a new session, read in this order:
1. `README.md` — project overview
2. `docs/01-triad-model.md` — the unifying root-cause model
3. `docs/02-treatments.md` — evidence tiers for interventions
4. `personal/profile.md` — if the user is asking about their specific case (may be gitignored — check if present)
5. Whichever other doc is relevant to the current question

## Content principles

### When adding to `docs/`
- Cite primary literature (RCTs, systematic reviews, mechanism papers) — not blog posts
- Use the format: `[Descriptive Title](URL)` in `docs/sources.md`
- Prefer 2025–2026 evidence; older studies OK if landmark
- Note evidence tier (RCT, meta-analysis, case series, mechanism paper)
- Flag uncertainty — "modest evidence," "case reports only," "trial ongoing," etc.
- Stay within scope: mechanism, treatments, protocols, sources. Not clinical care.

### When adding to `personal/`
- This is personal medical planning — treat carefully
- Convert relative dates to absolute (e.g., "next month" → "2026-09")
- Update the action plan as new labs/results/decisions come in
- Never publish this externally without explicit instruction

### When updating existing content
- Preserve source citations
- Add new evidence to appropriate section — don't overwrite
- If a claim is now contradicted by new evidence, mark it: `~~old claim~~ (superseded by [new source] 2026)`
- Update `README.md` "Key findings" table when major new evidence lands

## Style conventions

- Markdown throughout
- Tables for comparative data (treatments, mechanisms, side effects)
- Short paragraphs, direct language
- Emojis sparingly and only for section markers when they aid scanning
- No purple prose — this is a working document, not a paper

## What NOT to do

- ❌ Do not give medical advice framed as certainty
- ❌ Do not invent citations — if a source can't be verified, don't cite it
- ❌ Do not commit `personal/` contents to git without asking
- ❌ Do not delete existing sources when adding new ones — accumulate the evidence base
- ❌ Do not restructure top-level layout without discussing first

## Useful searches when researching

Standard queries that surface the best long COVID literature (2025–2026):

- `long COVID [mechanism] 2026 clinical trial results`
- `[drug name] long COVID RCT`
- `PASC [symptom] treatment evidence`
- `RECOVER trial [name] results`
- `[mechanism] SARS-CoV-2 persistence`

Good source domains: `nature.com`, `thelancet.com`, `nejm.org`, `nih.gov`, `pnas.org`, `sciencedirect.com`, `pmc.ncbi.nlm.nih.gov`, `medrxiv.org`, `frontiersin.org`, `recovercovid.org`, `healthrising.org` (patient community synthesis), `rthm.com` (specialty LC clinic writeups).

Skeptical sources — cite carefully or avoid: general wellness blogs, supplement sellers, unclear methodology sites.

## User's specific case (if `personal/` present)

If `personal/profile.md` is readable in the current session, respect what's documented there:
- Phenotype classification (dopamine-deficit + vagal-autonomic, no PEM)
- Duration (LC since 2021)
- Interventions tried / not tried
- Contraindications / preferences

Ground personalized recommendations in `personal/profile.md`, not general LC advice.

## Update log

Add entries here when significant additions/corrections happen:

- **2026-08-17** — Initial synthesis: Triad model, treatment tiers, bupropion protocol, sources
- **2026-08-18** — Restructured as GitHub-ready project with docs/personal split

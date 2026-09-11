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
- **2026-08-18** — Added docs/04-unified-model.md: "The Stuck Sickness Program" — three-layer unified RCA (hardware → telemetry → state); explains symptom package via energy-budget triage, partial drug responses via latch/hysteresis, and derives the 4-phase permanent-exit blueprint
- **2026-08-20** — Added `mpb/` sub-project: androgenetic alopecia research + treatment plan. Includes `mpb/docs/07-5ari-neuro-overlap.md`, which governs sequencing between the 5-ARI change and bupropion — **do not start both in the same window**.
- **2026-09-07** — **2026 literature sweep.** Added `docs/02-treatments.md` Tier 5 with the year's new candidates + 15 sources. **Correction: BC-007 (rovunaptabin) FAILED** — no superiority over placebo (reCOVer Phase IIa, *eClinicalMedicine* 2025); the doc previously listed it as "Phase 2 ongoing." New: dopamine-targeted therapy (rasagiline + tyramine precursor, patent Jan 2026, no efficacy data — but the only candidate matching this case's dopaminergic phenotype), bezisterim/ADDRESS-LC (topline Sept 2026), baricitinib + semaglutide (RECOVER-TLC, results end-2026), oxaloacetate, HBOT (mixed: 40-session positive, 10-session HOT-LoCO negative), sipavibart, taVNS/COVIVA. **Framing: a 2026 SR finds no pharmacological therapy with consistent efficacy in adequately powered RCTs. There is no cure.**
- **2026-09-08** — **Mast-cell / gut sweep.** Added `docs/05-mast-cell-gut-protocol.md` (anatomy of the gut mast-cell→vagal-afferent reflex, evidence hierarchy, India drug/probiotic/test availability with prices, challenge-test design, sequencing with the 5-ARI window). **Corrections:** STIMULATE-ICP antihistamine arm = −1.5 FAS points, open-label, not sustained (was listed as plain "fatigue improvements"); COVIVA taVNS = **null**, as are 3 other controlled taVNS trials (non-drug section downgraded); LDN "52% response" traced to an open pilot — **no LDN RCT has reported**; Wong 2023 human serotonin finding contested/non-replicated; gut viral persistence documented to ~22–30 months only; **expired fish oil cannot form histamine** (refined oil, no histidine) — reframed as oxidised-lipid irritant. Added Tier 2 gut synbiotic (SIM01 RCT n=463) and a ranked "dopamine axis after bupropion palpitations" section (Bupron XL exists in India; guanfacine does not; topical finasteride 0.25% standalone does not). Executable phased plan prepended to `personal/action-plan.md`.

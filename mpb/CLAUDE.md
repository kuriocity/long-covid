# CLAUDE.md — Instructions for AI Collaboration (MPB sub-project)

Inherits the conventions of `../CLAUDE.md`. This file adds what's specific to the MPB project.

## What this repo is

A personal androgenetic alopecia (male pattern baldness) research and treatment-planning knowledge base. Sibling of the long COVID project in the parent directory. Not a clinical guideline, not peer-reviewed.

## Reading order for context

1. `README.md` — framing, structure, key evidence table
2. `context.md` — the current treatment stack (read this before answering any "should I…" question)
3. `docs/02-treatments.md` — evidence tiers
4. `personal/profile.md` — the user's specific case and history
5. `docs/07-5ari-neuro-overlap.md` — the 5-ARI / long COVID anhedonia confound, which governs drug choices here
6. Whichever other doc is relevant

## Hard content rules

- **Never call anything a cure.** MPB has no cure in 2026. Halt, partial regrowth, and surgical restoration are the available categories. Say which one an intervention belongs to.
- **Always state the evidence tier**: RCT / meta-analysis / open-label / case series / mechanism-only / marketing.
- **Never invent citations.** If it can't be verified, don't cite it.
- **Distinguish miniaturized from fibrosed follicles** when discussing regrowth potential. Regrowth claims apply only to the former.
- **Separate serum from scalp effects** for 5-ARIs and topicals — this is where most bad internet advice comes from.
- **Flag the 5-ARI neuropsychiatric question honestly.** The user tapered dutasteride in 2024 over anhedonia-like symptoms that are confounded with long COVID. Do not dismiss it as nocebo, and do not treat it as established causation. Both errors are costly here.
- **Treat frontal/temporal and vertex as separate questions.** Nearly all headline trial data is vertex data. Never quote a vertex effect size as if it applies to the temples.
- **Watch for reverse causation in self-reported asymmetry.** "The side I treated is thinner" almost always means "I treated the side that was already thinner." Ask for a pre-treatment baseline photo before entertaining a drug-harm explanation.
- **Adherence is the real bottleneck**, not drug selection. When proposing anything, ask whether it survives contact with a bad week. Prefer once-daily oral over twice-daily topical when efficacy is comparable.
- Cite primary literature; add to `docs/sources.md` as `[Descriptive Title](URL)`.
- Prefer 2024–2026 evidence; older is fine if landmark (e.g. the 2019 duta-vs-fin meta-analysis).

## When updating

- Convert relative dates to absolute (`next month` → `2026-09`).
- Superseded claims get marked, not deleted: `~~old claim~~ (superseded by [source] 2026)`.
- Log every treatment change in `status.md` with before/after and side effects.
- Update `context.md` whenever the stack changes.
- Update the `README.md` key-evidence table when major new evidence lands.

## Cost assumptions

Costs are given in **INR** (India market) with USD where the product is import/compounded-only. Flag when a price is a clinic-marketing figure rather than a surveyed one.

## What NOT to do

- Do not give medical advice framed as certainty
- Do not recommend compounded topicals without noting the 2025 FDA concern about unvalidated compounded finasteride formulations
- Do not recommend starting or stopping a 5-ARI and a psychoactive drug (e.g. bupropion, from the LC project) in the same window — it destroys attribution
- Do not restructure the top-level layout without discussing first

## Update log

- **2026-08-20** — Project created. Mechanism, treatment tiers, 5-ARI guide, topicals/adjuncts, procedures, 2026 pipeline, 5-ARI/LC neuro overlap, sources, personal profile + action plan.
- **2026-08-24** — **Correction.** Comparative cohort/pharmacovigilance data does not support "dutasteride is worse for mood than finasteride" and may show the reverse (French nationwide cohort; caveats: BPH, 50+, finasteride 5 mg, observational). The oral duta → oral fin step-down in docs 03/07 was downgraded; **topical finasteride 0.25% is now the recommended step-down**, since only a route/dose change reduces exposure. Aligns with the standing "topical/non-hormonal only" decision in the LC `context.md`.
- **2026-08-20** — Added `docs/08-frontal-temples.md`. Frontal/temporal scalp treated as a separate problem: dutasteride's frontal subgroup superiority (which **complicates** the dutasteride→finasteride step-down recommended in doc 07), local dutasteride delivery as a possible way to have both, the mature-hairline / traction / FFA differential, and the reverse-causation trap behind unilateral-application asymmetry claims.
- **2026-09-08** — **India availability check (from the LC sweep).** Standalone **topical finasteride 0.25% is not marketed in India**; only 0.1% finasteride + minoxidil combinations exist (Morr-F 5%/10%, Hair 4U F, Tugain Men, Actihair 5F). Oral minoxidil (Lonitab 2.5 mg ₹18.7, 5 mg ₹45) and oral finasteride are available. Doc 07 Option 2 therefore needs an India-feasible route (verified combo, import, or compounding with the FDA caveat) before the step-down window opens (LC plan: ~week 6). Noted in `docs/07-5ari-neuro-overlap.md`.

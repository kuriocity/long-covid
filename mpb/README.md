# MPB Research Project — Androgenetic Alopecia

A personal research and treatment-planning knowledge base for **male pattern baldness** (androgenetic alopecia, AGA), built from the 2019–2026 literature: RCTs, meta-analyses, pharmacokinetic data, and the 2026 drug pipeline.

Sister project to `../` (long COVID). The two overlap more than they look like they should — see [docs/07-5ari-neuro-overlap.md](docs/07-5ari-neuro-overlap.md).

## The honest framing

**There is no cure for MPB in 2026.** Nothing available today reverses the genetic program or regenerates a follicle that has fully fibrosed. What *is* achievable, and what this project plans for:

| Goal | Achievable? | With what |
|---|---|---|
| **Halt progression** | Yes, reliably | 5-ARI (finasteride/dutasteride), for as long as you take it |
| **Partial regrowth** | Yes, 6–18 months | 5-ARI + minoxidil + microneedling — recovers miniaturized (not dead) follicles |
| **Cosmetic restoration of bald scalp** | Yes | Hair transplant — moves follicles, doesn't create them |
| **True follicle neogenesis / cure** | Not yet | Pipeline only (PP405, GT20029) — realistically 2029–2031 |
| **Stop treatment and keep the hair** | No | Discontinuation → loss of all gains within 6–12 months |

So "cure steps" in this repo means: **halt → regrow what's recoverable → restore what isn't → hold it, at the lowest side-effect cost.** That's the whole game.

## What this is NOT

- Medical advice
- A substitute for a dermatologist / trichologist
- Peer-reviewed

Educational and personal-planning only. Confirm every drug decision with a physician.

---

## Structure

```
mpb/
├── README.md                      ← You are here
├── CLAUDE.md                      ← Instructions for AI collaboration
├── context.md                     ← Current stack at a glance
├── status.md                      ← Dated log of changes + photo checkpoints
├── docs/
│   ├── 01-mechanism.md            ← Why hair is lost: DHT, AR, miniaturization, genetics
│   ├── 02-treatments.md           ← Every intervention, ranked by evidence tier
│   ├── 03-5ari-guide.md           ← Finasteride vs dutasteride: dosing, PK, side effects
│   ├── 04-topicals-adjuncts.md    ← Minoxidil, tretinoin, ketoconazole, microneedling
│   ├── 05-procedures.md           ← PRP, LLLT, transplant planning + India costs
│   ├── 06-pipeline.md             ← 2026 pipeline and realistic timelines
│   ├── 07-5ari-neuro-overlap.md   ← 5-ARI neurosteroid effects vs long COVID anhedonia
│   ├── 08-frontal-temples.md      ← Temples/frontal scalp: separate biology, separate plan
│   └── sources.md                 ← Curated primary literature
└── personal/                      ← Personal application
    ├── profile.md                 ← My case, history, what's been tried
    └── action-plan.md             ← The actual sequenced plan
```

## Reading order

1. **[docs/02-treatments.md](docs/02-treatments.md)** — what works, ranked. Start here if you want the answer.
2. **[docs/01-mechanism.md](docs/01-mechanism.md)** — why those things work.
3. **[docs/03-5ari-guide.md](docs/03-5ari-guide.md)** — the one decision that matters most.
4. **[docs/07-5ari-neuro-overlap.md](docs/07-5ari-neuro-overlap.md)** — the confound specific to my case.
5. **[docs/08-frontal-temples.md](docs/08-frontal-temples.md)** — why the temples need their own plan.
6. **[personal/action-plan.md](personal/action-plan.md)** — the sequenced steps.

---

## Core model (one paragraph)

MPB is not a disease of the scalp — it's a **genetically programmed, androgen-driven change in follicle behavior**. In genetically susceptible follicles (polygenic, with a major X-linked *AR* locus — hence the father/grandfather pattern), 5-alpha-reductase converts testosterone to DHT locally in the dermal papilla. DHT binds the androgen receptor and reprograms the follicle to shorten anagen (growth) and lengthen telogen (rest) with each cycle. Each cycle produces a thinner, shorter, less pigmented hair — **miniaturization** — until the follicle produces only invisible vellus hair and eventually fibroses. The critical implication: **miniaturized follicles are recoverable; fibrosed ones are not.** Everything in the treatment plan is a race to suppress the androgen signal before more follicles cross that line.

## Key evidence compiled here

| Finding | Source |
|---|---|
| Dutasteride 0.5 mg/day = most effective monotherapy for male AGA | Network meta-analysis, 2025 |
| Dutasteride suppresses serum DHT ~90–98% vs finasteride ~71% | SR/MA, Clin Interv Aging 2019 |
| Dutasteride terminal half-life ~5 weeks → intermittent dosing viable | FDA Avodart label; ISHRS |
| Thrice-weekly dutasteride ≈ daily finasteride 1 mg on hair count | Pilot RCT, JAAD Int 2025 |
| Missed 5-ARI doses cause minimal DHT rebound | Urology Times / PK analysis |
| Topical finasteride 0.25%: similar efficacy, serum DHT −34.5% vs −55.6% oral | Phase III RCT, 2021 |
| Microneedling + minoxidil > minoxidil alone (SMD 1.32) | SR/MA of 12 RCTs, Arch Dermatol Res 2025 |
| Tretinoin raises follicular SULT1A1 1.8×; converts 43% of minoxidil non-responders | Sharma, Dermatol Ther 2019 |
| Low-dose oral minoxidil 1.25–5 mg effective; hypertrichosis 24% | Expert consensus + SR 2024–2025 |
| Activated PRP increases hair density at 3 and 6 months | SR/MA 43 RCTs, Dermatol Ther 2025 |
| EMA confirmed finasteride–suicidal ideation association | EMA, 2025 |
| Clascoterone 5% topical: FDA submission 2026, approval ~2027 | Pipeline tracking 2026 |
| Dutasteride beats finasteride at the **frontal** scalp too (MD 0.63, p=0.01) | Regional subgroups, SR/MA 2019 |
| AGA asymmetry is baseline: 77% of **untreated** men lose more on the right | Observational study, n=100 |
| Topical/intralesional dutasteride: Phase II RCT + SR/MA of small studies | 2024–2025 |
| GT20029 (topical AR PROTAC degrader) positive Phase 2 | J Dermatolog Treat, Dec 2025 |

---

*Living document. Last updated: 2026-08-20.*

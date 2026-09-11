# Long COVID Research Project

A personal research and treatment-planning knowledge base for long COVID (Post-Acute Sequelae of SARS-CoV-2 / PASC), built from 2025–2026 clinical literature, RCT results, and specialist protocols.

## What this is

A structured, source-linked synthesis of the current state of long COVID science — organized around:

1. **A unified root-cause model** (the "Damaged Triad" hypothesis: gut, endothelium, vagus nerve as a self-reinforcing loop)
2. **Treatment options** by evidence tier (RCTs, case series, experimental)
3. **Practical protocols** for specific drugs (e.g., bupropion) and lifestyle interventions
4. **Curated primary sources** organized by topic

Built collaboratively with Claude (Anthropic) using research and reasoning across the 2025–2026 literature.

## What this is NOT

- ❌ Medical advice
- ❌ A substitute for a physician
- ❌ A peer-reviewed publication
- ❌ Guaranteed accurate — this is a working understanding subject to update as new evidence emerges

**All content is for educational/personal-planning purposes only. Consult a qualified physician before making any medical decisions.**

---

## Structure

```
long_covid/
├── README.md                  ← You are here
├── CLAUDE.md                  ← Instructions for AI collaboration
├── LICENSE                    ← MIT
├── .gitignore                 ← Personal notes excluded by default
├── docs/                      ← Public research content
│   ├── 01-triad-model.md      ← Root-cause hypothesis (hardware layer)
│   ├── 02-treatments.md       ← Treatment evidence tiers
│   ├── 03-bupropion-guide.md  ← Bupropion practical guide
│   ├── 04-unified-model.md    ← The Stuck Sickness Program (full unified RCA)
│   ├── 05-mast-cell-gut-protocol.md ← Food-reactive / mast-cell phenotype: anatomy, drugs (India), tests
│   └── sources.md             ← Curated references
└── personal/                  ← Personal application (gitignored)
    ├── README.md              ← Personal entry point
    ├── profile.md             ← Personal symptom profile
    └── action-plan.md         ← Personal 90-day plan
```

## Reading order

New readers should go:

1. **[docs/04-unified-model.md](docs/04-unified-model.md)** — The full unified RCA (start here)
2. **[docs/01-triad-model.md](docs/01-triad-model.md)** — The hardware layer (which tissues and why)
3. **[docs/02-treatments.md](docs/02-treatments.md)** — What actually works and doesn't
4. **[docs/03-bupropion-guide.md](docs/03-bupropion-guide.md)** — Deep-dive on one high-relevance drug
5. **[docs/05-mast-cell-gut-protocol.md](docs/05-mast-cell-gut-protocol.md)** — The gut mast-cell / vagal-afferent phenotype and its protocol
5. **[docs/sources.md](docs/sources.md)** — Primary literature

---

## Core hypothesis (one paragraph)

Long COVID is a **self-sustaining inflammatory loop between the gut epithelium, vascular endothelium, and vagus nerve** — three ACE2-receptor-rich tissues SARS-CoV-2 preferentially damages. Once damaged, each leg feeds injury to the other two, forming a positive-feedback cycle that continues long after the acute virus is cleared. Every observed long COVID phenomenon — microclots, neuroinflammation, mitochondrial dysfunction, serotonin depletion, dopamine loss, HPA flattening, POTS, autoantibodies, EBV reactivation, PEM — is downstream of this loop. **Full recovery requires breaking the loop at multiple points simultaneously**, which explains why single-drug trials keep failing while multi-modal protocols at LC clinics succeed.

See [docs/01-triad-model.md](docs/01-triad-model.md) for the full model, mapped observations, and mechanistic evidence.

---

## Key 2025–2026 findings compiled here

| Finding | Source |
|---|---|
| Fluvoxamine reduces LC fatigue significantly (RCT) | REVIVE trial, Annals Int Med March 2026 |
| Dopamine terminal density loss in striatum documented | 2026 Nature-published imaging study |
| Fibrinaloid microclots — 4 distinct subtypes identified | Pretorius group, PolyBio Symposium 2026 |
| Nicotinamide Riboside modest fatigue benefit (RCT) | Lancet eClinicalMedicine 2025 |
| ~~Vagus nerve stimulation improves autonomic + fatigue~~ **taVNS: no benefit over sham in 4 controlled trials** | COVIVA, *Neurol Ther* 2026 (n=45) + Percin 2025, Vienna 2025, Mayo nVNS |
| Gut viral RNA/antigen persistence documented to ~22–30 months; **nothing at 4–5 years**; blood antigen does not track symptoms | Peluso 2024 *Sci Transl Med*; Hany 2024; Mateu 2026 |
| Metformin does NOT treat existing LC | REVIVE trial 2026 |
| Extended Paxlovid does NOT treat LC | RECOVER-VITAL 2025 |
| Antihistamine (H1+H2): **small (−1.5 FAS points), transient** fatigue benefit in unselected LC; food-reactive subgroup untested | STIMULATE-ICP, Wall 2026, *Lancet Infect Dis* (n=778, open-label) |
| **Bifidobacterium synbiotic (SIM01) ~doubles odds of improvement** in fatigue, memory, concentration, GI symptoms | Lau 2024, *Lancet Infect Dis* (RCT, n=463) |
| Gut mast-cell activation + persistent viral protein in ileal biopsies 15–22 months post-infection | Augustin 2026, *Mucosal Immunol* |
| Stellate ganglion block — 56% improved in largest series (n=102), durable in ~1/3 of responders, 25% transient AEs; sham RCTs started 2026 | Chiang 2025 *Cureus*; Peddireddy 2026 SR; NCT07468604 |

---

## Contributing

This is a personal research project. If you're another long COVID researcher, patient, or clinician who wants to suggest additions/corrections:

- Open an issue with the specific citation
- Reference primary literature (RCTs, meta-analyses, mechanism papers) rather than blog posts where possible
- Flag anything that turned out to be wrong so I can update

## License

MIT — free to use, modify, redistribute with attribution. See [LICENSE](LICENSE).

## Acknowledgments

- **NIH RECOVER Initiative** for the trial infrastructure
- **Patient-Led Research Collaborative** for pushing the field forward
- **Berlin Cures, Yale (Arnsten group), Pretorius group, RTHM clinic** for mechanism + treatment research
- **Anthropic / Claude** for research assistance in compiling this synthesis

---

*This is a living document. Last updated: 2026-08-18.*

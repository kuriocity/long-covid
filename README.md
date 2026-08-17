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
│   ├── 01-triad-model.md      ← Root-cause hypothesis
│   ├── 02-treatments.md       ← Treatment evidence tiers
│   ├── 03-bupropion-guide.md  ← Bupropion practical guide
│   └── sources.md             ← Curated references
└── personal/                  ← Personal application (gitignored)
    ├── README.md              ← Personal entry point
    ├── profile.md             ← Personal symptom profile
    └── action-plan.md         ← Personal 90-day plan
```

## Reading order

New readers should go:

1. **[docs/01-triad-model.md](docs/01-triad-model.md)** — Start here for the mental model
2. **[docs/02-treatments.md](docs/02-treatments.md)** — What actually works and doesn't
3. **[docs/03-bupropion-guide.md](docs/03-bupropion-guide.md)** — Deep-dive on one high-relevance drug
4. **[docs/sources.md](docs/sources.md)** — Primary literature

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
| Vagus nerve stimulation improves autonomic + fatigue | Italian VNS trial 2025 |
| Long COVID viral persistence in gut 12+ months | Multiple 2025 biopsy studies |
| Metformin does NOT treat existing LC | REVIVE trial 2026 |
| Extended Paxlovid does NOT treat LC | RECOVER-VITAL 2025 |
| Antihistamine (H1+H2) improves LC fatigue | STIMULATE-ICP, Lancet Infect Dis 2026 |
| Stellate ganglion block — dramatic case recoveries | Multiple case series, RECOVER-TLC ongoing |

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

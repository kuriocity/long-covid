# 07 — The 5-ARI / Long COVID Overlap

**Why this document exists:** the symptoms attributed to 5-alpha-reductase inhibitors and the symptoms of the dopaminergic long COVID phenotype are **substantially the same symptoms**. Anyone treating both conditions at once is running two interventions on one circuit with no way to attribute the result — unless the sequencing is designed deliberately. This document designs it.

Read alongside `../personal/profile.md` (MPB case) and `../../personal/profile.md` (the long COVID phenotype).

---

## The symptom collision

| Symptom | 5-ARI / post-finasteride reports | LC dopaminergic phenotype |
|---|---|---|
| Anhedonia | ✅ (including specifically **sexual** anhedonia) | ✅ (core feature) |
| Fatigue | ✅ | ✅ (core feature) |
| Emotional blunting / flat affect | ✅ | ✅ |
| Low motivation / drive | ✅ | ✅ (core feature) |
| Cognitive impairment / brain fog | ✅ | ✅ |
| Depressed mood | ✅ (EMA-confirmed signal for suicidal ideation, 2025) | ✅ |
| Low libido | ✅ (the hallmark) | Possible, secondary |
| Erectile dysfunction | ✅ | Uncommon |
| Genital numbness / sensory change | ✅ (distinctive) | ❌ |
| Anxiety, insomnia | ✅ | Variable |
| **Hypersomnia** (excess sleep, always sleepy) | Less characteristic | ✅ (documented LC entity) |
| Orthostatic / autonomic symptoms | ❌ | ✅ |
| PEM (post-exertional malaise) | ❌ | ✅ in the ME/CFS subtype |

**Nine of the first eleven rows overlap.** This is the whole problem.

---

## Two different mechanisms converging on the same phenotype

### 5-ARI pathway (GABAergic / neurosteroid)

```
5-AR inhibition (type 1 = the CNS isoenzyme; dutasteride blocks it, finasteride largely doesn't)
    ↓
progesterone → 5α-dihydroprogesterone → ALLOPREGNANOLONE blocked
    ↓
reduced positive allosteric modulation of GABA-A
    ↓
depressed mood, anxiety, anhedonia, cognitive dulling, sleep disruption
```

Also relevant: DHT itself is neuroactive, and androgen signalling interacts with dopaminergic tone — so a purely GABAergic account is probably incomplete.

### Long COVID pathway (dopaminergic / inflammatory)

```
SARS-CoV-2 → neuroinflammation + kynurenine shift + HPA flattening
    ↓
reduced striatal dopamine terminal density (2026 imaging study, per ../../docs/01-triad-model.md)
    ↓
anhedonia, amotivation, lethargy, mental exhaustion, hypersomnia
```

**Different neurotransmitter systems. Same clinical picture. Fully additive in principle** — reduced inhibitory-tone modulation stacked on reduced reward signalling. Nothing in either mechanism predicts they'd cancel out.

---

## What the timeline in this specific case tells us

| Date | Event |
|---|---|
| 2020-02 | Topical minoxidil started |
| 2020 | Dutasteride started |
| 2021 | COVID infection → long COVID onset |
| 2021–2023 | Severe brain fog, fatigue, mental exhaustion |
| 2023–2026 | Substantial spontaneous recovery to ~70–80% |
| 2024 | **Dutasteride tapered/stopped** over anhedonia-like symptoms |
| 2024–2026 | Minoxidil only, inconsistently |
| 2026 (current) | Dutasteride restarted, alternate-day |

### Three readings, and what each predicts

**Reading A — it was the dutasteride.** Predicts: symptoms should have improved measurably in the 2024–2026 window after stopping it, on a timescale of 2–4 months (allowing for the ~5-week terminal half-life), and should worsen again now that it's restarted.

**Reading B — it was the long COVID.** Predicts: the 2024 dutasteride stop produced no clear symptom change, the 2023–2026 improvement tracks the general LC recovery curve rather than the drug timing, and restarting dutasteride now changes nothing.

**Reading C — both, additively.** Predicts: partial improvement on stopping, incomplete because the LC component persisted — which is exactly what a plateau at 70–80% looks like from the inside.

### What the evidence in hand actually favours

- **Dutasteride preceded the LC onset by roughly a year without producing these symptoms.** That's real evidence against dutasteride being *sufficient* on its own. It doesn't rule out an additive contribution once a second hit landed.
- **The symptom profile leans LC:** hypersomnia is prominent and is characteristic of the LC phenotype, not of the 5-ARI picture. Meanwhile the most *distinctive* 5-ARI features — genital numbness, sexual anhedonia specifically, marked anxiety, insomnia — are not documented in the profile. Weak evidence, and this discrimination is **not a validated method**, but it's the only discriminating signal currently available.
- **The 2024 taper was not a clean experiment.** It coincided with the ongoing spontaneous LC recovery slope, there was no structured before/after measurement, and dutasteride's months-long washout smears the timing.

**Working conclusion: Reading C, weighted toward LC as the dominant term.** Held loosely. The correct response is not to argue about it — it's to run the clean experiment that 2024 wasn't.

---

## The clean experiment

### The key pharmacokinetic fact that reframes the current situation

**Alternate-day dutasteride is not a reduced dose.** With a ~5-week terminal half-life and minimal DHT rebound between missed doses, alternate-day dosing sits at or near maximal DHT suppression. In neurosteroid terms, the current regimen is functionally full-dose dutasteride, including full type-1 (CNS) inhibition.

**Implication: reducing the frequency did not reduce the exposure.** If the concern was a 5-ARI-mediated mood effect, the current regimen has not addressed it. See [03-5ari-guide.md](03-5ari-guide.md) for the real de-escalation ladder.

> ⚠️ **Amendment (2026-08-20).** Regional subgroup data in the 2019 SR/MA show dutasteride beats finasteride **at the frontal scalp** as well as the vertex — and on blinded global photographic assessment the frontal advantage is the larger of the two (MD 0.25 vs 0.17). **If the temples/hairline are a treatment priority, Option 1 costs more than a crown-only analysis implies.** It remains the right first move, because an unmeasured mood question on a full-strength CNS-active drug outranks a subgroup effect size. But the trade is real, and there's a way to hedge it: pair the step-down with **local dutasteride delivery to the frontal scalp** (topical/mesotherapy/intralesional — Phase II RCT plus an SR/MA of small studies, so emerging rather than established). See [08-frontal-temples.md](08-frontal-temples.md).

> ### ⚠️ Correction (2026-08-24) — Option 1 is downgraded; Option 2 becomes the recommended move
>
> Option 1's whole rationale was that finasteride spares CNS type-1 5-AR and should therefore carry less mood liability. **The comparative human data does not support this** — a French nationwide cohort found *higher* suicide/self-harm risk with finasteride than dutasteride in men with prior mood disorders, and pharmacovigilance reports psychopathological issues more often for finasteride. (Caveats: BPH population, 50+, finasteride at **5 mg** not 1 mg, observational.) See [03-5ari-guide.md](03-5ari-guide.md).
>
> **Consequence: swapping one oral 5-ARI for another is not a reliable way to test or reduce a mood effect.** To change exposure you must change **route or dose**, not brand.
>
> **→ Option 2 (topical finasteride 0.25%) is now the recommended first move.** It cuts serum DHT reduction to ~34.5% vs ~55.6% oral with comparable local efficacy, and it is the only option that genuinely reduces systemic exposure while keeping treatment going. It also reconciles with the standing decision already recorded in the long COVID `context.md`: *"Do NOT restart oral 5-ARI during recovery; topical/non-hormonal MPB options only."* That earlier judgement looks better than the one this document originally made.
>
> Cost: topical finasteride has weaker frontal efficacy than oral dutasteride — see [08-frontal-temples.md](08-frontal-temples.md). That is the price of the safer route, and it is a real one.

### Option 1 — Switch dutasteride → finasteride 1 mg daily (downgraded — see correction above)

**The trade:** you give up some efficacy (finasteride is measurably weaker on hair count) and you remove **type-1 inhibition — the CNS isoenzyme**. You also trade a months-long washout for a days-long one, which means every future decision becomes testable.

Why this is the right first move:
- It's the **only option that tests the hypothesis without sacrificing the hair.** Finasteride 1 mg daily still halts progression in the large majority of men
- The 2025 intermittent-dosing RCT found **thrice-weekly dutasteride did not significantly beat daily finasteride 1 mg** on hair count. If you were going to dose dutasteride intermittently anyway, you were already in finasteride's efficacy range — while keeping type-1 inhibition and the long washout. That's the worst of both
- It buys **reversibility**. On finasteride you can test a change in 3 weeks instead of 4 months

**Protocol:** stop dutasteride, start finasteride 1 mg daily. Allow **8–12 weeks** for residual dutasteride to clear before reading the mood signal. Rate weekly throughout.

### Option 2 — Step down to topical finasteride 0.25% ⭐ now the recommended first move

Serum DHT reduction ~34.5% versus ~55.6% for oral finasteride, with comparable local efficacy in the Phase III trial and lower sexual AE rates (2.8% vs 4.8%). The next rung down if Option 1 still produces a signal. Caveat: **the 2025 FDA concern about unvalidated pharmacy-compounded topical finasteride applies** — obtain a trial-validated formulation, not a compounding-pharmacy improvisation.

> ⚠️ **India availability check, 2026-09-08.** A standalone **topical finasteride 0.25% product is not marketed in India.** Retail listings (1mg, Apollo, PharmEasy, Medkart) carry only **finasteride 0.1% + minoxidil** combinations — Morr-F 5%/10% (Intas, ₹850–1,456/60 mL), Hair 4U F (Glenmark ₹811), Tugain Men 5% (Cipla ₹944), Actihair 5F (Leeford ₹483). Fintop/Finax-type finasteride-only topicals were not found. Oral finasteride 1 mg and oral minoxidil (Lonitab 2.5 mg ₹18.7, 5 mg ₹45) are available. **Consequence:** Option 2 as written (0.25%, trial-validated formulation) requires import or compounding — and compounding carries exactly the FDA caveat above. The India-feasible choices are (a) a 0.1% combination twice daily, accepting the lower finasteride concentration and the twice-daily-wet-application adherence problem documented in `../personal/profile.md`; (b) Option 1 (oral finasteride 1 mg) as the step-down, accepting that it does not reduce systemic exposure the way the topical would but does remove type-1 inhibition and restores a 3-week washout; or (c) a validated import. **Decide before the step-down window opens** (long COVID plan: ~week 6 of the phased plan in `../../personal/action-plan.md`). Sources in `../../docs/sources.md` (India availability block).

### Option 3 — Full 5-ARI holiday, 4 months, structured

Only if the mood signal is severe, or if Options 1 and 2 both leave it in place. This is the definitive test and it costs real hair: expect progression to resume and gains to erode over 6–12 months. Run it *with* weekly ratings and a fixed end date, not open-ended.

### Option 4 — Wait for clascoterone

**Topical androgen receptor antagonist, FDA submission targeted 2026, potential approval ~2027.** Blocks the receptor locally with minimal systemic androgen effect — meaning it attacks the same pathway **without the 5-AR inhibition, and therefore without the allopregnanolone mechanism entirely.** If the 5-ARI mood question turns out to be real in this case, clascoterone is the exit route from the trade-off. Set a calendar check for **2027-01**. It is not a reason to do nothing for 18 months.

---

## Sequencing rule — the thing most likely to be gotten wrong

The long COVID plan calls for **bupropion**. This plan calls for a **5-ARI change**. Both act on the same symptom cluster.

**Do not start them in the same window.** If you start bupropion and switch the 5-ARI together and feel better, you will never know which one did it — and you'll be committed to both indefinitely, one of them possibly for nothing.

**Recommended order:**

```
Weeks 0-2     Baseline. Weekly ratings for 2 weeks BEFORE changing anything.
              (energy, motivation, anhedonia, sleep, mental exhaustion, libido, erectile function)
              Same day each week. Retrospective recall is worthless here.

Week 2        Switch dutasteride → finasteride 1 mg daily. Change NOTHING else.

Weeks 2-14    Keep rating weekly. 8-12 weeks for dutasteride washout + signal to emerge.
              → Anhedonia improves? Reading A/C had weight. Consider stepping down further
                (Option 2), and reassess whether bupropion is needed at all.
              → No change? The 5-ARI is largely exonerated. Proceed to bupropion with a
                clean attribution, and stop spending hair on this hypothesis.

Week 14+      Then, and only then, start bupropion per ../../docs/03-bupropion-guide.md.
```

**Why the 5-ARI moves first:** it's the *removable cause* candidate. Bupropion is symptomatic treatment that works regardless of cause — and it will **mask** the very signal you're trying to read. Test the cause before you cover it up. The cost of this ordering is a 12-week delay on bupropion. The cost of the reverse ordering is never knowing, and possibly taking two drugs for one problem for years.

**Secondary note:** psychotropics can occasionally provoke telogen effluvium. If diffuse shedding appears within a few months of starting bupropion, log it in `status.md` and raise it with the prescriber rather than assuming AGA progression — the treatments diverge. Do not pre-emptively avoid bupropion on this basis.

---

## Do not do these

- ❌ **Don't switch to saw palmetto as a "natural, safe alternative."** It's a weak 5-AR inhibitor and **shares the same neurosteroid mechanism.** Weaker efficacy, same theoretical liability, worse evidence
- ❌ **Don't change the 5-ARI and start bupropion in the same month**
- ❌ **Don't judge a mood change inside 8 weeks of a dutasteride change** — the half-life makes it uninterpretable
- ❌ **Don't rely on memory.** Weekly written ratings or the experiment is void. Expectancy effects here are large and documented in both directions
- ❌ **Don't stop everything at once out of frustration.** That's what makes 2024 uninterpretable. One variable, 8+ weeks, written record
- ❌ **Don't dismiss a real mood signal as nocebo.** The EMA confirmed a suicidal-ideation association in 2025. Hair is not worth that risk, and the whole point of the ladder above is that there are options at every rung

---

## Bottom line

The 2024 taper was the right instinct executed without instrumentation. The current alternate-day regimen doesn't reduce exposure and therefore doesn't resolve the question. **Switch to finasteride 1 mg, measure weekly for 12 weeks, and only then touch the long COVID stack.** That single move preserves nearly all the hair benefit, removes CNS type-1 inhibition, restores reversibility, and produces the first interpretable data point this question has ever had.

Sources: [sources.md](sources.md).

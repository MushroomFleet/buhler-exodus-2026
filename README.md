# Buhler–Exodus 2026

A worked demonstration that **TINS-CENA challenge loops transfer out of software engineering and into advanced science**, using a real, live, contested physics claim as the test subject. The repository contains two artifacts: a topic-focused research scratchpad assembled from a three-hour engineering podcast, a granted US patent, and open web sources; and a CENA challenge-loop pass run against that scratchpad from the standpoint of *an engineer who wants to build the thing today*. The subject is Exodus Propulsion Technologies' "Electrostatic Pressure Force" propellantless thruster, developed by Dr Charles Buhler and Andrew Aurigema. **The output is an assessment of claims as reported — not a debunking, and not an endorsement.** Both inventors are credentialed, publish their build instructions for free, invite replication, and propose the orbital test that would settle the question; the artifacts say so repeatedly and in those terms.

## What the method is

The workflow has two movements. First, **collapse**: a long unstructured source (transcript, images, patent, press) is folded into one semantically named scratchpad where every claim is sorted into confidence tiers — textbook physics, arithmetic on the subject's own numbers, direct quotation, secondary reporting, and the analyst's own inference. Facts that decay (prices, publication status, current claims) are web-search-verified at writing time rather than recalled. Second, **challenge**: adversarial passes from the [TINS-CENA](https://github.com/MushroomFleet) taxonomy interrogate one assumption class at a time — baseline, existence proof, ambition split, padding audit, deliverable minimum, bottom-up re-derivation, actionability audit, finer points. Each loop is *challenge → evidence → verdict → decision of record → mechanical fold-in*, with superseded decisions kept visible rather than overwritten.

The claim under test in this repository is not the thruster. It is the method: that "are you sure about that?" run with evidence attached collapses a science-assessment problem the same way it collapses a budget.

## Contents

| File | Role |
|---|---|
| `Buhler-research.md` | The research scratchpad. Physics assessment across 17 sections: the field-momentum and hidden-momentum lineage, the Feynman disk, the centre-of-energy theorem, the stated mechanism, the full thrust ledger, the patent derivation, a steelman of the proponents' case, an epistemic-status table, a 15-item discriminating-test list, and an image log. |
| `Buhler-replication-CENA.md` | The challenge-loop pass. Parametric tagging, loops L1/L3/L4/L6/L7/L8/L9/L10, a 15-entry decision ledger, a costed bill of materials, and a termination-criteria table. |
| `README.md` | This file. |
| `LICENSE` | **MIT** |

## What the loops produced

Stated as findings, with the reasoning living in the artifacts.

**Cost collapse, $10–20k → ~$650.** The naive replication estimate assumes the vacuum configuration is mandatory. It isn't — the subjects' own strongest claim is that thrust persists for days after the power is disconnected. Ion wind needs current, cable stiffness needs cables, supply EMI needs a running supply. Charge the device, disconnect it, remove the supply from the room, and all three vanish without a chamber. The reported 2–4 mN is 0.2–0.4 grams-force, which a 0.001 g balance resolves with 200–400× margin. Convergence was reached by naming the assumption, not by splitting estimates.

**The signal is 10⁻⁴ of the device's own internal force.** From the single dimensioned specification in the entire record — 10⁸ V/m — the Maxwell stress is 44 kPa, or ~442 N across a 10×10 cm device. The claimed 50 mN is one ten-thousandth of that. This cuts both ways: it explains why the effect appears in "90% of configurations," and it means any mechanical path coupling 0.01% of that internal force outward — plate deflection, electrostriction, mount strain, dielectric creep — reproduces the result. No control for this exists anywhere in the public record.

**The patent derivation proves too much.** US 11,511,891 B2 derives its central force equation in six steps, of which the first five contain no electromagnetism at all. The same manipulation applied to gravitational potential energy yields a reactionless gravity drive. Separately, the step that generates the entire result assumes stored energy decays as 1/t — which the patent's own constant-voltage apparatus violates.

**Their own patent cites the experiment that nulled it.** Talley (1991), Veritay Technology, under US Air Force contract: an asymmetric capacitor on a torsion wire in vacuum, force observed, traced to electrostatic interaction between device and chamber. That is the governing precedent, it appears in their background section, and no public source addresses how the current configuration differs.

**Two facts, if published, would make replication meaningful.** The patent closed eight of ten actionability gaps — blade geometry, gap behaviour, dielectrics, 40 kV, polarity, scaling laws, and the full FEMM/MATLAB/COMSOL design loop are all public and have been since 2022. What remains is the device mass (without which no thrust-to-weight figure is checkable) and the definition of the dummy-plate control (the programme's strongest evidence, specified in one clause that does not say what it matches on). Publishing both would cost approximately nothing.

**Three artifact classes were added that appear in no prior source:** Maxwell-stress deformation, electron-stimulated desorption (which survives both vacuum and power-off, and predicts the subjects' own puzzling 12-hour observation), and an unmentioned X-ray hazard — a 140 kV electrode pair in vacuum with sharp field-emitting features is an X-ray tube, and the chamber has a large viewport.

## How to use this

**As a reference on the claim.** Read `Buhler-research.md` §13 (epistemic status) first — it sorts every statement in the document into confidence tiers and lists the seven questions that cannot be resolved without the inventors. Then §11 (the steelman) before §3–§6 (the objections), because the objections were written first and the steelman is what keeps them honest.

**As a replication starting point.** Read `Buhler-replication-CENA.md` L6 for the Tier-0 protocol and bill of materials, L7 for the derived build parameters, and the revised L9 gap table for what the patent does and does not tell you. Then §7 of the research scratchpad for the fifteen discriminating tests, of which items 12–15 are the ones nobody has run.

**As a method template.** Both files are structured to be copied. The pattern:

```
1. Collapse sources into one semantically named scratchpad.
2. Tag every number: measurement, arithmetic, quotation, secondary report, or inference.
3. Web-search-verify anything that decays. Say what was verified vs assumed.
4. Write the steelman before trusting your own objections.
5. Run loops. Attach evidence to every verdict.
6. Fold in mechanically, same session. Keep superseded decisions visible.
7. Sweep for stale references. Zero is a gate, not a goal.
```

## The challenge taxonomy

Shared vocabulary across both artifacts.

| Loop | Question | Instance in this repo |
|---|---|---|
| L1 | What does this cost or take? | $10–20k naive replication baseline, ±2× |
| L3 | Cheapest published comparable? | The subjects' own $150 kit — rejected; by their account ion wind exceeds the effect in air |
| L4 | Proof claims vs product claims? | "A force exists that isn't ion wind" is buildable; "Mars in 3.5 days" is excluded on energy grounds |
| L5 | Why N× the anchor? | Reported thrust-to-weight spans 10⁴ across the record |
| L6 | Smallest shippable unit? | Tier-0 power-off protocol, ~$650 |
| L7 | Re-derive from first principles on named hardware | 44 kPa Maxwell stress; the 10⁻⁴ residual |
| L8 | Can the spec as written be built? | Not from the transcript; yes from the patent |
| L9 | Could an implementer start tomorrow? | Ten gaps → two, after the patent |
| L10 | What did nobody price? | Lethality procedure, X-rays, electron-stimulated desorption |

## Requirements

Reading the artifacts requires nothing but a Markdown viewer. Reproducing the method requires a long-form source, a web-search-capable LLM, and the discipline to tag assumptions before challenging them. Reproducing the *experiment* requires the bill of materials in `Buhler-replication-CENA.md` L6 — and the safety section in L10 is not optional. The subjects describe their own apparatus as "lethal at every possible instance," and the X-ray finding is ours, not theirs.

## Scope and fairness

This repository assesses **published claims**, not people. Dr Charles Buhler is a credentialed electrostatics researcher who helped establish NASA Kennedy's Electrostatics and Surface Physics Laboratory; Andrew Aurigema is a career aerospace engineer. They abandoned a twenty-year theory on tape when it stopped working, publish free build instructions, invite outside replication, and propose the orbital flight that would end the argument. Their measurement practice is better in at least one respect than most published work in this field — mounting the entire high-voltage supply inside the test article eliminates a classic artifact at the root rather than correcting for it.

Nothing in these artifacts demonstrates the effect is not real. They establish that the reported evidence does not yet distinguish a new force from a measurement artifact, that the vehicle-scale extrapolation fails on energy grounds independent of that question, and that the decisive tests are known, cheap, and so far unperformed by anyone outside the group. If new information arrives, the decision ledger is append-only and the artifacts are built to absorb it.

## License

See `LICENSE`. **Not yet selected — choose one before publishing.**

## 📚 Citation

### Academic Citation

If you use this codebase in your research or project, please cite:

```bibtex
@software{buhler_exodus_2026,
  title = {Buhler-Exodus 2026: TINS-CENA challenge loops applied to a contested physics claim},
  author = {Drift Johnson},
  year = {2026},
  url = {https://github.com/MushroomFleet/buhler-exodus-2026},
  version = {1.0.0}
}
```

### Donate:

[![Ko-Fi](https://cdn.ko-fi.com/cdn/kofi3.png?v=3)](https://ko-fi.com/driftjohnson)

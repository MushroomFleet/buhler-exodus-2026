# Buhler Replication — TINS-CENA Challenge Loops

**Subject under challenge:** `Buhler-research.md` (v. 2026-08-25)
**Challenge frame:** *an engineer who wants to build this today, using only the information in that document.*
**Method:** TINS-CENA — evidence-anchored adversarial passes with mechanical fold-in. See the decision ledger at §D.

**Stance:** the scratchpad is an *assessment* artifact. This pass asks whether it can function as a *build* artifact, and if not, what the minimum is that could. Every number below is either search-verified at time of writing, derived from first principles, or tagged `[PARAMETRIC]`.

---

## M1 — Parametric tagging pass

Before loops can run, the scratchpad's numbers must be sorted. Loops attack assumptions, never measurements.

| Class | Items | Loop-eligible? |
|---|---|---|
| **Reported measurements** (theirs, not ours) | 50 mN; 2–6 mN typical; 125 µN; 0.5/1.7/1.8 Earth unity; 10⁻⁶ torr; 30,000–200,000 s charging; 10⁸ V/m | **No** — challenge the *interpretation*, not the value |
| **Textbook physics** | P/c = 3.336 nN/W; P = ε₀E²/2; Noether; centre-of-energy theorem | **No** |
| **Our arithmetic on their numbers** | 47 GW; 168 kN; 16.9 kJ/day; 18–71 µA | **No** — but re-derivable, and L7 does |
| `[PARAMETRIC]` **— assumptions** | Device capacitance ~1.8 nF; stored energy ≤100 J; device mass; gap; groove geometry; replication cost; which artifact class dominates | **Yes — these are the targets** |

**Immediate finding:** the scratchpad contains **no dimensioned geometry whatsoever.** Not one length. This is the fact that drives L9.

---

## L1 — Baseline: what does a replication cost and take?

**Challenge:** *Estimated cost and time for an engineer to replicate, from this document?*

**Top-down instinct:** "It's a vacuum experiment with high voltage and sub-millinewton force measurement — call it $10–20k and six months." Stated uncertainty ±2×.

**Verdict:** the instinct is defensible but **unexamined**, and it silently assumes the vacuum-chamber configuration is the one that must be built. L6 destroys that assumption. Baseline recorded so the later collapse is traceable. → **D1**

---

## L3 — Existence proof: what is the cheapest published comparable?

**Challenge:** *Match on the binding constraint. What is the cheapest demonstration in the literature that would count?*

**Candidate A — their own $150 DIY kit** (§12.6). Rejected as an anchor. The binding constraint is not "produces a deflection," it is **"discriminates against ion wind."** By Buhler's own statement at 2:03:26 — *our effect is much much weaker than ion wind* — a 0.1 mN deflection on a string in air is fully explained by the artifact. The kit is an anchor for *building*, not for *knowing*.

**Candidate B — Tajmar's Dresden torsion balance.** The right methodological anchor: independent apparatus, own error budget, published null results on EmDrive and Mach-effect claims. But it is a university facility, not a floor.

**Candidate C — the power-off persistence protocol (§12.2).** *This is the real existence proof and it comes from their own data.* Reasoning below at L6.

**Verdict:** the binding constraint is artifact discrimination, not thrust production. Anchor is C. → **D2**

---

## L4 — Ambition split: which claims serve the proof, which serve the product?

**Challenge:** *Separate the provable claim from the competitive claim.*

| Claim | Class | Buildable today by one engineer? |
|---|---|---|
| A force exists that is not ion wind, not Coulomb attraction to surroundings, not thermal | **PROOF** | **Yes** — see L6 |
| The force persists with zero power input | **PROOF** | **Yes** — same rig |
| The force scales with area/field as claimed | PROOF (second tier) | Yes, with a parameter sweep |
| Thrust-to-weight ≥ 0.5 at system level | PRODUCT | Only if A is established |
| Propellantless spacecraft propulsion | PRODUCT | No |
| Mars in 3.5 days | PRODUCT — **and excluded on energy grounds regardless** (§9.5) | No |

**Verdict:** the proof claim is separable, cheap, and does not require accepting or rejecting any theory. **The product claims are archived, not deleted** — gated on the proof claim. An engineer today should build only for row 1 and 2. → **D3**

---

## L6 — Deliverable minimum: the smallest discriminating unit

**Challenge:** *What is the smallest thing that could actually settle something?*

**This is the pass that collapses the plan, and the insight comes from their own strongest claim.**

Their most extraordinary reported result — thrust persisting for days with the power off (§12.2) — is also **the cheapest one to test, because it eliminates the dominant artifact by construction rather than by equipment.**

Ion wind requires continuous current. Cable stiffness requires cables. Power-supply EMI requires a running supply. **If the device is charged, then fully disconnected and physically separated from its supply, all three vanish without a vacuum chamber.**

### The Tier-0 protocol

1. Build the device. Charge to target field for the stated duration.
2. **Disconnect entirely. Remove the HV supply from the room.**
3. Place the device, thrust axis vertical, on a milligram balance inside a grounded enclosure.
4. Read the apparent weight change.

**Sensitivity check:** their persistent thrust is 2–4 mN = **0.20–0.41 grams-force**. A 0.001 g jeweller's balance resolves this with 200–400× margin. No load cell, no vacuum, no data acquisition.

**Free controls, all zero-cost:**
- Invert 180° → sign must flip.
- Rotate 90° → must null.
- Uncharged identical device → must read zero.
- Wait for charge decay → must decay with it.
- Grounded enclosure at two distances → Coulomb attraction to surroundings varies, internal thrust does not.

**Verdict:** the strongest claim in the programme is testable for **under $650**. → **D4**

### Bill of materials (search-verified where marked)

| Item | Cost | Source |
|---|---|---|
| HV supply, 0–30 kV, ≤400 µA, used | **$111–131** | < cite index="30-1">Spellman X3000 30 kV 400 µA and Bertan 2554-2 0–30 kV 400 µA listed at $131 and $111</cite> |
| Milligram balance, 0.001 g | $30–300 `[PARAMETRIC]` | not verified |
| Materials: brass shim, Kapton tape, foil, RTV, foam | ~$100 `[PARAMETRIC]` | |
| Grounded enclosure, discharge stick, interlock | ~$100 `[PARAMETRIC]` | see L10 |
| **Tier 0 total** | **~$350–650** | |
| *Tier 1: + rotary-vane pump and small chamber (10⁻³ torr — kills ion wind actively)* | +$450–1,100 | < cite index="21-1">vacuum chambers listed under $250 and in the $250–600 band</cite> |
| *Tier 2: + used turbo pump for 10⁻⁶ torr, matching their spec* | +$250–2,500 | < cite index="29-1">used turbomolecular pumps listed from $250 to ~$1,700</cite>; < cite index="23-1">a turbo pumping station at $2,495</cite> |
| *Tier 3: + internal HV supply, ITO Faraday cage, load cell, DAQ — their full configuration* | +$3,000–5,000 `[PARAMETRIC]` | |

**Top-down ($10–20k, L1) vs bottom-up ($650, L6): the gap is entirely the vacuum chamber, and the vacuum chamber is only necessary if current is flowing.** Their own persistence claim removes the current. Convergence achieved by identifying the assumption, not by splitting the difference. → **D5**

---

## L7 — Bottom-up: re-derive the physics from the one hard spec

**Challenge:** *"Are you sure about that?" Derive the device from first principles using only what the document actually specifies.*

The scratchpad contains exactly **one** dimensioned engineering specification: **field strength 10⁸ V/m** (2:02:37, "we play at 10 to the 8th volts per metre... two orders of magnitude greater than it takes to break down air").

Everything else follows:

```
Gap at 30 kV:    d = 30,000 / 10⁸        = 0.30 mm
Gap at 140 kV:   d = 140,000 / 10⁸       = 1.40 mm
```

**Material check.** Air breaks down at ~3×10⁶ V/m — so **air cannot hold this field, and neither can styrofoam** (mostly air). Kapton's dielectric strength is ~3×10⁸ V/m, so at 10⁸ V/m Kapton runs at **1/3 of breakdown.** This identifies the load-bearing material: *the Kapton is holding the field; the foam is not.* An engineer reading §12.3's materials list would not have known which layer matters. Now they do.

**Capacitance and stored energy**, 10×10 cm active area, 0.30 mm Kapton (ε_r ≈ 3.4):

```
C = ε_r ε₀ A / d = 3.4 × 8.85×10⁻¹² × 0.01 / 3×10⁻⁴ ≈ 1.0 nF
U = ½CV² at 30 kV                                    ≈ 0.45 J
```

This tightens §12.2's energy bound: **sub-joule, not ~100 J.** The energy entailment there gets *stronger*, not weaker.

**The number that reframes everything.** Maxwell stress at the operating field:

```
P = ε₀E²/2 = 8.85×10⁻¹² × 10¹⁶ / 2 = 44,250 Pa ≈ 44 kPa
Total across 0.01 m²                             ≈ 442 N
```

**The device contains an internal electrostatic force of ~442 newtons. The claimed net thrust is 50 mN.**

```
Claimed effect / internal force ≈ 1.1 × 10⁻⁴
```

**This is the single most important finding of the whole CENA pass**, and it cuts both ways with unusual symmetry:

- *For them:* it explains why the effect is so hard to design out and why it appears in "90% of configurations" (§12.10). A 0.01% residual of a 442 N force is not exotic; it is what you would expect any real asymmetry to produce.
- *Against them:* **any mechanical path that couples 0.01% of that internal force to the outside world reproduces the result exactly.** Plate deflection under 44 kPa, electrostriction of the dielectric, strain in the mounting, creep in the Kapton — all operate at far more than the 10⁻⁴ level. A device pulling itself into a slightly different shape shifts its centre of mass, and on a pendulum or balance that is indistinguishable from thrust.

**Verdict:** the signal is a ten-thousandth of a force that is definitely, uncontroversially present. Neither the transcript nor the scratchpad contains any control for mechanical deformation under Maxwell stress. **This is a named artifact class that nobody — including this document, until now — has addressed.** → **D6**

---

## L8 — Plan/hardware gap: can the document as written be built?

**Challenge:** *Read the spec against the bench.*

**No.** The scratchpad specifies one field strength and no geometry. An engineer cannot cut metal from it.

Worse: the two figures that *would* let a builder size the device are mutually inconsistent by four orders of magnitude.

| Device | Thrust | Mass | T/W (Earth unity) |
|---|---|---|---|
| Spinner (§12.4) | 2 mN | 2–2.5 kg | **9 × 10⁻⁵** |
| Persistent (§12.2) | 2–4 mN | `[PARAMETRIC]` ~2 kg | **~2 × 10⁻⁴** |
| Best-ever 50 mN | 50 mN | ~5 g (inferred from "1g") | **~1.0** |
| "Advertised" system level | — | — | **0.5** |

**A builder has no way to know which of these to target, and they differ by 10⁴.** Aiming at 0.5 means expecting half the device's weight; aiming at the spinner means expecting 0.01% of it. These require completely different instruments. → **D7**

---

## L9 — Actionability audit: what questions can this document not answer?

**Challenge:** *Could an implementer start tomorrow?*

> **REVISED 2026-08-25, second pass.** The original audit was run against the transcript and scratchpad only. **US 11,511,891 B2 has since been read, and it closes most of these gaps.** Both the original verdict and the revision are kept below, per the method — superseded decisions stay visible.

### First pass (transcript only) — ten gaps, L9 FAILED

| # | Gap | Pinned default | **Patent status** |
|---|---|---|---|
| G1 | Groove pitch, fin count, tip radius | **Unpinnable.** Blocks exact replication | **CLOSED** — blade configuration disclosed; blade length ≤ blade spacing (beyond that the far surface is Faraday-shielded); triangular ground features optimal at ~23, claimed 6× gain |
| G2 | Electrode gap | 0.30 mm at 30 kV | **CLOSED** — "as close as possible" short of breakdown; FIG. 28 gives force vs gap |
| G3 | Which dielectric where | Kapton in gap, foam outer | **CLOSED** — polyimide, PTFE, styrofoam, epoxy, RTV, HV putty all disclosed as gap dielectrics |
| G4 | Operating voltage | 30 kV | **CLOSED — up to +40 kVDC.** The 140 kV needle was an early outlier, not the operating point |
| G5 | Polarity | Never stated; test both | **CLOSED** — V− (ground) to the copper tape; large-area electrode is ground, blades are HV. Patent also states force is polarity-independent (∝E²) |
| G6 | Thrust direction | Toward large-area electrode | **CONFIRMED** |
| G7 | Charge protocol | 30,000 s | Open — patent is silent on the persistence protocol entirely |
| G8 | Device mass | Unstated | **STILL OPEN** — the missing denominator in every T/W figure |
| G9 | Scaling law | None exists | **CLOSED** — F ∝ V²; F ∝ ground area (claimed linear); FEMM+MATLAB and COMSOL tool chain disclosed |
| G10 | **Dummy-plate definition** | Undefined | **STILL OPEN** — the patent describes 180° flip and ITO-box controls, but never defines the dummy plate |

### Revised verdict

**Eight of ten gaps closed. L9 now PASSES for construction and FAILS for verification.**

An engineer can now build the device: blade geometry, gap behaviour, materials, 40 kV, polarity, the ~23-triangle ground optimisation, and a fully disclosed FEMM/MATLAB/COMSOL design loop. **This is a reproducible engineering specification.** The earlier finding — "can build a device that produces a reading, cannot build a device that produces evidence" — was **half wrong and is corrected here.**

What remains open is narrower and sharper:

- **G8 — device mass.** Without it, no T/W figure can be checked, and the 0.5-vs-1.7-vs-1.8 Earth-unity spread (D7) stays unresolvable.
- **G10 — the dummy-plate control.** Still the single most important undisclosed item, and §7.15 explains why: a symmetric dummy deforms symmetrically, so the control may null the artifact and the effect together.

→ **D11** supersedes D8.

---

## L10 — Finer points: what did nobody price?

**Challenge:** *What resource, hazard, or failure mode appears in no budget?*

### F1 — Lethality is unpriced

At 2:02:53: *"it was lethal at every possible instance."* Neither the transcript nor the scratchpad contains a safety budget. At 30–140 kV with a ~1 nF capacitance, stored energy is sub-joule — below the ~10 J conventionally treated as the lethality threshold for capacitive discharge — but the **supply** is not, and 400 µA at 30 kV across a chest is well above the ~30 mA fibrillation range if a fault path opens. Interlocked enclosure, grounded discharge stick, single-hand rule, no lone working. **Priced above at ~$100; the real cost is procedure, not hardware.**

### F2 — X-rays. Nowhere mentioned, in three hours or in the scratchpad.

**A high-voltage electrode pair in vacuum is an X-ray tube.** Field emission from sharp features — and the design deliberately uses sharp fins (§12.1) — releases electrons that accelerate through the full potential and produce bremsstrahlung on impact.

- At 30 kV: soft X-rays, largely stopped by a steel chamber wall, but not by a viewport.
- At 140 kV: **penetrating.** This is diagnostic-radiography energy.

Their vacuum chamber has "a great big viewport on the side" (2:12:47). **An engineer replicating the 140 kV configuration in vacuum, watching through a viewport, is standing in front of an unshielded X-ray source.** This must be in any build plan. Cost: a $30 dosimeter badge and leaded glass or a camera instead of an eye. → **D9**

### F3 — Electron-stimulated desorption: an unexcluded artifact, and it fits their own data

Field emission in vacuum does not merely make X-rays. Electrons striking surfaces liberate adsorbed gas — **electron-stimulated desorption**, a standard vacuum-science effect. Asymmetric geometry gives asymmetric desorption gives a gas jet gives real thrust with real reaction mass.

Three reasons this deserves a place in the artifact table:

1. **It survives high vacuum.** ESD does not need ambient gas; it needs adsorbed monolayers, which are present at 10⁻⁶ torr indefinitely.
2. **It survives power-off.** Their own mechanism — trapped charge maintaining a static field (§12.2) — *maintains field emission*, which maintains ESD. The persistence they report as anomalous has a conventional explanation they have not excluded.
3. **It matches their own most puzzling observation.** They report (2:14:50) that a new thruster shows *no thrust* until ~12 hours of pumping, and attribute this to water shorting the device. ESD offers an alternative reading of the same data: at first the surface is saturated and desorption is diffuse; as pumping proceeds and the field can be sustained, emission-driven desorption becomes directional.

**This is not a claim that ESD explains the effect.** Magnitudes are unknown and would need calculating. It is a claim that **a named, conventional, vacuum-compatible, power-off-compatible momentum source has never been mentioned by anyone in this record**, and that it predicts their water observation as well as their own explanation does.

**Test:** a residual gas analyser on the chamber during a thrust run. If thrust correlates with a partial-pressure rise in H₂O, CO, or H₂, it is ESD. RGA, used: `[PARAMETRIC]` $1–3k. **This should be item 14 on the scratchpad's §7 list.** → **D10**

---

## D — Decision ledger

| ID | Date | Decision |
|---|---|---|
| D1 | 2026-08-25 | Baseline recorded: naive replication estimate $10–20k, ±2×, assuming vacuum configuration. Assumption flagged for challenge. |
| D2 | 2026-08-25 | Binding constraint is **artifact discrimination**, not thrust production. The $150 DIY kit is rejected as an existence proof — by their own account ion wind exceeds the effect in air. |
| D3 | 2026-08-25 | Proof/product split adopted. Rows 1–2 buildable; product claims **archived and gated**, not deleted. Mars vision remains excluded on energy grounds (§9.5) independent of this. |
| D4 | 2026-08-25 | **Tier-0 persistence protocol adopted as the minimum deliverable.** Power-off testing eliminates ion wind, cable stiffness and supply EMI by construction rather than by equipment. |
| D5 | 2026-08-25 | **$10–20k → ~$650.** Convergence achieved by identifying the vacuum assumption, not by splitting estimates. Tiers 1–3 retained as gated escalations. |
| D6 | 2026-08-25 | **Claimed effect is ~10⁻⁴ of the device's internal Maxwell stress (442 N on 0.01 m² at 10⁸ V/m).** New artifact class named: mechanical deformation under electrostatic pressure. No control exists for it anywhere in the record. |
| D7 | 2026-08-25 | Reported T/W spans 10⁴ (9×10⁻⁵ to ~1.0). A builder cannot select a target. Logged as an unresolved inconsistency in the source material, not in this analysis. |
| D8 | 2026-08-25 | **L9 FAILS.** Ten gaps; G1 (geometry) blocks exact replication; G10 (dummy-plate definition) means the programme's key control is unreproducible as documented. |
| D9 | 2026-08-25 | **X-ray hazard added.** Unmentioned in three hours of transcript. Mandatory in any build plan at ≥30 kV in vacuum; serious at 140 kV. |
| D10 | 2026-08-25 | **Electron-stimulated desorption added as artifact class 14.** Survives vacuum and power-off; predicts their 12-hour water observation. RGA test specified. |
| **D11** | 2026-08-25 | **SUPERSEDES D8.** US 11,511,891 B2 read. **Eight of ten gaps closed** — blade geometry, gap, dielectrics, 40 kV, polarity, thrust direction, scaling law, design tool chain. **L9 now passes for construction, fails for verification.** Only G8 (device mass) and G10 (dummy plate) remain. |
| **D12** | 2026-08-25 | **Operating voltage corrected: 40 kV, not 140 kV.** The needle was an early outlier. Tier-0 BOM is unaffected — the $111–131 supplies already cover it. |
| **D13** | 2026-08-25 | **Target force corrected to ~237 µN** (patent's own figure), measured on an Omega DGF155-0.12 at **0.1 mN resolution — a 2.4σ-equivalent margin against instrument resolution.** A replication that beats this resolution by 10× is trivially achievable and would be a genuine improvement on the source work. |
| **D14** | 2026-08-25 | **V² scaling does not discriminate.** Patent presents F ∝ V² as verification; but Coulomb attraction, dielectrophoresis, electrostriction and Maxwell-stress deformation all scale as V². It excludes ion wind and nothing else. **The programme's main scaling result is silent on its main uncontrolled artifact.** |
| **D15** | 2026-08-25 | **Talley (1991) flagged as the governing precedent.** Cited in their own patent: Air Force contract, asymmetric capacitor on a torsion wire in vacuum, force observed and traced to **device–chamber electrostatic interaction**. Image 2 shows a torsion arm with a large copper disc on the chamber wall. **Any replication must reproduce Talley's chamber-interaction control, and the distance sweep (§7.12) is now mandatory rather than optional.** |

---

## Termination status

| Criterion | Status |
|---|---|
| **Convergence** — top-down and bottom-up agree | ✅ $10–20k → $650, gap explained by a named assumption |
| **Gate completeness** — no spend before evidence | ✅ Tier 0 → 1 → 2 → 3, each gated on the previous producing signal |
| **Cheapest-line inversion** — deliverable is among the cheapest lines | ✅ The device is ~$100 of a ~$650 experiment; cost mass sits in instrumentation, which is correct |
| **Actionability (L9)** — unknowns inside tasks, not between them | ⚠️ **PASSES for construction, FAILS for verification** (D11) |

**Revised termination status.** The first pass concluded that an engineer *"can build a device that produces a reading, and cannot build a device that produces evidence."* **The first half of that is now wrong and is withdrawn.** US 11,511,891 B2 discloses blade geometry, the blade-length rule, gap behaviour, six usable dielectrics, 40 kV, polarity, the ~23-triangle ground optimisation, the V² and area scaling laws, and a complete FEMM/MATLAB/COMSOL design loop. **That is a buildable specification, and it was public since 2022.**

The residue is two items:

- **G8 — device mass**, without which no thrust-to-weight claim is checkable.
- **G10 — the dummy-plate control**, still the highest-value undisclosed item in the programme.

**And one new obligation, from their own citations (D15):** Talley did this experiment in vacuum on a torsion wire under Air Force contract in 1991, found a force, and attributed it to electrostatic interaction between device and chamber. **A replication that does not explicitly rule out what Talley ruled in is not a replication of the claim — it is a repetition of the prior art.** The ground-plane distance sweep is promoted from §7.12 to a gate condition.

**Cheapest thing that would still change everything: they publish G8 and G10.** Cost to them, approximately nothing.

---

## Next-cycle profile (archived, gated)

Preserved rather than deleted, per method:

- **Tier 1–3 escalation.** Gated on Tier 0 producing a repeatable, sign-reversing signal above 3σ.
- **Maxwell-deformation control (D6).** Design a device where electrode deformation is instrumented independently — strain gauge or interferometric — so that the 10⁻⁴ residual can be attributed. This is the highest-value new experiment identified by this pass.
- **ESD discrimination (D10).** RGA correlation during thrust.
- **Sidereal survey** (§7.13 of the scratchpad). Free once Tier 0 exists.
- **The product claims.** Filed. Funded by the proof claim succeeding, and by nothing else.

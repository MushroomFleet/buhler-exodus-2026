# Buhler Research — Master Scratchpad

**Subject:** Charles Buhler (lead research engineer, Electrostatics and Surface Physics Laboratory, NASA KSC) — transcript extracts covering ~18:46 to ~24:19, describing the theoretical path from field momentum through hidden momentum to the current "electric-field-only" thruster claim.

**Purpose:** working reference. Track what is textbook-correct, what is load-bearing, what is unsupported, and what would settle it. Not a verdict document.

**Status:** live. Sections marked `[PENDING]` await further transcript or images. Sections marked `[EXPAND]` are stubs.

### Speakers

Three people are present throughout: **Dr Charles Buhler** (physics, theory, electrostatics), **Andrew Aurigema** (engineer, co-inventor, named with Buhler on the patent), and the **interviewer**. Attributions in this document are provisional where the transcript does not label turns.

Working heuristic, to be revised as more transcript arrives: the *physics derivations* (field momentum, hidden momentum, the Feynman disk, QED) are Buhler; the *vehicle and mission engineering* (the 45-tonne spacecraft, the toilet, the car analogy) is Aurigema. The 2016 experiment that restarted the programme is Aurigema's — the "Drew" referred to at 21:45.

**This matters for assessment.** Attributing an engineering extrapolation to the physicist, or a physics claim to the engineer, misallocates both credit and objection. Where a claim's speaker is uncertain, this document says so rather than guessing.

---

## 0. Orientation — what this document is and isn't

Buhler is a credentialed electrostatics researcher, not a hobbyist. Nearly everything he states as physics in these extracts is **correct and correctly attributed**. The disagreement, where there is one, is never about whether he has understood the cited physics — he has — but about whether the cited physics supports the weight placed on it.

Two things worth stating up front so they don't have to be re-litigated:

1. **He explicitly abandons his own twenty-year theory on tape.** "After 20 years working on that theory and two solid years he and I working on that almost every day, it was wrong. It was just wrong. Very wrong." Followed by *"nature doesn't care what you believe."* This is the single most diagnostic moment in the transcript so far, and it points the opposite way from crankery. Cranks defend; he discarded.
2. **The abandonment makes the claim harder to assess, not easier.** What remains is an unexplained empirical effect with the theoretical scaffolding removed. That is a legitimate position for a researcher to occupy — anomaly first, theory later — but it means there is no longer a *prediction* to test, only an effect to explain. Assessment must shift entirely to artifact elimination.

**Read §11 before §3–§6.** Sections 3 through 6 are objections, and they were written before the steelman was. §11 reconstructs the strongest version of the proponents' case and flags where this document is inferring rather than reporting. §12 gives the confidence level attached to every class of claim here. With the authors unavailable to correct us, those two sections are what keep the rest honest.

---

## 1. Timeline of the argument as presented

| Time | Move | Status |
|---|---|---|
| 18:46–19:17 | Field momentum, **g** = ε₀**E**×**B**, known since 1860s | Correct |
| 19:22–19:30 | Changing momentum gives force; E×B thrusters tried since 1940s–50s | Correct, incomplete (§4.2) |
| 19:32–20:20 | Hidden momentum (says 1970s; actually Shockley & James 1967) cancels field momentum where charges flow | Correct |
| 20:27–20:43 | "Get rid of hidden momentum" — possible in the angular case | Correct premise, wrong inference (§3) |
| 20:43–21:20 | Feynman disk: charged beads on insulating disk in solenoid; solenoid off → disk rotates | Correct; misread as loophole (§3) |
| 21:29–21:45 | "Do the linear analogue" — blocked by hidden momentum | Correct that it's blocked; wrong about *why* (§4.1) |
| 21:45–22:52 | Drew's 2016 experiment; the 140 kV "needle thing"; static charges → no hidden momentum → field momentum survives | Internally consistent; artifact-exposed (§5) |
| 22:59–23:15 | **Theory abandoned. "It was wrong. Very wrong."** | Credit due |
| 23:15–23:53 | Effect retained; Pac-Man thruster in styrofoam → no B field, no current, "no power," still thrust | **The escalation** (§6) |
| 23:53–24:19 | Rebuilt on classical energy conservation, electric fields only | `[PENDING]` — need the maths |
| 24:19+ | Slideshow | Image 1 logged, Appendix A |
| 29:40–29:59 | Foam adopted to stop room-air ionisation depositing charge on the article — "it nulls my fields" | See §6.5 — rationale is better than it first appears |
| 36:01–36:28 | "We can turn the power off and the engine stays on" | Explained at 1:57 — **§12.2** |
| 37:16–37:51 | $150 DIY thruster, free build video, 0.1 mN on a string in air | **§12.6 — the replication paradox** |
| **38:20–39:24** | **The mechanism: electrostatic pressure × area, small tips vs large foil** | **§12.1 — the specific error** |
| 40:13 | Star Trek model, 2.5 mN, "first warp drive ship in history" | Aurigema's register again (§11.9) |
| 43:04 | "We are over unity" — 1.8 lb thrust per 1 lb of cell | **Terminology landmine — §12.5** |
| 46:04–47:28 | Patent 1 held 3.5 yrs; patent 2 rejected for violating conservation of momentum | §12.8 |
| 48:22 | "Peer review is designed to shut down the flow of information" | §12.9 |
| 52:06–54:16 | Vacuum chamber, 10⁻⁶ torr; "our system loves vacuum" | §12.3 |
| 55:13–55:31 | 1.7 unity is **active material only**, excludes framing, supply, tape | Answers §9.5's open question |
| 59:19–1:03:18 | **3U CubeSat proposal, ~$300k–$1M** | **§12.11 — the actual falsification path** |
| 1:31:03–1:31:55 | Buhler: telepathy and clairvoyance are real, practised with family | §12.10 |
| 1:54:17–1:54:53 | **HV supply mounted inside the article, inside the Faraday cup, on the pendulum** | **§12.3 — better than §7.6 proposed** |
| 1:56:48 | "90% of the time the darn force is there" | §12.10 |
| **1:57:07–2:00:26** | **Frozen charge driven into dielectrics; 2–4 mN persists for days, power off** | **§12.2 — the decisive passage** |
| 2:03:04–2:03:40 | Biefeld–Brown overlap; **"our effect is much much weaker than ion wind"** | §12.1, §12.6 |
| 2:13:18–2:15:31 | Load cells, 0.1 mm deflection; 12 hr water desorption before thrust appears | §12.3 |
| 2:23:39 | **"About 0.5 Earth unity"** — system level | §12.5 |
| 3:00:09–3:03:18 | Asteroid deflection use case | Reasonable given the premise |
| 30:08 | "That and that piece of wire produce thrust. It's in our patent." | Patent located, §10.1 |
| 31:40–31:51 | **"To date about 50 millinewtons"** — "enough to lift two pieces of paper" | **First hard number.** Arithmetic in §9 |
| 31:58–32:16 | 1000 units → 5 N → Mars in 3.5 days at "38 g" continuous | Array scaling error (§9.4) |
| 32:30–33:00 | Chemical rockets to orbit, then Exodus everywhere; the "old car floored" analogy | Sound intuition, no objection |
| 33:10–33:35 | **45 t vehicle, 30 t propulsion, 15 t payload** (Aurigema) | Makes it checkable — **§9.5, the 47 GW problem** |
| 33:35–34:13 | 38 g, coffee in the mug, ~1M mph at midpoint | **"38 g" = 0.38 g. Confirmed, not a transcript error (§9.3)** |
| 34:17–35:05 | Turnover, direct descent, hover at Mars | Correct torch-ship mission design |
| 35:14–35:26 | Constant gravity load; 3.5 days of GCR not 9 months | Correct; they decline to overclaim |

---

## 2. The physics he gets right (and it's most of it)

### 2.1 Field momentum is real and cashable

Static crossed **E** and **B** fields store linear momentum with density

```
g = ε₀ (E × B) = S / c²
```

A bar magnet at 10 kV genuinely holds nonzero field momentum. This is Griffiths ch. 8, not fringe. His framing — "anytime you have an electric field and a magnetic field in the same spot, you have a momentum" — is accurate.

### 2.2 Hidden momentum is real and he characterises it correctly

A current loop in an external **E** field carries **mechanical** momentum

```
p_hidden = m × E / c²
```

Origin: charge carriers on the high-potential side of the loop are relativistically heavier than those on the low-potential side. Same current, asymmetric momentum flux, net mechanical momentum — equal and opposite to the field momentum. His gloss ("counteracts any field momentum in your system *if the charges are allowed to flow*") is fair, and the conditional is the hinge of his whole argument.

### 2.3 The Feynman disk is described accurately

Charged beads on an **insulating** disk inside a solenoid. Current off → induced circumferential **E** torques the beads → disk spins. (Minor correction: *Lectures* Vol. II §17-4, revisited §27-6, aimed at Caltech sophomores rather than set as graduate homework. Immaterial.)

Angular momentum stored in the field before switch-off:

```
L = ε₀ ∫ r × (E × B) dV
```

The disk's mechanical gain exactly equals the field's loss.

---

## 3. Failure point one: the Feynman disk is not a loophole

He reads the disk as a configuration where hidden momentum is absent — correct, the beads are static charges on an insulator, no mobile carriers, no Shockley–James term. He then treats this as an existence proof that field momentum can be converted to motion without cancellation.

**The disk is the opposite of a loophole. It is the canonical demonstration that the ledger balances.** Nothing is unaccounted for; the field carried the angular momentum the whole time, and the paradox is purely pedagogical — it *feels* like angular momentum appears from nowhere.

There is a genuine linear/angular asymmetry here, but it cuts against the propulsion argument:

- **Linear** is constrained by the **centre-of-energy theorem**: total momentum is zero iff the centre of energy is stationary. Follows from ∂_μT^{μν} = 0. Material-independent.
- **Angular** has no corresponding theorem, because a spinning body's centre of energy doesn't move.

So the angular case is unconstrained *precisely because rotation displaces nothing.* The disk demonstrates a capability that requires no new physics and that we already fly: **it is a reaction wheel.** Attitude control, not propulsion. Every satellite has three.

**And it is one-shot.** Turn the solenoid back on and the induced field torques the beads the other way; net over a closed cycle is zero. Ratcheting it requires shedding the charge while B is off — but the shed charge carries the angular momentum away with it, at which point you have propellant and you are doing conventional electrostatic ion propulsion.

---

## 4. Failure point two: hidden momentum was never the real obstacle

### 4.1 The centre-of-energy theorem, not Shockley–James

His strategy is: find a configuration where hidden momentum does not apply, and the field momentum survives uncancelled. The bound-charge/static-charge route is not a stupid move — there is a real AJP literature on whether intrinsic spin dipoles carry hidden momentum the way current loops do.

But the cancellation does not *rest* on hidden momentum. Hidden momentum is the **bookkeeping** showing how the books balance in the current-loop case. It explains the mechanism; it is not the reason a mechanism must exist. The reason is the centre-of-energy theorem, which follows from conservation of the stress-energy tensor regardless of what the device is made of.

**Consequence:** eliminating hidden momentum does not buy thrust. It means the compensating momentum is somewhere else — typically mechanical stress in the structure holding the thing together, or momentum transferred to the surrounding medium.

### 4.2 Momentum has to *leave*

"If you change that momentum, you get a force" — true, but force *on what*? Changing field momentum transfers momentum between field and matter **inside** the device. Sustained thrust requires momentum to exit the system boundary. In a closed cycle, whatever is transferred on the upstroke is recovered on the downstroke; time-average zero.

This is precisely where EmDrive-class claims fail, and where the historical E×B thrusters he cites (Brown's asymmetric capacitors, "lifters") failed: momentum *was* leaving — as ion wind, in air — and the effect vanished in hard vacuum.

---

## 5. The 140 kV needle — the worst possible geometry for a clean claim

> "It moved about 3 or 4 feet in the air. It was 140,000 volts, but it was covered in tape."

Every element of this description is a known false-positive generator:

- **Needle geometry.** A sharp point is the optimal corona-discharge emitter. Field enhancement at the tip scales roughly as 1/r. This is how you *build* an ion thruster deliberately.
- **In air.** Corona → ion wind → momentum dumped into the atmosphere. Textbook electrohydrodynamic thrust.
- **140 kV.** Far above corona onset for any sharp electrode in atmosphere (~kV/mm scale).
- **Covered in tape.** Dielectric surfaces accumulate charge; surface charge migration and triboelectric effects add irreproducible electrostatic forces toward grounded objects.
- **"Moved 3 or 4 feet."** Free flight, not a calibrated balance. No force measurement exists here — only a displacement, in air, with an unmeasured ion current.

This is Brown's lifter, rediscovered. It is not evidence of anything anomalous. He appears to know this, which is presumably why the work moved to the styrofoam configuration.

### 5.1 The photographs make this worse (Images 4–5)

Two frames of the needle experiment were supplied on 2026-08-25 and they confirm the reconstruction above, with one detail that is worse than anything the transcript conveys.

**The device is suspended by its own high-voltage cable.** The visible red HV lead runs down from above and *is* the pendulum string. There is no separate suspension.

Aurigema himself identifies this artifact class, at 1:53:41–1:54:06 — the transcript's most technically astute passage:

> *"You put 5,000 volts on a wire... if the wire is thin, it can actually physically change shape because the electrostatics inside want to get away from each other... they can actually make wires change shape. So if you have wires running to your test article, when you power it up, a source of false information could just be the fact that you powered it up."*

He is right, he took it seriously, and he eventually solved it properly by mounting the entire supply inside the article on the pendulum (§12.3). **But the founding experiment — the one that made Buhler say "that sucker's moving" and restart the whole programme — has that exact artifact in its purest available form, because the charged conductor and the suspension are the same object.** At 140 kV, on a thin lead, this is not a small correction.

**Second: the 6 mN was never measured.** The frames show a ruler lying flat on a styrofoam block on the floor, positioned to read horizontal displacement. Per 2:01:03, *"when you do the math and you do the weight, that thing was making about six millinewtons."* So the figure is inferred from pendulum deflection, F ≈ mg·tan θ — and **neither the mass nor the deflection angle appears anywhere in the record.** It belongs in §12.4's ledger flagged as derived, not measured.

**Third, the arithmetic.** Applying §9.2 to this device: 6 mN of ion wind at 5–20 N/kW needs 0.3–1.2 W, which at 140 kV is **2–9 µA**. Corona onset for a sharp point in air is a few kV; at 140 kV a needle is a vigorous emitter. A current of a few microamps is entirely invisible on any supply front panel. The conventional explanation requires nothing improbable.

**Fourth, a discrepancy worth flagging rather than resolving.** At 22:20 the claim is *"it moved about 3 or 4 feet in the air."* Using the ruler for scale, the swing between the two supplied frames appears to be on the order of 10–20 cm, not 90–120 cm. This may be a different or later article, and single frames are poor evidence of amplitude — but the apparent gap is roughly 5–10× and should be asked about rather than assumed away.

**Net:** the observation that started the programme is the least reliable data point in it — air, 140 kV, needle geometry, unshielded, suspension by the energised cable, force inferred rather than measured. Everything they built afterwards is better than this. That is to their credit as a trajectory, and it is also why this particular experiment should carry no evidential weight at all.

---

## 6. The escalation: "no current, no power, still thrust"

This is the most important passage so far and it is worth being precise about why.

> "We had no more B field, which means we had no more current... you don't have any power because power is voltage times current. So you're not expelling a lot of power and you're getting thrust."

He presents low power as *convenient* — easier to build, fewer confounds. **It is the opposite. It maximises the strength of the claim.**

### 6.1 The photon bound

Any propellantless device is bounded by the perfect photon rocket:

```
F/P = 1/c = 3.336 nN/W = 3.34 µN/kW
```

As P → 0, the permitted thrust → 0. So "we have essentially no power and we're getting thrust" is not a simplification — it is a claim of a violation whose *magnitude* grows as the power falls. If he is drawing microwatts and producing micronewtons, that is a violation by six orders of magnitude, not a low-efficiency thruster.

### 6.2 The trap: how little current ion wind needs

Electrohydrodynamic thrust in air runs roughly **5–20 N/kW** — around a million times more thrust-efficient than a photon rocket. Therefore:

| Leakage current at 140 kV | Power | EHD thrust if it's ion wind |
|---|---|---|
| 1 µA | 0.14 W | ~0.7–3 mN |
| 100 nA | 14 mW | ~70–300 µN |
| 10 nA | 1.4 mW | ~7–30 µN |

A current small enough to read as "zero" on a supply's front panel is more than sufficient to produce easily visible thrust. **"No measurable current" is not the same as "no current," and the gap between them is exactly the size of the effect being claimed.** This is the single most likely resolution and the first thing to eliminate.

Required: a picoammeter in the HV return line, logged continuously during thrust runs. Not a supply readout.

### 6.3 Stored energy is nowhere near enough

If the device is genuinely drawing nothing, the only available energy is electrostatic:

```
U = ½CV²
C ≈ 10 pF, V = 140 kV  →  U ≈ 0.10 J
```

For scale, sustaining 1 mN of genuinely propellantless thrust at the photon limit would require ~300 kW. The stored energy is not in the same universe. Any sustained thrust must therefore be drawing power from somewhere, which returns us to §6.2.

### 6.4 Styrofoam is not vacuum

Embedding the device in foam suppresses *conduction* current but introduces a new set of confounds:

- Expanded polystyrene is ~95%+ air by volume. Corona in the voids is not excluded.
- EPS is an excellent triboelectric charge acceptor. Charged foam near a charged device produces large, drifting, irreproducible forces.
- **Dielectrophoresis:** a charged body in a dielectric medium with a field gradient experiences net force toward higher field. This produces real thrust — against the foam.
- **Electrostriction / Maxwell stress** deforms the foam, which pushes back mechanically.

Critically: **if the device pushes on the foam, the foam is part of the system.** The centre-of-energy constraint applies to device + foam + container. This is not propellantless; it is pushing on a very light solid instead of on air. The measurement must weigh the whole assembly, or the foam must be absent.

### 6.5 The stated rationale (29:40–29:59) — and what it concedes

He later gives the actual reason for the foam, and it is not the one implied earlier:

> "Sometimes these air tests are terrible cuz you'll ionize the air and then the charges from the room will get to the outside of your test article... and mess with your fields. So, how do I keep the air away from my damn thruster? It nulls my fields."

Two things follow.

**First, this is an explicit admission that ambient charge couples to the device.** He is describing corona ionisation of the surrounding air and subsequent charge deposition on the exterior of the test article. That is the signature of the exact artifact class in §5 and §6.2. He has observed it directly.

**Second — and this is a correction to the earlier reading in this document** — his fuller rationale elsewhere is more defensible than the transcript alone suggests. He has stated publicly that the foam serves two deliberate purposes: <cite index="2-1">preventing sparking at the high voltages involved, since other lightweight materials break down and damage the test article, and preventing the air itself from breaking down and creating an ion wind</cite>. He is on record: *we do not want ion wind.*

That is the correct concern, correctly identified, and the foam is a reasonable — if imperfect — engineering response to it. This document's earlier framing treated the foam as a post-hoc configuration found by trial. That was too harsh. It is a deliberate countermeasure against the exact artifact class in §5.

**The residual objection is narrower but still stands:** foam does not remove air, it immobilises it. Cured foam voids sit at roughly atmospheric pressure, and suppressing bulk convective ion wind is not the same as suppressing charge transport through the void network. The foam addresses the *dominant* form of the artifact while leaving a weaker channel open. This matters only because the air-ambient configuration is not where the load-bearing claim rests anyway — see §9.4.

### 6.6 Spray polyurethane foam is a worse medium than EPS, not a better one

The transition from a "vat of styrofoam" (EPS beads) to sprayed polyurethane — the "brain blob" — introduces three confounds that EPS does not have:

- **Outgassing.** Freshly cured SPF releases blowing agents (pentane, HFCs, CO₂) for days to weeks, at rates that decline with age. An irregular blob outgasses **asymmetrically**. This is real gas thrust from a real reaction mass. Order of magnitude: a leak of ~1 µg/s at ~100 m/s gives ~0.1 µN. **If the claimed thrust is micronewton-scale this is a live and probably leading candidate; at millinewton scale it is insufficient alone.** The diagnostic is unmistakable: thrust that decays monotonically over days as the foam cures out, and that partially recovers if a fresh blob is applied.
- **Charge trapping and slow decay.** Polyurethane is a strong triboelectric acceptor with very high volume resistivity. Charge injected into the foam bulk persists for hours. Any thrust from trapped charge will show hysteresis and slow drift rather than clean on/off switching.
- **Uncontrolled geometry.** A hand-sprayed blob has no reproducible shape, mass, or dielectric distribution. Dielectrophoretic force depends on ∇|E|², which depends entirely on that uncontrolled geometry. Two blobs will not give the same result, and that irreproducibility will look like sensitivity to some subtle parameter rather than what it is.

The foam also **defeats visual inspection** for corona — you cannot see a glow discharge occurring inside an opaque blob, and the voids in cured SPF are at roughly atmospheric pressure.

---

## 7. Discriminating tests — what would actually settle it

Ordered by how cheaply they kill the most likely artifacts.

1. **Picoammeter on the HV return.** Log current to the nanoamp during thrust. Compute F/P. If F/P sits in the 5–20 N/kW band, it is EHD and the question is closed.
2. **Hard vacuum.** Below ~10⁻⁵ torr, with a bakeout and no foam. Corona and ion wind vanish; if thrust survives, everything changes.
3. **180° reversal on the balance.** Rotate the device in place. Thrust should reverse; spurious forces (cable stiffness, thermal, electrostatic pull toward chamber walls) generally do not.
4. **Dummy load.** Same voltage, same power, same thermal profile, geometry scrambled. Should null.
5. **Faraday cage / grounded shield** at varying distance. Real internal thrust is distance-independent; image-charge attraction to the chamber is not.
6. **Cable management.** HV cable stiffness changes measurably with applied voltage and is a classic false positive on torsion balances. Route through the pivot axis; test with dummy cables.
7. **Thermal null.** Let the device reach equilibrium; look for thrust that decays with the thermal transient (convection, outgassing).
8. **Photon bound check.** Report F/P explicitly in every run. If it exceeds 3.34 µN/kW, state the violation factor plainly.
9. **Foam age series.** Same device, blobs cured 1 day / 1 week / 1 month / 1 year. If thrust declines with cure age, it is outgassing. Cheap, fast, and kills or clears the leading candidate outright.
10. **Foam substitution.** Replace SPF with a machined, aged, geometrically identical block of the same density — and separately with a solid dielectric of much higher density. If thrust tracks *shape* it is field geometry; if it tracks *foam-ness* it is gas or trapped charge.
11. **Charge decay monitoring.** Non-contact electrostatic voltmeter on the foam surface during and after runs. Establishes whether thrust correlates with surface potential or with applied voltage — these are separable and they answer different questions.
12. **Ground-plane distance sweep.** Vary the separation between the device and any copper sheet or conductive surface (see Appendix A). Image-charge attraction scales steeply with distance; internal thrust does not.
13. **Sidereal variation.** If the force is sourced from the vacuum, it requires a preferred frame (§11.4). Log thrust magnitude against sidereal time and against device orientation over weeks. A real vacuum-sourced effect should modulate; a lab artifact should track the *solar* day (HVAC, humidity, mains) instead — and the two drift apart by four minutes daily, which is exactly what makes this test clean. **Costs nothing but patience, requires no new apparatus, and would be the first forward prediction the programme has ever tested.**
14. **Residual gas analyser during thrust.** Field emission from the sharp fin geometry liberates adsorbed gas from surfaces — **electron-stimulated desorption** — which is a real momentum source with real reaction mass. It survives high vacuum (it needs adsorbed monolayers, not ambient gas) and it survives power-off (trapped charge maintains the field, which maintains emission). If thrust correlates with a partial-pressure rise in H₂O, CO or H₂, it is ESD. **This artifact class appears nowhere in three hours of transcript and was missed by this document until the CENA pass.** See `Buhler-replication-CENA.md` §L10/F3.
15. **Instrument the electrode deformation.** At 10⁸ V/m the Maxwell stress is 44 kPa — roughly 442 N across a 10×10 cm device. The claimed 50 mN is **~10⁻⁴ of that internal force**. Any mechanical path coupling 0.01% of it outward — plate deflection, electrostriction, mount strain, Kapton creep — reproduces the result. Strain-gauge or interferometric monitoring of the electrodes during a run would separate deformation from thrust. **No control for this exists anywhere in the record.** See CENA §L7/D6.

Historically, nearly every claim in this space died on 2, 3, or 6. Given the images, **9 and 12 are now the highest-yield-per-hour tests available.**

---

## 8. Structural assessment of the argument

The pattern across all four extracts is consistent and worth naming:

> **Correct physics, correctly cited, with the load placed on a step the cited physics does not support.**

- Field momentum is real → yes, but it doesn't leave the device.
- Hidden momentum can be sidestepped with bound charge → yes, but hidden momentum wasn't the binding constraint.
- The Feynman disk converts field momentum to motion → yes, and it's a reaction wheel.
- Low power makes it simpler → no, it makes the claim maximal.

The abandonment of the field-momentum theory (§1, 22:59) removes the only part of the programme that made falsifiable predictions. What remains is: *something moves, we don't know why, we're rebuilding from energy conservation.* That is a legitimate research posture. It is also, evidentially, the weakest possible one, because it converts every measurement into an artifact-elimination problem with no theory to constrain the search.

**The question that matters is not whether he is honest — he plainly is — but whether the styrofoam configuration has been run on a torsion balance in hard vacuum with the return current logged.** Everything else is preamble.

> **Update following §10.** The vacuum half of that question is answered: ~2,000 vacuum runs are claimed. The current half is not — no F/P figure appears anywhere in the public record. And the whole question has been superseded by a better one: **not whether *he* has run the test, but whether anyone else has.** As of May 2026, nobody had. That, and not any argument in §3–§6, is where the claim currently sits.

---

## 9. The 50 mN figure — arithmetic

At 31:40 he gives the first hard number in the transcript: **"to date about 50 millinewtons."** Everything in this section follows from that one figure.

### 9.1 Sanity-check the paper analogy

He calibrates it as "enough to lift two pieces of paper." One sheet of A4 at 80 gsm is 0.0623 m² × 80 g/m² = **4.99 g**, weighing 49 mN. So 50 mN lifts *one* sheet, not two. US Letter at 20 lb bond is ~4.5 g, 44 mN — again about one sheet. The analogy is off by roughly 2×. Trivial in itself, but it is the kind of factor-of-two that should not appear in a rehearsed public figure, and it is worth noting because §9.3 contains a much larger transcription problem.

### 9.2 What 50 mN means against the two relevant bounds

**Against the photon bound.** A perfect photon rocket delivers 3.336 nN/W. To make 50 mN legitimately propellantless requires

```
P = 0.05 N ÷ 3.336×10⁻⁹ N/W = 1.5 × 10⁷ W  ≈  15 megawatts
```

If the device draws anything on the order of a watt, the claim is a violation of momentum–energy accounting by a factor of ~1.5 × 10⁷. This is the number that should be quoted whenever the claim is described, because it is the actual size of the assertion. "Fifty millinewtons" sounds modest. "Fifteen million times the photon limit" is the same statement.

**Against the ion-wind bound.** Electrohydrodynamic thrust in air runs 5–20 N/kW. So 50 mN of ion wind requires

```
P = 0.05 N ÷ (0.005 to 0.02 N/W) = 2.5 to 10 W
at 140 kV  →  I = 18 to 71 µA
```

**This is the single most important number in the document.** Tens of microamps at 140 kV reads as 0.02–0.07 mA — indistinguishable from zero on any supply whose current display resolves to 0.1 mA. It is also exactly the current a sharp electrode at 140 kV in atmosphere would draw from corona. So in the *air-ambient* configuration, 50 mN is precisely what conventional physics predicts, drawn from a current small enough to be honestly described as "no current."

The gap between "no measurable current" and "no current" is 15 megawatts wide, and it is entirely filled by a supply's display resolution.

### 9.3 The Mars claim — "38 g" decoded

The transcript says "38 g continuous acceleration," repeatedly and consistently across both speakers. **This document initially logged that as a transcription error. It is not — it is a speaker convention, and the 33:00–35:26 passage proves it three separate ways.**

The decisive line is at 34:49: *"your engines can make say 39 gs and the Mars surface is only pulling at you at 38, that means you go down slowly."* Mars surface gravity is **0.376 g**. So "38" here unambiguously means **38% of one g**. They are saying "g" where they mean "percent of g," and the vehicle spec was evidently chosen so that thrust-to-weight just exceeds Mars gravity, permitting a powered hover descent.

Two independent confirmations:

- **"Pour your coffee in your mug the whole time."** At 0.38 g, yes. At 38 g you are a red smear — human tolerance is roughly 9 g briefly and ~50 g is reliably fatal.
- **"At the midpoint we're doing about a million miles an hour."** Check it: v = a·t_half = 3.73 m/s² × 151,200 s = **564 km/s = 1.26 million mph**. Their figure is right.

And the trajectory closes:

```
d = a·t_half² = 3.73 × (151,200)² = 8.53 × 10¹⁰ m = 0.57 AU
Mars at close approach ≈ 0.52 AU  ✓
```

**Every number in the Mars passage is internally consistent at 0.38 g.** The trajectory arithmetic, the midpoint velocity, the hover condition at Mars, and the comfort claim all agree. Credit where due — this is not hand-waving, it is a correctly worked brachistochrone. The unit convention is sloppy to the point of being misleading to a listener, but the underlying calculation is sound.

*(Note for future transcripts: treat "N g" from these speakers as N% of g until proven otherwise.)*

### 9.4 Where the scaling argument actually fails

"Put a thousand of those together and you have a 5 Newton thruster, and you put a 5 Newton thruster behind anything and you can be at Mars in three and a half days."

The error here is subtle and it is the standard one in this field. **Acceleration of an array does not improve with array size.** Thrust scales with N, but so does mass:

```
a_array ≈ g × (m_thrusters / m_total)
```

So the array's acceleration is capped by the **thrust-to-weight ratio of a single unit**, degraded by whatever fraction of the vehicle is payload, structure, and power. Adding units buys total force, never acceleration.

This means "5 N behind anything" is wrong as stated — 5 N gives 0.38 g only on a vehicle massing **1.34 kg total**, thrusters included. Worked the other way: to hit 0.38 g you need the thruster array to be ≥38% of all-up mass *and* each unit to have T/W ≥ 1.

Aurigema evidently understands this — at 33:10 he specifies a **45 tonne vehicle with 30 tonnes of propulsion**, i.e. 67% propulsion fraction. That is the correct shape of answer. It is priced out in §9.5.

Which is exactly why his headline claim elsewhere is stated as "1g." That is not a force, it is a **thrust-to-weight ratio of the test article** — and it is the only figure that matters for the Mars extrapolation. Note also that 50 mN equals the weight of a 5.1 g mass, so "1g thrust" and "50 mN" are the same measurement on a ~5 g article. They are consistent. But media reporting of "1g thrust" as though it were a force is a category error, and the Mars number depends entirely on the ratio surviving the addition of structure, power, and payload — which has not been demonstrated. As one summary of the programme puts it, < cite index="11-1">these are extrapolations, not demonstrated performance</cite>.

### 9.5 The 45-tonne vehicle — the argument that does not depend on momentum at all

At 33:10 Aurigema supplies the missing masses: **45 metric tonnes all-up, 30 tonnes of propulsion system, 15 tonnes of spacecraft, crew and payload.** This finally makes the extrapolation checkable.

**Required thrust:**
```
F = m·a = 45,000 kg × 3.73 m/s² = 168 kN
```

**Required specific thrust of the propulsion system:**
```
168,000 N ÷ 30,000 kg = 5.6 N/kg
```

Against a device-level claim of ~9.8 N/kg (the "1g" figure), that leaves a factor of 1.75 in hand. **On mass alone the extrapolation is not absurd** — provided the 1g ratio survives the addition of high-voltage supplies, wiring, structure and thermal management, which has never been tested. Worth stating plainly, because it is the one part of the vision that arithmetic does not immediately kill.

**Then there is the energy.**

This is the argument that matters most, because **it is entirely independent of momentum conservation.** Grant the drive everything — grant that it pushes on the quantum vacuum, that momentum balances in some unobservable ledger, that §4's centre-of-energy theorem has an exemption nobody has found. The vehicle still has to *acquire kinetic energy*, and that energy has to come from somewhere.

```
Midpoint velocity:  v = 564 km/s
Kinetic energy:     KE = ½ × 45,000 kg × (5.64×10⁵ m/s)² = 7.2 × 10¹⁵ J
```

**7.2 petajoules — about 1.7 megatons of TNT.** And deceleration is not free: there is no regeneration on a torch trajectory, so the same energy must be spent again shedding it. Total ≈ 14.3 PJ over 302,400 s:

```
Average power = 1.43×10¹⁶ J ÷ 3.024×10⁵ s = 4.7 × 10¹⁰ W = 47 gigawatts
```

**47 GW continuous, from 30 tonnes** — a power density of ~1.6 MW/kg. For calibration, space fission reactor designs run around 1 kW/kg; the best conceivable nuclear-electric systems are three orders of magnitude short. Only nuclear *explosives* reach that power density, and they do it once.

Second calibration, via the photon limit: 168 kN of genuinely propellantless thrust needs 168,000 ÷ 3.336×10⁻⁹ = **5 × 10¹³ W = 50 terawatts**, roughly seventeen times humanity's entire electrical generating capacity.

**This is the load-bearing objection to the vision, and it is thermodynamic rather than mechanical.** The programme's central selling point — *"you're not expelling a lot of power and you're getting thrust"* (23:45) — is exactly what makes the Mars scenario impossible. You cannot deposit 14 petajoules of kinetic energy into a spacecraft using negligible power, whatever the momentum ledger says. Either the device draws tens of gigawatts, or it does not reach Mars in 3.5 days. It cannot be both, and no theory of vacuum momentum transfer alters this, because **energy conservation is a separate constraint from momentum conservation** and none of the proposed mechanisms address it.

If the answer is that the energy also comes from the vacuum, the claim has escalated from a propulsion breakthrough to a perpetual motion machine of the first kind, and should be described as one.

*Caveat for fairness:* this objection bites the 45-tonne Mars vision, not the 50 mN bench result. A 5 g article at 50 mN over short runs involves trivial energy and is not touched by this argument. The two must be assessed separately — §9.2 for the bench claim, §9.5 for the vision.

### 9.6 Smaller items from 32:30–35:26

- **The car analogy (32:43).** "Floor it and never run out of gas, you'll be the fastest car on the planet in a few hours." Correct and well-chosen intuition for continuous low thrust. No objection.
- **"Land on any other object in the solar system" (32:33).** Checkable, and it is an overreach at vehicle level. Powered landing requires T/W > local surface gravity, and the 45 t vehicle of §9.5 has T/W = 0.38. That covers the Moon (0.165 g), Mars (0.376 g, marginally), Mercury (0.38 g, marginally), Ganymede, Titan, Io, and every asteroid — but **not Venus (0.90 g), not Earth (1 g), not Jupiter (2.53 g)**. "Any other object" should read "most solid bodies." At the *device*-level claim of 1 g it would extend to Venus and Earth, but only for a vehicle that is entirely thruster with no payload. Minor, but it is the same array-scaling confusion as §9.4 reappearing.
- **"Orbits are so 20th century," dropping straight in (34:17).** Correct for a torch ship. Constant-thrust vehicles genuinely do not need orbital mechanics in the conventional sense.
- **"Same gravity load the whole time" (35:14).** Correct, with one skipped exception: turnover is a freefall interval.
- **Radiation (35:26).** Right direction — GCR dose scales roughly with exposure time, so 3.5 days versus 9 months is a real order-of-magnitude gain. They also decline to overclaim: *"we haven't solved any of the big problems."* Fair.
- **Hover-and-land at Mars (34:58).** Follows correctly from T/W > Mars gravity. Internally consistent.

The pattern in this passage is worth naming: **the mission-design engineering is competent.** Brachistochrone, turnover, hover descent, dose scaling — all handled correctly. The problem is not that they cannot do the arithmetic. It is that all of it is downstream of a device whose energy budget has never been stated.

---

## 10. External record as of August 2026

The transcript is a snapshot. The published context materially changes the assessment in both directions, and the earlier sections of this document were written without it.

### 10.1 The patent

Filed by **Andrew Neil Aurigema and Charles Buhler**. < cite index="4-1">The claimed mechanism is a net electrostatic pressure force whose magnitude depends on the geometry of the conductive surfaces, the applied voltage, and the dielectric constant of material in the gap between electrodes, with a stated use case as a spacecraft thruster operating in vacuum</cite>. Exodus < cite index="10-1">filed several patents between 2023 and 2024, including asymmetric electrode geometries for unidirectional force</cite>. A patent documents a claim; it validates nothing.

### 10.2 Vacuum testing IS claimed — correcting this document

**This is the most significant correction to the earlier sections.** §7 listed hard vacuum as the decisive untried test. It is claimed to have been done, extensively: < cite index="18-1">Buhler stated in a March 2026 interview that he had conducted roughly 2,000 experiments in vacuum chambers</cite>, and the programme < cite index="7-1">reports over 4,500 tests overall, with thrust exceeding 1g claimed in vacuum</cite>. He < cite index="14-1">addresses the ion-wind objection directly, citing vacuum testing and multiple verification methods</cite>.

So the air-and-foam configuration in Image 1 and in §5–§6 is **not** where the load-bearing claim rests. Those are demonstration and development articles. Any assessment that stops at "it's ion wind in a foam blob" is attacking the weakest version of the claim and should be discarded. §7's test list retains value as a checklist for what a replication must control, not as a list of things nobody thought of.

### 10.3 The theory has now changed twice

- **~2000–2016:** field momentum, **E**×**B**, hidden momentum. *Abandoned on tape at 22:59 — "it was wrong, very wrong."*
- **~2016–2023:** classical energy conservation, electric fields only. The transcript's present tense.
- **2024–present:** < cite index="5-1">third-order QED perturbation theory, with the force attributed to momentum transfer from the quantised vacuum</cite>.

Three incompatible mechanisms for one persistent empirical claim, over roughly twenty-five years. This is not automatically disqualifying — anomaly-first research legitimately outruns its explanations — but the pattern means the theory is tracking the effect rather than predicting it. No version has yet produced a falsified-or-confirmed quantitative prediction in advance.

**On whether they claim a "new force":** they do, explicitly and in those words. < cite index="18-1">Buhler told The Debrief that the discovery of a New Force is fundamental, in that electric fields alone can generate a sustainable force onto an object and allow centre-of-mass translation</cite>. This sits awkwardly beside the QED framing, which claims the opposite — a known mechanism, correctly computed. Both positions are live in the public record simultaneously. See §11.7 for why each inherits a different fatal problem.

Note also the drift in what conservation means across those versions. The current position is that < cite index="14-1">the system conserves quantum momentum even though that momentum is not directly observable or manipulable in the way classical momentum is</cite>. An unobservable conserved quantity is not a testable constraint, and this is the point at which the argument stops making contact with the centre-of-energy theorem in §4.1 rather than answering it.

### 10.4 The post-power-off persistence

< cite index="18-1">Buhler has reported that under some conditions apparent thrust persisted after the device was switched off.</cite>

He presents this as anomalous and supportive. Trapped charge in a dielectric relaxes over exactly these timescales; so do thermal gradients, outgassing transients, and mechanical creep in a balance suspension.

> **Superseded by §12.2.** The full transcript gives their explanation in detail: charge is driven into dielectrics and remains after power-off, and the effect is field-driven regardless of the field's source. This is *coherent on their own theory* rather than an unexplained anomaly — so the artifact reading and their reading fit the same data equally well, and this observation does not discriminate between them. It does, however, produce the sharpest energy objection in the document. See §12.2.

### 10.5 The actual state of the evidence

< cite index="13-1">Popular Mechanics reported in May 2026 that there was no published independent replication using an outside lab's own apparatus, instrumentation, and uncertainty budget.</cite> That remains, as of this writing, the crux. The peer-reviewed paper has been < cite index="7-1">described as planned</cite> since at least 2024 and < cite index="5-1">was expected "later in the year" as of mid-2025</cite>; no publication has appeared.

To his credit, Buhler's own stated position is the right one: < cite index="12-1">he has said his team would welcome anyone with the proper equipment to attempt replication, and that validation in high-vacuum systems would be helpful</cite>. And < cite index="16-1">he has stated that if hardware moves under its own power in space with no reaction mass, the debate is over</cite>. That is the correct test and he is proposing it himself.

**The gap is therefore not one of nerve or honesty. It is that ~2,000 in-house vacuum tests, however careful, are not a substitute for one test by someone else.** < cite index="18-1">More experiments by the same team do not address independent replication, which is where the claim runs into its biggest problem.</cite> A systematic error is perfectly reproducible; reproducibility within one lab measures consistency of method, not correctness of method. This is why the Dresden group's null results on EmDrive mattered — different apparatus, different error budget, different people.

### 10.6 Source-quality warning

Almost the entire public record runs through APEC (Alternative Propulsion Engineering Conference), The Debrief, NextBigFuture, and downstream aggregators. None is peer-reviewed; APEC is an advocacy venue. Treat quoted thrust figures as claims-as-reported, not measurements.

One further signal worth logging without over-weighting: an April 2026 paper circulated attempting to explain the Exodus force via < cite index="15-1">Randell Mills' GUT-CP "space drive" mechanism, framing the two propellantless claims as expressions of one principle</cite>. Mills' hydrino programme is long-discredited. Buhler did not write this and cannot be held responsible for who adopts him — but the direction of adoption is information about the epistemic neighbourhood the claim now occupies.

---

## 11. The steelman — the claim as its proponents would state it

**Why this section exists.** Everything above is assessment. Without the authors available to correct misreadings, there is a standing risk that this document argues against a version of the idea they would disown. This section attempts the strongest available reconstruction of their positive case, flagged throughout for how much is theirs and how much is this document's inference.

### 11.1 Asymmetric electrostatic pressure — the Maxwell stress framing

> **Note:** this subsection reconstructs their case in its strongest form. They state it themselves at 38:20–39:24, in a weaker and more specific form — see **§12.1**. The reconstruction below is more charitable than what they actually argue.

Their patent language is *net electrostatic pressure force as a function of electrode geometry, applied voltage, and the dielectric constant of material in the gap.* The formal home for that is the **Maxwell stress tensor**:

```
T_ij = ε₀(E_i E_j − ½ δ_ij E²)
```

Force on any volume = ∮ T·dA over an enclosing surface. Electrostatic pressure ε₀E²/2 is real, geometry-dependent, and scales as E² — which matches their stated scaling exactly.

**Their claim, as best reconstructed:** if geometry and materials are arranged so the internal stresses do not perfectly cancel, a residual force survives on the assembly as a whole.

**The standard answer:** for a closed, isolated electrostatic system the surface integral over any surface enclosing *everything* vanishes. No self-force. The asymmetry is real and produces genuine internal stresses; it does not produce a net external force, because every stress has a matching counter-stress transmitted through the structure.

**Where this is genuinely non-trivial:** the cancellation is easy to state and hard to *measure*. A device where the compensating force is transmitted through a mechanical support rather than through the field can look, on a badly configured balance, exactly like net thrust. This is why §7 is a list about measurement rather than about theory.

### 11.2 Bound versus free charge — why they think it matters

They repeatedly distinguish free charge in conductors from bound charge in dielectrics, and treat both as contributing to the thrust signature. `[INFERENCE — not stated by them]` the reasoning is probably continuous with the hidden-momentum argument of §4: mobile carriers redistribute and cancel; bound charges cannot redistribute, so the Maxwell stress on them must be transmitted through the material lattice instead.

If that is the argument, the counter is direct: **the lattice transmits it to the rest of the body.** That is what makes it cancel. Immobility of the charge changes the *route* by which the counter-force is delivered, not whether it is delivered.

But note this is a reconstruction. If their actual argument is something else, this document has not engaged it.

### 11.3 Abraham–Minkowski — the best available intellectual cover

`[INFERENCE]` If there is a legitimate technical foothold anywhere in this claim, it is here, and it deserves to be stated properly.

The momentum of light in a dielectric medium has two competing century-old expressions: **Minkowski** (p = nE/c) and **Abraham** (p = E/nc), differing by n². The controversy is real, it ran from 1908 to roughly 2010, and it involved serious people.

Its resolution: the *total* momentum of field-plus-medium is unambiguous and conserved. The dispute was over how to split that total into "field" and "material" parts, which is convention-dependent. Both bookkeeping schemes give identical physical predictions.

**Why this is the strongest steelman available:** a device involving high fields in dielectrics, analysed with Minkowski momentum while omitting the compensating material momentum, will *appear* to show unbalanced momentum. This is simultaneously (a) the most defensible thing a proponent could cite, and (b) a well-characterised way to make exactly this error. Any serious engagement with the Exodus theory should ask which momentum convention is being used and whether the material counter-term is carried.

### 11.4 The QED vacuum claim — and the objection this document was missing

Their current theory attributes the force to momentum transfer from the quantised vacuum via third-order QED perturbation theory. The steelman: the vacuum is not nothing. Vacuum polarisation is real, the Casimir effect produces measurable forces from boundary conditions on vacuum modes, and QED corrections are among the best-verified predictions in physics.

**The objection — which belongs in this document and was absent until now:**

> **The QED vacuum is Lorentz invariant. It has no rest frame.**

"Pushing against the vacuum" is not a well-defined operation, because there is nothing to push against that could distinguish one inertial frame from another. Any device that gained momentum by pushing on the vacuum would define a preferred frame, and would therefore be a detection of Lorentz violation — a far larger claim than propulsion, and one constrained experimentally to extraordinary precision.

Casimir forces do not escape this: they are forces *between bodies*, always balanced pairwise, and they cannot be arranged to produce net momentum on a closed system.

**This objection also has diagnostic value.** Note that the GUT-CP paper attempting to explain the Exodus force does so by invoking < cite index="15-1">directional free-electron accelerations relative to absolute space</cite> and predicts < cite index="15-1">orientation-dependent variation relative to Earth's absolute-space frame</cite>. That is an explicit appeal to a preferred frame — the author has correctly identified what the claim requires, and it is exactly what a century of Michelson–Morley-descended experiment excludes. If the Exodus effect were real and vacuum-sourced, it should show sidereal variation. **That is a testable prediction, it can be run in their own lab, and it costs nothing but time.** It belongs in §7.

### 11.5 What is genuinely unresolved

Stripped of the surrounding argument, the defensible core is small but not empty:

- Momentum bookkeeping in dielectric media is subtle enough to have occupied serious physicists for a century.
- Whether intrinsic spin dipoles carry hidden momentum the way current loops do is a live dispute in the pedagogical literature.
- Measuring sub-millinewton forces on a high-voltage article without artifact is genuinely hard, and honest people have got it wrong in both directions.

None of these gets you to Mars. All of them are reasons why a competent electrostatics researcher could pursue this for twenty-five years in good faith.

---

### 11.6 Are they claiming a free lunch? — the critical velocity

A common and fair defence of the programme is that they are *not* claiming free energy. At bench scale this is correct, and the reason is worth stating precisely, because it explains how they can deny the free lunch in good faith.

A device producing force F while drawing power P delivers mechanical power F·v. Energy conservation is violated only when

```
F·v > P     ⟺     v > v_c = P / F
```

For 50 mN drawing ~1 W, **v_c = 20 m/s.** Their test article sits on a balance at essentially zero velocity. **No energy violation is observable in their laboratory, at any point, ever.** They are not concealing one; there is nothing there to conceal.

**But the free lunch is entailed rather than claimed.** Any device with F/P > 1/c, operated above v_c, generates net energy. For the §9.5 vehicle:

```
Peak power required at midpoint = F·v = 168 kN × 564 km/s = 9.5 × 10¹⁰ W = 95 GW
Average over the transit                                    = 47 GW
```

A vehicle that genuinely carried its energy budget would need 95 GW peak from 30 tonnes (3.2 MW/kg). A vehicle that does not carry it is a free-energy machine from roughly the sixth second of the burn onward.

**This is how to hold both facts at once:** the bench result implies no energy anomaly; the mission vision implies an enormous one. The programme's own extrapolation is what converts a momentum claim into an energy claim. Objections framed as "they're claiming perpetual motion" are unfair to the experiment and fair to the brochure.

### 11.7 Noether closes the QED route specifically

The move to third-order QED (§10.3) is, on its face, a *retreat to known physics* — a claim that no new force is needed, only a correctly computed higher-order effect. That sounds more modest than "New Force," and in one sense it is.

**It is also self-defeating, for a reason requiring no calculation.** The QED Lagrangian is invariant under spacetime translations. By Noether's theorem, energy–momentum conservation is therefore exact in QED — not approximate, not order-dependent, but a structural consequence of the symmetry, holding identically at every order of perturbation theory.

**A third-order QED calculation cannot produce net momentum for a closed system.** Not because nobody has looked, but because the symmetry forbids it. If the Exodus effect is real, QED is the wrong place to have found it; if the mechanism really is third-order QED, the net force must integrate to zero.

Note the bind this creates. **"New Force" and "third-order QED" are incompatible positions**, and the programme has occupied both simultaneously — the former in press interviews, the latter in technical presentations. Whichever is dropped, the other inherits a specific problem: a new force must survive Lorentz-invariance constraints (§11.4); a QED effect must survive Noether. `[FLAG FOR FUTURE TRANSCRIPTS: watch which framing is used in which venue.]`

### 11.8 Is the claim unfalsifiable? — separating effect from explanation

A frequent objection is that this has the structure of Russell's teapot: positioned so that failure to disprove counts as support. **That charge is half right, and the half matters.**

**The effect is falsifiable, and they propose the right test themselves.** Orbital flight, independent replication with an outside error budget, the sidereal test (§7.13), a published F/P — any could kill it. < cite index="16-1">Buhler's own stated position is that if hardware moves under its own power in space with no reaction mass, the debate is over</cite>. That is a falsification condition offered voluntarily. It is not a teapot.

**The explanation has become teapot-shaped.** The current position — that < cite index="14-1">the system conserves quantum momentum even though that momentum is not directly observable or manipulable in the way classical momentum is</cite> — posits a conserved quantity making no contact with measurement. An unobservable ledger cannot be checked, cannot fail, and cannot constrain. That is the teapot move exactly, and it appeared at the point where the theory had to meet §4.1 rather than answer it.

**Correct formulation:** an unfalsified but falsifiable *claim*, attached to an unfalsifiable *explanation*. These need separate handling. Criticism aimed at the effect should demand tests; criticism aimed at the theory should demand observables.

### 11.9 A note on rhetoric and proportion

Logged without over-weighting, since it concerns presentation rather than physics.

The vehicle vision (§9.5) is described with far more specificity than the device: coffee mugs, flush toilets, ham sandwiches, bone density, diapers. The device is a hand-sprayed foam blob producing 50 mN with an unstated power draw. **Confidence is expressed in inverse proportion to the evidence available at each level.**

Two mitigations. First, this is Aurigema, not Buhler — the division of labour (§0) appears to extend to rhetorical register, and attributing the brochure to the physicist would be an error. Second, the mission profile is not borrowed from science fiction; fiction borrowed it from orbital mechanics. Its familiarity from *The Expanse* or *Project Hail Mary* is not evidence against it, and dismissing it on those grounds is a genetic fallacy.

**What survives those concessions:** describing the destination in consumer detail while the F/P ratio has never been published inverts where the uncertainty actually lies. It invites the "they've built the Star Trek impulse engine" response — and that response, while not an argument, is a rational reaction to a claim whose vividness scales inversely with its support.

## 12. The full transcript (35:57 – 3:04) — new material and what it changes

The remaining two and a half hours supply what every earlier section was missing: **the stated mechanism, the measurement practice, and the full thrust ledger.** Three items change the assessment materially. Several others sharpen it.

### 12.1 The mechanism, finally stated: pressure × area

At 38:20–39:24 Aurigema gives the actual physical argument, with Buhler endorsing it ("that's pretty good explanation"). **This upgrades §11.1 from reconstruction to fact, and it is more specific — and more clearly wrong — than the steelman version.**

Their argument, in their words: the device has grooves with *very small area* at the fin tips on one side, and a *very large area* foil on the other. "The large area has a greater electrostatic pressure pushing against it than the very small area of the tips of the fins... I push a million pounds against zero area, or I push one pound against 10 inches of area." Net force forward because area wins.

**The error is specific and identifiable.** The argument treats electrostatic pressure as roughly uniform across the device, so that force scales with area. It is not uniform. Electrostatic pressure is

```
P = ε₀E² / 2
```

and E is enormously enhanced at sharp features — that is the whole reason the tips are sharp, and it is the same field enhancement that makes needles corona-emit (§5). At the fin tips the area is tiny but P is huge. On the flat foil the area is large but P is small. **They trade off exactly**, because the field lines leaving the tips are the same field lines terminating on the foil. The Maxwell stress integrated over any closed surface enclosing the whole device is zero. This is not a subtle cancellation; it is Newton's third law applied to the internal charges.

Two supporting observations:

- At 39:21 the definition is given as "electrostatic force times area, which is electrostatic pressure." **Pressure is force divided by area.** A small slip in conversation, but it is the exact quantity the argument turns on.
- At 2:03:04 Buhler acknowledges the overlap with **Biefeld–Brown** — and the asymmetric-capacitor pressure argument is precisely the reasoning that has failed there for a century.

To their credit, Aurigema hedges: "there's a few more subtleties to it than that." The subtleties are where any real claim would have to live, and they are not stated anywhere in three hours.

### 12.2 Persistent thrust explained — and what it entails

**This is the most important passage in the entire transcript.** At 36:01–36:28 and again in full detail at 1:57:07–2:00:26, they describe the effect this way:

- High fields drive charge **into** dielectric materials, where it becomes trapped ("frozen charge").
- Cutting power removes only the free charge. The driven-in charge remains and keeps its field.
- "This is a field-driven phenomenon. It doesn't care where the field comes from."
- They charge devices for 30,000 s (~8 hours), sometimes 100,000–200,000 s (~1–2 days).
- Power off, high vacuum, electrically isolated: **"I'll come back the next day and the thrust will still be there"** — 2–4 mN.
- As charge eventually bleeds off through imperfect insulators, thrust bleeds off with it.

**Assessment, honestly split.**

*In their favour:* this is a coherent account. It explains the "no current, no power" claim without any mystery — the field is electrostatic and stored, so of course there is no current. It is internally consistent with their theory, since electrostatic pressure depends on the field and not on its source. And the observation that thrust tracks charge decay is exactly what their model predicts.

*Against:* it is also, precisely, the trapped-charge artifact signature flagged in §10.4 — charge injection into dielectrics with slow relaxation. Both readings fit the same data. **The observation does not discriminate**, which is why §14's decay-constant question remains open rather than resolved.

**But it does something else, and this is decisive.** It converts the free-lunch question from an extrapolation into a direct entailment of their own bench description.

A device with zero energy input, producing sustained thrust, is bounded by its stored electrostatic energy. Generously, for a large-area device at high voltage:

```
C ≈ ε₀A/d ≈ 8.85×10⁻¹² × 0.2 m² / 10⁻³ m ≈ 1.8 nF
U = ½CV² at 140 kV ≈ 17 J        (call it ≤100 J to be generous)
```

Now let that device be free to move — which is exactly what they propose to do in orbit:

```
3 mN sustained for one day:  impulse = 3×10⁻³ × 86,400 = 259 N·s
On a 2 kg article:           Δv = 130 m/s
Kinetic energy gained:       ½ × 2 × 130² = 16.9 kJ
```

**16.9 kilojoules out of ≤100 joules stored, in the first day — and kinetic energy grows as t², so a week gives ~830 kJ.** The ratio is not marginal, it is unbounded and increasing.

Why this matters more than §9.5's vehicle argument: that one required accepting their Mars extrapolation. **This one requires only their own description of their own bench result.** On a load cell nothing moves, so no work is done and no violation is observable (§11.6) — which is why they can report this in good faith. The moment the device is free to translate, the violation is immediate and enormous.

**The orbital test they propose is therefore not merely a demonstration of thrust. It is the direct test of whether energy is conserved** — and it is a test they are actively seeking to run. That is genuinely to their credit, and it means this question resolves itself if they fly.

### 12.3 Measurement practice — substantial credit is owed

§7 listed thirteen discriminating tests. The transcript shows most have been done, and one solution is better than what §7 proposed.

| §7 test | Status per transcript |
|---|---|
| 2. Hard vacuum | Done. 10⁻⁶ torr claimed (52:06) |
| 3. 180° reversal | Done (1:53:02) — "flip it backwards, flip it 180, turn it 90°" |
| 4. Dummy load | Done (1:53:09) — "dummy plates that look just like your plates but don't have the asymmetry... they don't work" |
| 5. Faraday shielding | Done — ITO plastic Faraday cage inside the chamber (1:47:37) |
| **6. Cable stiffness** | **Solved better than §7 suggested** (1:54:17) |
| 12. Ground-plane distance | Partially — "no cabinets or tables or chairs feet away" (1:51:12) |
| Earth's magnetic field | Addressed (1:50:00) — including a permanent magnet control |

**The cable solution deserves specific credit.** §7.6 flagged HV cable stiffness as a classic false positive. Their answer was to mount **the entire high-voltage power supply inside the test article, inside the Faraday cup, inside the chamber, with the whole assembly on the pendulum** — then run a thousand tests in that configuration. That eliminates the failure mode at the root rather than correcting for it, and it is better practice than most published torsion-balance work in this field.

Force measurement is by **load cell**, not free deflection (2:13:18), with the article pre-loaded to 10–15 mN and the change observed. Also correct, and note the consequence: the article moves ~0.1 mm, so essentially no work is done — reinforcing §12.2.

They also report a genuinely instructive artifact of their own discovery (2:14:50): a new thruster shows **no thrust** immediately after pump-down, and thrust appears only after ~12 hours, which they attribute to molecular water desorbing from surfaces and shorting the device. This is a real and physically sensible effect, and it is the kind of observation that indicates people who are actually running experiments. Note also that it cuts *against* outgassing as the artifact — outgassing declines with pump time while their thrust increases with it.

**What remains uncontrolled:** the residual pressure of 10⁻⁶ torr with foam, tape, Kapton and RTV inside is high enough that outgassing is not excluded on its own; and no F/P figure appears anywhere in three hours, despite the entire claim resting on it.

### 12.4 The thrust ledger

The transcript scatters numbers across three hours. Collected:

| Device | Thrust | Context |
|---|---|---|
| DIY $150 kit | 0.1 mN | Air, on a string (37:42) |
| Vacuum carousel | 125 µN | High vacuum, Faraday cage (1:48:09) |
| Spinner | 2 mN | Vacuum, pin-and-jewel pivot, 2 kg article (56:33) |
| Star Trek model | 2.5 mN | "First warp drive ship in history" (40:13) |
| Persistent / power-off | 2–4 mN | Vacuum, days after charging (1:59:22) |
| 140 kV needle | 6 mN **(derived, not measured)** | Air, pendulum suspended by its own HV lead (2:01:03). Inferred from deflection; mass and angle unstated — see §5.1 |
| **Best to date** | **50 mN** | (31:40) |

Typical devices produce 0.1–6 mN. The 50 mN figure is an outlier by roughly an order of magnitude and is not attached to a described configuration anywhere in the transcript. **§9's entire analysis is built on that unattached number** — worth noting, since the more commonly demonstrated 2–6 mN would change every arithmetic result by an order of magnitude while changing none of the conclusions.

### 12.5 "Over unity" and the three incompatible "Earth unity" figures

At 43:04: **"We are over unity. If the propulsion cell weighs a pound, we can make 1.8 pounds."**

**"Over unity" conventionally means energy output exceeding energy input — i.e. perpetual motion.** They mean thrust-to-weight ratio above 1. These are entirely different claims, and using the free-energy term for a T/W ratio is a serious own goal in a field where they are already fighting that association. `[TERMINOLOGY LANDMINE — like "38 g" in §9.3, note for future transcripts.]`

More useful: the transcript gives **three different unity figures**, and the discrepancy answers §9.5's open question.

| Figure | Basis | Source |
|---|---|---|
| 1.8 | Propulsion cell material only | 43:04 |
| 1.7 | "based on the actual thruster itself" | 55:13 |
| **0.5** | **"advertising right now about 0.5 Earth unity"** | 2:23:39 |

At 55:22 the reconciliation is given explicitly: the 1.7 figure "doesn't count for the mass of the framing, the power supply, the tape, all the non-components that are doing nothing except holding it together." Their own analogy: "a car saying I have enough horsepower to move the engine, but not the car."

**So the system-level figure is 0.5 Earth unity — a factor of ~3.5 below the active-material figure.** This is exactly the degradation §9.5 flagged as untested, and they have now quantified it themselves. Applied to the 45-tonne vehicle:

```
30,000 kg × 4.9 N/kg = 147 kN   (vs 168 kN required for 0.38 g)
Actual acceleration = 147,000 / 45,000 = 3.27 m/s² = 0.33 g
Transit time = 2√(d/a) = 3.6 days
```

**The Mars vision survives on mass, marginally.** 3.6 days rather than 3.5. Credit where due — the mass budget is roughly self-consistent. §9.5's energy objection is untouched by this and remains the binding constraint.

### 12.6 The DIY thruster paradox

They publish free build instructions for a $150 device (37:16–37:51) and invite anyone to replicate. **This is the most falsification-friendly thing in the entire programme** and deserves saying plainly.

But note what it produces: 0.1 mN, hung on a string, **in air**. And at 2:03:26 Buhler states directly: **"Our effect is much much weaker than ion wind."**

**By their own account, the configuration they offer to the public for replication is the one in which the artifact is stronger than the effect.** Anyone who builds the kit and sees it move has learned nothing, because ion wind fully explains a 0.1 mN deflection at those voltages in atmosphere. The devices that could discriminate — vacuum, Faraday-caged, load-cell instrumented — cost far more than $150 and are not replicable from a video.

This is not dishonesty; the kit is clearly meant as an accessible demonstration. But the replication path they are counting on (49:22–50:28, the "lifters went mainstream via hobbyists" model) **cannot in principle deliver the evidence they need**, and the lifter analogy is doubly unfortunate given that lifters turned out to *be* ion wind.

### 12.7 Replication claims versus the published record

At 47:29 they state they have "affidavits" and "videos of people that reproduced our work," and at 2:10:45 Buhler refers to "the guys that have reproduced my work."

This does not contradict §10.5. < cite index="13-1">Popular Mechanics reported in May 2026 that there was no published independent replication using an outside lab's own apparatus, instrumentation, and uncertainty budget.</cite> Informal replication by associates and hobbyists, submitted as patent-office affidavits, is a different thing from an independent laboratory publishing a result with its own error budget. Both statements can be true simultaneously, and the distinction is the entire point of §13's closing note.

### 12.8 The patent office, and an epistemic closure problem

The first patent took 3.5 years, allegedly held in DoD and then NASA review. The second was rejected on the grounds that it violates conservation of momentum (46:52).

One remark stands out (46:20): the patent office sought external reviewers, and **"there just aren't that many people on this planet who know how to read our patent... most of them work on our team. The few that don't work on our team, they were contacted by the patent office and said we can't, because we work on the team that invented it."**

Taken at face value, this describes a claim whose competent-reviewer pool is largely internal to the group making it. That is a structural epistemic problem independent of anyone's good faith — it is the same issue as §13's systematic-error point, arriving from a different direction. It is also, notably, an argument *for* seeking outside replication rather than against it.

### 12.9 Peer review posture

At 48:22: **"peer review is designed to shut down the flow of information."** Buhler: "I'm not waiting for the scientific community. It'll take them 20, 30 years."

They do say they intend to publish, and Buhler correctly notes the physics can't be patented anyway. But the Wright brothers analogy (48:31) is worth checking: the Wrights were *secretive*, widely disbelieved, and the thing that settled it was **public demonstration** in 1908 — not exemption from scrutiny. Wilbur also published in Chanute's journal and in *Zeitschrift für Luftschiffahrt*. The analogy actually supports flying the device, which is their plan; it does not support treating peer review as obstruction.

### 12.10 Prior-plausibility signals

Logged neutrally, because they bear on epistemic standards rather than on electrostatics, and it would be a genetic fallacy to treat them as refuting the thruster.

- **Telepathy and clairvoyance (1:31:03–1:31:55).** Buhler: "Like telepathy, very real. You have to practice it." He describes testing it with his children and wife, and reports clairvoyance drawing experiments working.
- **The orb encounter (2:43:05–2:49:16).** A 45-minute event off Cocoa Beach in 2013–14 with his wife, ending when he mentally asked the lights to leave.
- **Inertia reduction (1:12:18).** An APEC colleague reportedly reducing a test article's inertial mass, relayed without evident scepticism.

**The relevant observation is not that these are unusual beliefs. It is that the epistemology is identical to the one applied to the thruster:** "you have to believe it. To believe it, you have to test it yourself. Don't just take someone's word for it" (1:31:04). Personal replication as the standard of evidence is exactly what produces both a career of careful electrostatics *and* confidence in mind-reading — and it is precisely the standard that independent replication exists to supplement.

This qualifies rather than cancels "credentialed NASA electrostatics expert." Both descriptions are accurate; the second does not follow from the first.

One further item, in a different register: at 1:56:48, **"90% of the time the darn force is there because it is so universal."** An effect that appears in nearly every configuration attempted, largely regardless of design, is more consistent with a systematic common to the apparatus than with a designed phenomenon. Their §12.3 dummy-plate control is the right answer to this and reportedly nulls — which is the strongest single piece of evidence in the programme's favour, and would repay far more detail than it receives.

### 12.11 The CubeSat proposal — the actual falsification path

At 59:19–1:03:18: a 3U CubeSat with the propulsion module as 50% of mass, roughly $300k–$1M all-in including launch and telemetry, with a customer reportedly interested.

**This is the serious proposal in three hours of conversation, and it is cheap.** Checking their numbers at 0.5 Earth unity system-level: a 4 kg 3U with 2 kg propulsion gives ~9.8 N — wait, that yields 2.45 m/s², reaching Mars in ~4 days, whereas they say "a couple of weeks." They are being *conservative* relative to their own figures, which is the right direction to err.

One internal inconsistency: at 1:02:15 they say escape from Earth orbit takes "about 12 or 13 hours." Low-thrust spiral escape from LEO requires roughly Δv = v_circ ≈ 7.8 km/s, so 12 hours implies a ≈ 0.18 m/s² — about fourteen times below the CubeSat spec they just described. One of the two figures is wrong.

**Regardless: this is the test.** In free flight, §12.2's energy entailment becomes directly observable, ion wind and image-charge attraction are absent by construction, and the tracking is done by someone else. Buhler's own framing is right — < cite index="16-1">if hardware moves under its own power in space with no reaction mass, the debate is over</cite>. At $1M, this is cheaper than continuing to argue about it.

---

## 13. Epistemic status of this document

**Read this before citing anything above.**

Without access to the authors, primary data, or the patent text, this document is an assessment of *claims as reported*. Every statement in it falls into one of five categories, and conflating them would be the main way to misuse it:

| Category | Confidence | Examples |
|---|---|---|
| **Textbook physics** | High | Field momentum, hidden momentum, Feynman disk, Maxwell stress, photon bound, Lorentz invariance of the vacuum |
| **Arithmetic on their stated numbers** | High — check it yourself | §9.2 (F/P), §9.3 (0.38 g decoding), §9.5 (47 GW) |
| **Direct transcript quotation** | High for content, **provisional for speaker** | Everything in §1 |
| **Secondary reporting** | Medium — advocacy venues, §10.6 | 2,000 vacuum tests, 4,500 tests, post-power-off persistence, QED theory |
| **This document's inference** | Low — flagged `[INFERENCE]` | §11.2, §11.3, and the reconstruction of what they mean by bound charge |

### What cannot be resolved without them

An explicit list, so that absence of an answer is not mistaken for absence of an answer *existing*:

1. **Input power / F–P ratio.** Never published in any source found. Everything in §9.2 turns on it.
2. **Force measurement method.** Balance type, resolution, calibration, uncertainty budget. Unknown for all 4,500 tests.
3. **Vacuum quality and residual pressure.** "Hard vacuum" is claimed; no figure given.
4. **Post-power-off decay constant.** The single most diagnostic available number (§10.4).
5. **Unit mass including power supply.** §9.5's mass budget is otherwise unfalsifiable.
6. **Whether §11.2's reconstruction is their actual argument.** It may not be.
7. **Whether the sidereal-variation test (§11.4) has been run.** Cheap, decisive for the vacuum hypothesis, no sign it has been attempted.

### The core methodological point

**A systematic error is perfectly reproducible.** Four thousand five hundred tests within one laboratory measure the *consistency* of a method, not its *correctness*. This is not a criticism of their care; it is a structural limit on what in-house repetition can establish, and it applies identically to work that turns out to be right. It is why the missing item is not more data but different hands.

Equally: **nothing in this document demonstrates the effect is not real.** It establishes that the reported evidence does not yet distinguish a new force from a measurement artifact, that the vehicle-scale vision is excluded on energy grounds independent of that question (§9.5), and that the decisive tests are known, cheap, and unperformed by anyone outside the group.

**Revised position after the full transcript.** Three things changed. Their measurement practice is better than this document assumed — most of §7 has been done, and the internal-power-supply solution is better than what §7 proposed (§12.3). Their stated mechanism is worse than the steelman reconstructed for them, and fails in a specific, identifiable way (§12.1). And the free-lunch objection no longer requires their Mars extrapolation: it follows directly from their own description of thrust persisting for days with the power off (§12.2).

The net effect is to narrow the question to a single point. **Given competent artifact control and an incorrect stated mechanism, the claim rests entirely on whether the dummy-plate control is as clean as one sentence at 1:53:09 suggests** — and on flying the CubeSat, which would settle both the effect and the energy question at once, for less than the cost of arguing about it.

---

## 14. US 11,511,891 B2 — the derivation, at last

**Source:** US 11,511,891 B2, *System and Method for Generating Forces Using Asymmetrical Electrostatic Pressure*, Aurigema & Buhler. Priority 2018-11-19, granted 2022-11-29. Continuation US 2024/0011469 A1 pending.

**This is the most important document in the file.** Everything before it assessed a claim whose mechanism had to be reconstructed from conversation. The patent states the mechanism as an equation, discloses the test apparatus, gives a measured force, and — remarkably — cites the prior art that nulled the effect.

### 14.1 Their derivation, reproduced

The patent derives its central result in six steps:

```
(1)  0 = ½Mv² + U                      "total energy (kinetic plus potential) is zero"
(2)  Mv = −(2/v)U                      solve for momentum
(3)  Mv = −2U dt/dx                    "turn the velocity in the denominator into its operator v = dx/dt"
(4)  d(Ut) = 0  ⟹  U dt = −t dU        "we make the claim that the differential
                                        of the energy-time product should also be set to zero"
(5)  Mv = +2t dU/dt
(6)  U = (ε₀/2)∫E² dτ                  substitute the field energy
(10) P(t) = Mv = ε₀t [E₂²A₂ − E₁²A₁]
(11) F = dP/dt = ε₀ [E₂²A₂ − E₁²A₁]
```

Equation (11) is §12.1's "pressure × area" argument in closed form. The patent calls it "remarkable," and it is — but not for the stated reason.

### 14.2 Four independent failures

**(a) The derivation proves too much.** Steps (1)–(5) contain no electromagnetism whatsoever. U is an arbitrary potential energy; the field energy is only substituted at step (6). **The same manipulation applied to U = −GMm/r yields a reactionless gravitational drive.** A derivation that produces propellantless thrust from *any* potential energy function has demonstrated an error in the manipulation, not a property of electrostatics. This is the cleanest single objection and it requires no field theory at all.

**(b) Step (4) is an assumption that their own device violates.** Setting d(Ut) = 0 means **Ut = constant, i.e. U ∝ 1/t** — the stored energy must decay as the reciprocal of time, forever. The stated justification is an analogy to least action, δS = δ∫L dt = 0, but that is a variational statement over *paths*, not a claim that the product of energy and time is constant along one path. And a charged capacitor at fixed voltage and fixed geometry holds **U constant**, which is d(Ut) = U dt ≠ 0. **The assumption that generates the entire result is falsified by the apparatus the patent describes.**

**(c) Step (3) is not a valid operation.** "Turning v in the denominator into its operator" treats dx/dt as an algebraic fraction that can be inverted and moved. That works notationally for separable first-order ODEs; it is not licensed here, where U is not being differentiated and nothing specifies what is held fixed.

**(d) Equation (11) integrates over an open surface.** The net force on a body is the Maxwell stress integrated over a **closed** surface enclosing it:

```
F_i = ∮ T_ij dA_j ,   T_ij = ε₀(E_i E_j − ½ δ_ij E²)
```

For an isolated configuration with no external field, taken at infinity, this is **exactly zero**. Eq. (11) instead evaluates ε₀E²A on *two selected patches*, differences them, and omits every other surface of the device. It also uses the scalar ε₀E² rather than the full tensor, discarding the E_iE_j term — which is precisely the part carrying directional momentum flux. **This is §12.1's error in algebraic form, and it is now citable rather than inferred.**

### 14.3 Their own equation states energy non-conservation

Worth isolating, because it closes §12.2's argument using nothing but their mathematics.

Equation (10) says momentum grows **linearly and without bound** from a static field: P(t) = ε₀t[E₂²A₂ − E₁²A₁]. Therefore

```
KE = P²/2M  ∝  t²
```

from a constant electrostatic field with **zero energy input**. Their own momentum equation predicts unbounded kinetic energy from a fixed stored charge. §12.2 derived this from their bench observations; §14 shows it was in the mathematics from the start.

### 14.4 The patent cites the prior art that nulled the effect

Two citations in their own background section deserve to be read carefully.

**Talley (1991), Veritay Technology, US Air Force contract.** The patent reports that Talley suspended an asymmetric-capacitor test article on a torsion wire in vacuum and *"ultimately attributed the force that he observed to the electrostatic interaction between the chamber and the device"* — quoting Talley's conclusion that under high vacuum *no detectable propulsive force was electrostatically induced* between test device electrodes.

**Canning et al. (2004), NASA Glenn, NASA/CR-2004-213312.** The patent reports Canning found that most asymmetric capacitors *"exhibit a null thrust unless there is an accompanying ion wind"* and that their operation is fully explained by electrostatic forces plus momentum transfer by collisions.

**A prior worker on an Air Force contract, doing the same experiment in vacuum on a torsion balance, found the force and traced it to device–chamber electrostatic interaction.** That is the single most relevant precedent in the field, it appears in their own patent, and nothing in three hours of transcript addresses how their configuration differs from Talley's. Image 2 — a torsion arm inside a chamber with a large copper disc mounted on the wall a short distance from the article's swept path — is the configuration Talley's result speaks to directly.

### 14.5 What the patent discloses that nothing else did

Genuinely new and useful, and much of it closes CENA gaps:

| Disclosure | Value |
|---|---|
| **Measured force** | **~237 µN** average, "repeated dozens of times" |
| **Force meter** | Omega DGF155-0.12, **0.1 mN resolution** |
| **Voltage** | up to **+40 kVDC** — *not* 140 kV |
| **Ground connection** | V− to the copper tape, i.e. **the large-area electrode is ground, the blades are HV** |
| **Dielectrics used** | polyimide, PTFE, styrofoam, epoxy, RTV, HV putty |
| **Blade length rule** | no benefit beyond blade spacing — beyond that the far surface is Faraday-shielded |
| **Ground-plane optimisation** | triangular features, optimum at **~23 triangles**, claimed **6×** improvement |
| **Gap** | force rises as gap closes, limited only by breakdown |
| **Design tools** | FEMM + MATLAB, and COMSOL — fully reproducible method |
| **Controls described** | grounded ITO-coated PET box, plastic bag, 180° flip for tension/compression |
| **Scaling** | force ∝ V², "observed repeatedly over a variety of shapes and geometries" |

**On the measured force: 237 µN was read on a meter with 0.1 mN resolution.** The signal is **2.4 resolution units.** For a claim of this magnitude that is a thin margin, and it is the number the patent offers as its proof.

**On the V² scaling — this is important and cuts against them.** They present V² dependence as verification. But **every** electrostatic artifact scales as V²: Coulomb attraction to the chamber, dielectrophoresis, electrostriction, and the Maxwell-stress deformation identified in §7.15. Ion wind is the one mechanism that does *not* follow V² cleanly. So the V² result rules out the artifact they were worried about while being fully consistent with the artifact class nobody has controlled for.

### 14.6 Theory position #4, contradicting #3

The patent states plainly that the invention *does not operate on* ion wind, Coulomb attraction to walls, Earth's magnetic field, field momentum, or hidden momentum — **and that it is "not related to some effects related to the quantum vacuum fluctuations as theorized by the makers of the EM Drive."**

By 2024–25 Buhler is presenting third-order QED perturbation theory with the force attributed to quantum-vacuum momentum transfer (§10.3). **The granted patent explicitly disclaims the mechanism the inventor now publicly asserts.** Adding the 2018 provisional's title — *A Propellantless Propulsion Concept for Spacecraft Based on Electrostatic Field Momentum Transfer* — the sequence is:

1. 2018 provisional: **electrostatic field momentum transfer**
2. 2022 patent: **not field momentum, not hidden momentum, not quantum vacuum** — pure electrostatic pressure asymmetry
3. Transcript present tense: classical energy conservation, electric fields only
4. 2024–25: **quantum vacuum, third-order QED**

Four positions, two of which explicitly deny each other. §11.7's bind now has documentary form: the legal instrument and the public theory are incompatible, and both cannot be relied on.

### 14.7 Net effect on the assessment

**Against:** the derivation is available and fails four ways; their own patent cites an Air Force vacuum test that traced the same force to chamber interaction; the headline measurement is 2.4× the instrument resolution; the V² result doesn't discriminate the uncontrolled artifact; the theory contradicts itself across documents.

**For, and it should be said:** the patent is a serious technical document. It surveys the prior art honestly, *including the results that go against it*. It names its instruments, discloses its computational method (FEMM/MATLAB/COMSOL — reproducible by anyone), gives real design rules, and describes controls that address ion wind and Coulomb attraction. This is not a document written by someone hiding anything. It is a document written by people who believe the effect is real and have tried to say how they got it.

**And it closes CENA's G1.** An engineer now has blade geometry, the blade-length rule, gap behaviour, the triangle optimum, materials, voltage, polarity and the modelling tool chain. **Exact replication is no longer blocked** — see the revised actionability audit in `Buhler-replication-CENA.md`.

---

## 15. Open threads

**Resolved by the full transcript:** the stated mechanism (§12.1), the persistence explanation (§12.2), measurement practice (§12.3), the thrust ledger (§12.4), whether the unity ratio survives ancillary mass — it doesn't, 1.7 → 0.5 (§12.5). "Drew" is Andrew Aurigema.

**Added by the CENA pass** (`Buhler-replication-CENA.md`, 2026-08-25) — three findings that belong here:

- **The claimed effect is ~10⁻⁴ of the device's own internal Maxwell stress.** From the one hard spec in the record (10⁸ V/m, at 2:02:37): P = ε₀E²/2 = 44 kPa, giving ~442 N across a 10×10 cm device against a claimed 50 mN. This reframes both sides — it explains why the force shows up in "90% of configurations," and it means any mechanical coupling of 0.01% of that internal force reproduces the result. **New artifact class, no control exists for it.** (CENA D6, §7.15)
- **Electron-stimulated desorption** survives both vacuum and power-off, and predicts their 12-hour water observation as well as their own explanation does. (CENA D10, §7.14)
- **X-ray hazard.** A 140 kV electrode pair in vacuum with sharp field-emitting features is an X-ray tube, and their chamber has a large viewport. Unmentioned by anyone in three hours. (CENA D9)

**Now the top questions:**

**Note:** §14 (patent) supersedes several threads below. G1 geometry is closed; the derivation is now available and refuted; Talley (1991) is the governing precedent.

- **The dummy-plate control (§12.3, 1:53:09).** Reportedly nulls. This is the single strongest piece of evidence in the programme's favour and it gets one sentence in three hours. How many runs? Same mass, same capacitance, same surface area, same charging history? Blinded? **If this control is as clean as described, it excludes most artifact classes at once — and if it isn't, it excludes the claim.** Everything else in §14 is lower priority than this.

  **CENA sharpens this into a specific problem (D8/G10).** Given §7.15, a dummy plate that is *symmetric* will also *deform symmetrically* — so the control may be nulling the deformation artifact and the claimed effect together, and cannot separate them. The published description, "looks just like your plates but doesn't have the asymmetry," does not say what it matches on. **This and the device geometry are the two facts that, if published, would make independent replication meaningful. Neither appears in any public source, and publishing them would cost approximately nothing.**
- **F/P.** Still absent after three hours. Nothing has changed.
- **The 50 mN configuration.** §9's whole analysis rests on a number never attached to a described device (§12.4). Typical results are 2–6 mN.
- **The decay constant of the persistent thrust.** Still unresolved and still discriminating — see §12.2. Their model and the trapped-charge artifact predict *different* functional forms even if both predict decay.
- `[PENDING]` **The "classical conservation of energy" maths** at 24:00. Does it address the centre-of-energy theorem, or the §12.2 energy entailment? Still the only place the actual obstacle could be engaged.
- `[PENDING]` **Has the §12.11 CubeSat flown or been contracted?** This resolves everything. Check quarterly.
- `[EXPAND]` Work §12.1 as a derivation: show ∮T·dA = 0 explicitly for a tip-and-plate geometry, with the field enhancement made numerical. Their argument deserves a refutation with numbers in it, not just a principle.
- `[EXPAND]` Does the Shockley–James term apply to **intrinsic spin** magnetisation? Real AJP dispute (Griffiths, Hnizdo, Boyer). Relevant to whether his bound-charge route was ever viable *on its own terms*, independent of §4.1.
- `[EXPAND]` Work the Feynman disk fully — show the induced-E torque integral equals the field angular momentum. Needed to state §3 as a derivation rather than an assertion.
- `[EXPAND]` Historical graveyard: Brown's asymmetric capacitors, Woodward/Mach effect, EmDrive, Cannae, NASA Eagleworks 2016 and the 2021 Dresden torsion-balance null. Cause of death for each. This is the most useful reference table to build.
- ~~**Open question:** what is the claimed thrust magnitude?~~ **RESOLVED:** 50 mN, stated at 31:40. Analysis in §9.
- **Open question (now the top one):** is there any published Buhler measurement with **F/P** reported?
- **Open question:** has anyone put the §9.5 energy objection to them directly, and what was the answer? This is the question that does not depend on adjudicating any momentum theory, and it should be asked before any momentum question. If the reply is that energy also comes from the vacuum, that is a substantially larger claim and should be logged as such.
- `[EXPAND]` Separate the **bench claim** (50 mN on a 5 g article — energetically trivial, stands or falls on §9.2 and independent replication) from the **vision** (45 t to Mars — killed by §9.5 regardless of replication). Conflating them helps neither side of the argument. Thrust figures are everywhere in the public record; input power is nowhere. Given §9.2, the ratio is the entire question, and its persistent absence from every source found is itself the most informative gap in the record.
- **Open question:** what is the decay time constant of the post-power-off thrust (§10.4)? Seconds → thermal/mechanical. Minutes-to-hours → trapped charge. This single number would probably settle more than any other available measurement.
- **Open question:** what is the mass of a single Exodus unit, and what is its measured T/W including power supply? The Mars extrapolation in §9.4 stands or falls on this and it does not appear anywhere.
- `[PENDING]` Retrieve and read the actual patent text (Aurigema & Buhler). The claimed geometry and any disclosed measurement method are the most concrete public artifact available.
- `[PENDING]` Locate the 2019 dataset — reported as 300–400 µN — and check whether any F/P was published then, when the claim was smaller and less contested.
- `[PENDING]` Has the promised peer-reviewed paper appeared since May 2026? Check quarterly.

---

## 16. Glossary

| Term | Meaning |
|---|---|
| Poynting vector **S** | Energy flux density, **E**×**H**; momentum density is **S**/c² |
| Field momentum | ε₀∫(**E**×**B**)dV — momentum stored in the EM field itself |
| Hidden momentum | Relativistic mechanical momentum in a current loop in an E field, **m**×**E**/c² |
| Centre-of-energy theorem | Total momentum = 0 iff centre of energy is stationary; from ∂_μT^{μν}=0 |
| EHD / ion wind | Thrust from corona-accelerated ions transferring momentum to neutral air |
| Dielectrophoresis | Force on a body in a dielectric medium due to field gradient |
| P/c bound | 3.34 µN/kW — max thrust for any propellantless device |

---

## 17. Reading list

- Griffiths, *Introduction to Electrodynamics*, ch. 8 — field momentum, done properly.
- Griffiths, "Resource Letter EM-1: Electromagnetic Momentum," *Am. J. Phys.* 80, 7 (2012) — the definitive survey, includes the hidden-momentum dispute.
- Shockley & James, *Phys. Rev. Lett.* 18, 876 (1967) — the origin of hidden momentum.
- Feynman, *Lectures on Physics* Vol. II §17-4 and §27-6 — the disk paradox and its resolution.
- Boyer, various *Am. J. Phys.* — the contrary position on hidden momentum and spin dipoles.
- Tajmar et al., Dresden (2021–22) — the torsion-balance protocol that nulled EmDrive and Mach-effect claims. **The methodological gold standard for this document's §7.**
- Masuyama & Barrett, *Proc. R. Soc. A* 469 (2013) — EHD thrust-to-power measurements in air; source of the 5–20 N/kW figure.
- Barnett, "Resolution of the Abraham–Minkowski Dilemma," *Phys. Rev. Lett.* 104, 070401 (2010) — for §11.3. The cleanest statement of why both conventions are right and neither yields free momentum.
- Pfeifer, Nieminen, Heckenberg & Rubinsztein-Dunlop, *Rev. Mod. Phys.* 79, 1197 (2007) — the full momentum-in-media review, if §11.3 needs developing.
- Mattingly, "Modern Tests of Lorentz Invariance," *Living Rev. Relativity* 8, 5 (2005) — the experimental constraints that make §11.4's preferred-frame requirement expensive.
- Milonni, *The Quantum Vacuum* — for assessing what can and cannot be extracted from vacuum fluctuations.

---

## Appendix A — Image log

For each image record: what device, what measurement apparatus, is it in vacuum, is there a balance, where do the HV cables run, is there any instrumentation visible for current measurement.

### Image 1 — "brain blob" SPF test article in transparent enclosure

**Source:** supplied alongside transcript ~29:40. Described as the styrofoam/spray-foam article inside a PET box used for lab testing.

**Observed with reasonable confidence:**
- Irregular hand-sprayed polyurethane foam mass, roughly spherical, ~20–25 cm across by eye, centred in the enclosure.
- Transparent enclosure, apparently acrylic or PET sheet, with a horizontal rail across the top.
- **Copper-coloured sheet material at the base and along at least one side wall.** This is the most consequential detail in the frame — see below.
- Metal post or bracket at left, terminating in what may be a pivot, knife-edge, or feedthrough.
- White EPS block at right supporting a dark cylindrical or rectangular object, with vertical wires adjacent.
- White tube or cable running from the left bracket toward the blob.

**Absent from the frame:**
- No vacuum chamber, no pumping port, no feedthrough flange.
- No visible torsion balance, load cell, or interferometric displacement sensor.
- No visible current instrumentation.
- No visible calibration standard or reference mass.

This is a bench-top setup at ambient pressure. Any thrust figure from this apparatus must be treated as air-ambient.

**The copper.** It is not determinable from a single frame whether the copper is (a) a grounded Faraday shield — good practice, and consistent with his stated worry about room charge — or (b) a ground plane / return electrode. The distinction matters enormously:

- If **shield**: it addresses the ambient-charge problem he describes, but places a large conductor within centimetres of a 100+ kV article. Image-charge attraction between the charged blob and the shield is then a first-order force, and any asymmetry in the blob's position or shape gives a net lateral component. The blob's geometry is visibly asymmetric.
- If **return electrode**: the device is completing a circuit through the enclosure and is not self-contained at all.

Either way, test §7.12 (ground-plane distance sweep) applies directly and is cheap.

**Assessment.** The image is consistent with the artifact picture in §6.5–6.6 and provides no evidence against it. It shows an enclosure that suppresses ambient charge exchange, not one that suppresses air. Nothing in the frame would detect a nanoamp of corona current inside the foam.

**Follow-up needed:**
- Is the copper grounded? To what?
- How is thrust actually measured? Nothing in this frame measures force.
- What is the cure age of this blob?
- Is the blob mechanically coupled to the box, or suspended independently?

### Images 2–3 — T-Blade assembly and instrumented chamber article

**Source:** ept.space/showcase, supplied 2026-08-25.

**Image 2 — "T-Blade thruster assembly."** Now identifiable against the patent as the FIG. 16/17 embodiment. Visible: a **laminated copper foil stack** (many layers — this is the large-area ground electrode, matching the patent's "V− connected to the copper tape") beside a **finned comb** of many thin parallel plates (the "blades," elements 100₁…100ₙ). Two such stages, upper and lower, sandwiched between transparent plates on white ceramic or PTFE standoffs — the patent's "non-electrically conductive means 103." Mirror-finish metal baseplate below.

This is the first confirmation that the "grooves" of §12.1 are a multi-blade comb, and it matches the patent's blade configuration directly. The layered copper stack is consistent with the disclosed strategy of maximising ground-plane area.

**Image 3 — instrumented article in the vacuum chamber.** A horizontal arm on a central pivot, 3D-printed white frame, with **electronics and what appears to be a battery pack at the centre** — consistent with 1:47:29 ("in the middle is a power supply or Bluetooth") and with 1:54:17's internal-supply solution (§12.3). Amber/Kapton-wrapped article with gold-green panels at the right end; a second frame with copper-coloured square pads at the left end. Stainless chamber, aluminium extrusion support cage, circular acrylic plate below.

**The consequential detail: a large copper disc is mounted on the chamber wall, close to the article's swept path.** Per §14.4, Talley (1991) — cited in their own patent — found a force in exactly this configuration and attributed it to electrostatic interaction between device and chamber. **Whatever that disc is for, its presence makes the ground-plane distance sweep (§7.12) mandatory rather than optional**, and it should be the first question asked of this apparatus.

Second observation: the arm carries **different articles at each end.** If one is the dummy (§15/G10), this image is the closest thing to a picture of the programme's key control — and it is not possible to tell from the frame whether the two match on mass, area or capacitance.

### Images 4–5 — the 140 kV needle, two extremes of swing

**Source:** podcast video frames, supplied 2026-08-25. Image 4 = rightmost position, Image 5 = leftmost. Corresponds to transcript 22:15–22:35 and 2:00:32–2:01:18.

**Observed:**
- A red high-voltage lead descending from above, terminating in a small cylindrical assembly — the brass rod in a plastic tube described at 2:00:44.
- **The HV lead is the suspension.** No separate string or pivot is visible.
- A white styrofoam block on the floor with a **ruler laid flat on it**, positioned to read horizontal travel — matching 2:00:56, *"I have a ruler there to try to measure how far it moved."*
- Smooth grey floor, unknown surroundings, no enclosure, no shielding, no instrumentation.

**Assessment:** see §5.1. Three findings:

1. **Suspension-by-energised-cable.** The artifact Aurigema himself describes at 1:53:41 is maximally present in the founding experiment, because the charged conductor and the pendulum string are the same object.
2. **The 6 mN is derived, not measured** — inferred from deflection via F ≈ mg·tan θ, with neither mass nor angle stated anywhere in the record.
3. **Apparent amplitude discrepancy.** Using the ruler for scale, the swing looks like ~10–20 cm against a recollected "3 or 4 feet." Possibly a different article; worth asking, not worth concluding from two frames.

**The frames are also the answer to a question §5 could only raise.** The transcript describes this experiment; the images show it is exactly as bad as the description implied, and one degree worse in the suspension.

**Follow-up:** What was the article's mass? What deflection was recorded? Was the return path instrumented at all? Was this the same device as the "3 or 4 feet" claim?

### Image 6 onward `[PENDING]`

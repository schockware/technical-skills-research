# Research Taxonomy: Realm × Word

**Scope:** the management of the software development lifecycle and the roles surrounding it. The verdict-words here are diagnostic terms for *expectations* issued inside that process — not labels for people, cultures, or beliefs. See [[__DISCLAIMERS_EXPECTATIONS_AND_BELIEFS]] for the fence and [[___DISCLAIMERS]] for standing.

This taxonomy has **two axes**:

- **Axis A — the Realm:** *what kind of object is being judged.* (Assumption → Expectation → Belief.)
- **Axis B — the Word:** *how it fails.* (Illogical → Irrational → Unreasonable.)

A case lands in a cell `(Realm, Word)`. The discipline of the framework — and its safety — is keeping the two axes distinct, and keeping every verdict on the **Expectation** row.

---

## 1. Axis B — The Word (how it fails)

A gradient of **wall-hardness**. Each word names a different *kind* of wall an expectation runs into.

| Word | Wall | Domain | One-line test |
| :--- | :--- | :--- | :--- |
| **Illogical** | impossible **in principle** | formal logic | No satisfying assignment exists in *any* world. The demand contradicts itself. |
| **Irrational** | impossible **in practice** | physics / biology | Logically coherent, but demands an output from incompatible or absent inputs. "Magic thinking." |
| **Unreasonable** | infeasible **in context** | law / psychology | Real and possible, but violates time, capacity, resource, or social-contract limits. "Elastic thinking." |

> **Hardest → softest:** `Illogical → Irrational → Unreasonable.`
> Illogical is the **floor**: a self-contradiction can't be rescued by more time, more resources, or a different universe. Irrational might be rescued by different physics. Unreasonable might be rescued by different constraints.

### §1.3 — The Word axis is not a flat line: one cut, two zones

The three words don't sit as three equal steps. There is a **primary partition** and then a sub-structure:

```
   REASONABLE  │  ─────────────── not-reasonable ───────────────
   (fits)      │  Unreasonable   │   Irrational  ·  Illogical
               │  (negotiable    │   (hard walls — no negotiation
               │   middle)       │    rescues them)
               └─ the cut that   └─ the cluster
                  triggers a flag
```

- **The primary cut is Reasonable vs. not-Reasonable.** This is the line that matters operationally: anything on the not-reasonable side is **flagged for closer inspection** (see §1.4). Crossing the line is the event; *which* failure-word applies is the follow-up.
- **Unreasonable is the negotiable middle.** It acknowledges reality and fails only on context (time, capacity, resource, social contract). It *shades toward* Reasonable — a different deadline or an extra pair of hands can move it back across the line. It is the one not-reasonable category that negotiation can rescue.
- **Irrational and Illogical cluster as the hard walls.** One is a physical/biological wall, one a logical wall, but they share the decisive property: **no negotiation rescues them.** More time, more people, more money do nothing. They are qualitatively together, on the far side from the negotiable middle.

*This matches the grading data in [[01_FINDING_THE_GRADIENT_FOR_WORD]]:* 🟡 was the large fuzzy region that shaded toward 🟢, while 🔴/🟣 were the clustered hard calls where graders only ever disagreed about *which* wall — never about *whether* it was a wall.

### §1.4 — Default to "not-reasonable," never "not-rational"

When flagging a composite that fails *any* of the three tests, the default umbrella term is **not-reasonable** — not "not-rational." This is a deliberate, mathematically motivated rule:

- **"Not-reasonable" is the accurate name for the union.** Every failure — unreasonable, irrational, or illogical — is at minimum *not-reasonable*. Formally: `not-reasonable = {unreasonable ∪ irrational ∪ illogical}`. Irrational ⊂ not-reasonable and Illogical ⊂ not-reasonable, but not the reverse. The flag should be named after the **union**, and the union's natural-language name is *not-reasonable*.
- **"Not-rational" names only a subset and imports baggage.** It correctly describes only the *irrational* member, so using it as the umbrella names the whole set after one of its parts — exactly the word-compression the disclaimers forbid (guards #4/#5). Worse, "not-rational" reads as a verdict on a *mind* — the #HiddenFigures person-attribution slide — whereas "not-reasonable" stays on the *expectation*.

**Rule:** the umbrella flag is *not-reasonable* ("inspect this"); the three specific words are the fine-grained grades underneath it. Reach for a specific word only after the cut is made, and never let a specific word stand in for the union.

---

## 2. Axis A — The Realm (what is being judged)

A gradient of **commitment and visibility**.

| Realm | What it is | Cost | Relation |
| :--- | :--- | :--- | :--- |
| **Assumption** | a tacit, unexamined input taken as given | cheap, invisible until surfaced | a belief not yet noticed |
| **Expectation** | an assumption *acted upon* — projected outward as a directed demand, with a deadline or standard | the working realm | an assumption aimed at someone |
| **Belief** | a committed, identity-adjacent conviction, defended when challenged | expensive to hold and to drop | an assumption promoted and fortified |

> **Cheap → expensive:** `Assumption → Expectation → Belief.`
> The research program operates on the **Expectation** realm. Assumptions are where expectations come from; beliefs are upstream cultural facts the expectations inherit.

---

## 3. The Grid (Realm × Word)

Any realm can fail in any of the three ways. The cell locates both *what* is wrong and *how*.

| | **Illogical** | **Irrational** | **Unreasonable** |
| :--- | :--- | :--- | :--- |
| **Assumption** | a premise that contradicts itself, held unnoticed | a tacit premise that magic-thinks reality | a tacit premise that human capacity is infinite |
| **Expectation** | a self-contradictory demand issued as work | a demand for output from incompatible inputs | a demand that exceeds time / capacity / contract |
| **Belief** | a conviction false on its own terms | *(upstream cultural fact — described, not judged)* | *(upstream cultural fact — described, not judged)* |

**Where the SDLC work lives:** the **Expectation** row. The anecdotes in `Author's Experiences/` are Expectation-row cases. The Belief row is upstream context — the framework *traces* its influence on expectations but does not put verdict-words on it.

---

## 4. The Fence Is a Realm Boundary

The scope fence from the disclaimers has a coordinate on this grid:

> **The work judges the Expectation row. A verdict-word landing on the Belief row has crossed the fence.**

- The framework may call an *expectation* illogical, irrational, or unreasonable. It may **not** put those words on a *belief*.
- **The danger is the diagonal:** risk = *severity of the Word* × *commitment of the Realm*. The bottom row — any verdict on a belief — is where the apparatus becomes a weapon.

**What the area does with the central belief ("smart → can learn anything"): describe & trace only.**
1. **Describe** it as a cultural fact to be understood.
2. **Trace** how it installs expectations — Axis 0 (fictional media) → the job description that demands the composite.
3. **Verdict only the downstream expectation**, never the belief.

The belief is a cultural fact to understand, never a defendant to sentence. (See [[___DISCLAIMERS]] on same-seat humility: present certainty is not a vantage point above the belief — which is *why* it is described, not judged.)

---

## 5. SDLC Specimen Matrix

The recurring composite-role expectations, placed on Axis B. These are the cases the research synthesizes.

| Expectation (SDLC) | Word | Structural root cause | Proxy |
| :--- | :--- | :--- | :--- |
| **Self-contradictory demand** (e.g. *finish report* ∧ *don't stop the task that fills the only available time*) | **Illogical** | No satisfying assignment in any world. | Logical contradiction |
| **Full-stack dev knowing *all* languages/stacks** | **Irrational** | Exceeds human retention/retrieval limits; ignores syntax & paradigm conflicts. | Data saturation |
| **CTO as IC + Manager + Strategist, simultaneously** | **Irrational** | Requires mutually exclusive cognitive modes at the same time. | Context-switching thrashing |
| **One headcount practicing all specialties + managing** | **Unreasonable** | Buys two full-time skill sets for one slot. | Capacity bottleneck |
| **Dev building code while managing people** | **Unreasonable** | Collides a Maker's schedule with a Manager's schedule. | Resource misalignment |
| **Lead managing and doing deep ICwork concurrently** | **Unreasonable** | Availability requirements cannibalize focus blocks. | Linear-time exhaustion |

> The CTO composite sits at **Irrational, not Illogical**: being in three cognitive modes at once is a *physical/biological* wall (you can't occupy three states simultaneously), not a self-contradiction. The self-contradiction floor is reserved for demands with literally no satisfying assignment.

---

## 6. SDLC Stress Tests

Recurring shapes that should sound familiar to anyone who has run a development process.

### The Mind-Reading Trap (requirements from zero input)
- **Irrational:** Expecting a developer to build to spec that was never communicated — inferring concrete requirements from nothing. *(Treats code as magic that resolves unwritten equations.)*
- **Unreasonable:** Delivering the full spec *after* the work is underway and expecting no rework. *(Acknowledges the data exists, ignores the cost of injecting it late.)*

### The Spatial-Time Continuum (estimation & deadlines)
- **Irrational:** Committing a fixed ship date before scope is known and assuming it holds. *(Expects the schedule to bend reality.)*
- **Unreasonable:** Demanding a known multi-sprint scope land in one sprint by "pushing harder." *(Possible on paper, statistically improbable in practice.)*

### The Inference Loop (product & bureaucracy)
- **The scenario:** Forcing developers (or any downstream role) to infer concrete requirements from zero input.
- **The verdict:** *Telepathic architecture error.* The **input** is **Irrational** (treats execution as magic that resolves unwritten equations); the **downstream execution** is **Unreasonable** (forces high-stress, low-probability guessing loops → burnout and systemic rework).

---

## 7. Environment and Cultural Spectrum

Rational actors still issue irrational or unreasonable expectations depending on the environment they sit in. **A case's cell is a property of the *expectation* and the environment that issued it — never of the person.** The Cultural Expectations area exists to surface *why* a given environment produces a given cell: what upstream beliefs, role designs, and feedback-loop failures make an illogical demand feel like an ordinary Tuesday.

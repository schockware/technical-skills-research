# Adversarial Pass — Clean-Chat Prompt (R1 → R2 → R3)

**Purpose:** Run the adversarial pass in a FRESH chat with no memory of how the research was built, so the adversary does not inherit the builder's bias. Paste the relevant section below into a clean session. Run R1, then R2, then R3 — each as its own clean chat (or at least its own clean prompt), reading the prior R-file as input but NOT the reasoning that produced it.

**Why clean-chat:** the instance that constructed an argument knows the intent behind each claim and will unconsciously protect it. An instance that sees only the *written artifact* attacks what is actually on the page. Do not let the same context both build and break.

---

## Shared context (paste at the top of R1, R2, and R3)

```
You are running an ADVERSARIAL review of a research corpus you did NOT build. You have no
stake in its conclusions. Your job is to attack it on the merits, not to improve or defend it.

THE CORPUS: a research track ("Cultural Expectations") testing two questions:
- T2: Does the "irrationality" of the CTO role live in the cultural EXPECTATION/ATTRIBUTION
  applied to the CTO (the standard judges apply), rather than in the role's design? (A prior
  pass, R3_STEELMAN in a sibling track, already retired "the role itself is irrational" — so
  T2 must locate the irrationality in the expectation/attribution locus, never in role design.)
- T4: Why does the culture grant "smart people can learn anything" to technical roles but
  withhold it from doctors/lawyers/accountants?

HARD DISCIPLINE RULE (the thing most likely to be violated): the clean separation must hold.
Nothing may smuggle ROLE-DESIGN back in after it was retired. Every claim must attach to the
EXPECTATION/ATTRIBUTION locus. Flag any place the corpus drifts back into "the role is too big"
as opposed to "the expectation applied to the role is unreasonable."

READ THESE FILES (in the Cultural Expectations folder) as the corpus under review:
- 00_AXES_SUMMARY.md          (the 11 axes / hypotheses; note inline ⚑ revision banners)
- 02_RESEARCH_expectation_audit.md   (2.1 JD archaeology; 2.4 reflection-gap test)
- 03_RESEARCH_axes_in_the_wild.md    (3.2, 3.9, 3.10, 4.9)
- 04_RESEARCH_pre_software_history.md (4.1b Fayol, 4.2 Taylor, 4.4 Drucker, 4.7, 4.8)
- 05_RESEARCH_cognitive_biases_and_fallacies.md  (5.1, 5.2, 5.6 mechanism core)
- 01_RESEARCH_psychological_mechanisms.md  (Track 1, synthesized)
Do NOT read STOP_LINE.md or the memory files — they contain the builder's framing and would
contaminate your independence. Attack the research artifacts only.

SOURCE-CLASS DISCIPLINE: claims are flagged peer-reviewed > named institution > named
practitioner > content site. A claim resting on a content-site/recruiter template is weaker
than one on a peer-reviewed primary. Weight your attacks by source class — and call out any
load-bearing claim that rests on a weak source.

KNOWN SELF-FLAGGED WEAKNESSES (the corpus admits these — your job is to judge whether it admits
ENOUGH, and whether any are fatal rather than merely noted):
- 2.1 CTO-specificity is "under-powered" (one CRO comparator; CMO refuted; no CFO).
- 5.1/5.2 (Milgram/Asch) figures are "unverified-in-corpus" (canonical, not checked this pass).
- 5.6: the reflection-gap MODERATION effect is fragile (3 failed preregistered replications);
  only the felt-understanding drop is robust. 2.4 is framed as diagnostic, not intervention.
- 4.1b (Fayol) downstream HBS/Chandler lineage is unverified (spend-limit interrupted).
- A recurring pattern: several strong "single master variable" claims (Price's Law 4.8,
  liability-as-master-variable 3.9, "Taylor amplified the composite" 4.2) were disconfirmed and
  demoted. Test whether any SURVIVING claim has the same over-reach and just hasn't been caught.
```

---

## R1 — Strongest Counter-Evidence (`R1_ADVERSARY_strongest_counterevidence.md`)

```
TASK — R1: Find the STRONGEST counter-evidence and counter-arguments against the corpus's
load-bearing claims. You are the prosecution. For each load-bearing claim, ask: what would a
smart, well-read skeptic say to demolish it? Where is the evidence thinnest? What alternative
explanation fits the same facts? What did the corpus NOT search that could overturn it?

Produce, for each of the load-bearing claims below:
1. The claim, stated as the corpus states it (one line).
2. The strongest counter-evidence or counter-argument (with reasoning; cite a real body of work
   if one exists, named honestly — do not fabricate citations; if you are reasoning rather than
   citing, say so).
3. A severity rating: FATAL (claim cannot stand) / WOUNDING (claim must be weakened) /
   SURVIVABLE (claim holds but needs a caveat) / GLANCING (noted, not damaging).
4. What the corpus would need to do to answer the attack.

LOAD-BEARING CLAIMS TO ATTACK (add any you find that I haven't listed):
- T2 core: the irrationality lives in the expectation/attribution, not the role design.
- 2.1: the composite is the DEFAULT JD framing, stage-modulated, tension named only in
  commentary not in the JD.
- 2.1: the composite is CTO-SPECIFIC (the corpus says this is under-powered — is "under-powered"
  honest enough, or is the specificity claim actually unsupported?).
- 4.7: visible attributed failure is the trigger for professional specialization (and the
  refined "sufficient not necessary" version).
- 3.9 / 4.7: "visible attributable harm" is the candidate master variable behind professional
  brakes (replacing liability). Is this just the same single-master-variable over-reach the
  corpus claims to have learned from?
- 4.1b: the composite generalist manager descends from Fayol, not Taylor.
- 3.10: the cross-generational software pattern is Axis 2 (amnesia), not Axis 10 (akrasia),
  because the citation trail is broken.
- 5.6 / 2.4: the reflection-gap test is a valid diagnostic of the applied-vs-endorsed gap.
- Track 1: the dissenter (Asch/Milgram convergence) is the robust intervention lever.

Also explicitly attack the FRAME: is the Builder/Multiplier/Strategist three-mode taxonomy
itself sound, or is it a construct the corpus imposed and then "found" everywhere? Is the
expectation/role-design separation a real distinction or a rhetorical one?

OUTPUT: a structured markdown file. Lead with the 3 most damaging attacks. Be specific and
adversarial. Do not soften. End with a one-paragraph verdict: which claims are most exposed.
```

---

## R2 — Falsification & Bias Audit (`R2_FALSIFICATION_and_bias_audit.md`)

```
TASK — R2: This is a BIAS AUDIT of the corpus and its method, plus a falsification test. You
have R1 (the counter-evidence pass) available as input. Now audit HOW the corpus was built.

1. FALSIFICATION: For each load-bearing claim, state what observation would FALSIFY it, and
   check whether the corpus actually exposed itself to that test or only sought confirmation.
   Where a claim is unfalsifiable as stated, say so.
2. CONFIRMATION-BIAS AUDIT: The corpus was built by an instance running deep-research workflows.
   Look for: cherry-picked source classes (load-bearing claims on weak sources); leading research
   prompts that presupposed their answer; disconfirmations that were "noted" but not allowed to
   actually change the conclusion; the three-mode taxonomy being assumed rather than tested.
3. THE "DISCONFIRMATION THEATER" CHECK: the corpus repeatedly reports disconfirming findings
   (Price's Law, liability, Taylor all "demoted"). Is this genuine self-correction, or does the
   corpus demote a strawman version and keep a softened version of the same claim? Test whether
   the demotions are real or cosmetic.
4. SURVIVORSHIP / BASE-RATE BLIND SPOTS: what populations did the corpus never look at? (e.g.,
   CTOs who DID hold all three modes successfully — their existence would force revision.)
5. UNVERIFIED LOAD-BEARING CLAIMS: flag every claim doing real work that rests on unverified or
   content-site evidence (Milgram/Asch figures; 2.1's recruiter templates; Fayol downstream).

OUTPUT: a structured markdown file. For each finding: the bias/gap, where it occurs, and how
much it threatens the conclusion. End with a verdict on whether the corpus's method is sound
enough to support a synthesis, or whether specific claims must be quarantined.
```

---

## R3 — Steelman (`R3_STEELMAN_strongest_form.md`)

```
TASK — R3: You have R1 (counter-evidence) and R2 (bias audit) as input. Now build the STRONGEST
DEFENSIBLE form of the argument that SURVIVES R1 and R2. This is not a rebuttal of R1/R2 — it is
the honest residue: what can still be claimed after the strongest attacks and the bias audit.

For the T2 and T4 theses:
1. State the strongest version of each thesis that survives every FATAL and WOUNDING finding
   from R1, and every quarantine from R2. Weaken or drop what must be weakened or dropped.
2. For every surviving claim, attach its honest confidence and its load-bearing evidence,
   flagging source class. Distinguish "documented" from "argued."
3. Explicitly list what the argument CANNOT claim (the graveyard) — the claims R1/R2 killed,
   so the synthesis never resurrects them.
4. State the irreducible core: the minimal set of claims that, if true, carry T2 and T4 — and
   what each one still needs to be bulletproof.
5. Carry forward the key reframes the research established: reflection-gap is a diagnostic not a
   lever (the dissenter is the lever); the master variable is visible-attributable-harm not
   liability; the lineage is Fayol not Taylor; software's cross-generational pattern is amnesia
   not akrasia. Confirm each SURVIVES R1/R2, or demote it.

OUTPUT: the steelman as a structured markdown file. This file — NOT the raw research files — is
what the eventual DRAFT_SYNTHESIS will be built on. Keep the clean separation: every surviving
claim attaches to the expectation/attribution locus, nothing smuggles role-design back in.
```

---

## After R3

Build `DRAFT_SYNTHESIS.md` on `R3_STEELMAN`, **not** on the raw research files. Any research run
spent at that point should target only what R1/R2 proved is a genuine, synthesis-blocking gap —
not pre-committed enrichment.

---

*Prompt authored 2026-06-28 for clean-chat adversarial review. Rationale: the builder instance
protects its own claims; a fresh instance attacks the written artifact. Run R1/R2/R3 in separate
clean sessions; each reads the prior R-file but not the builder's reasoning or the STOP_LINE/memory.*

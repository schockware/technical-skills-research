# Corpus Conventions — Greppable Anchors

**Purpose:** One place that defines every machine-greppable marker used across the CTO research corpus, so claims, citations, gaps, and risks can be located with a single `grep` regardless of which file they live in. Survives the planned draft-split — when the publishable version forks off, these anchors are the seams that tell you what's safe to ship.

**Created:** 2026-06-24

> **Load-bearing premises (2026-06-25):** Two assertions the thesis explicitly stands on are stated in `17_PREMISES_load_bearing_assumptions.md`. **P1 (component-equivalence)** licenses all borrowed non-CTO evidence — cite it wherever IC→EM / founder-transition / cross-domain evidence is used for a CTO claim. **P2 (etymology-is-contingent)** marks the etymology/investor/misnomer layer as non-load-bearing. These came out of the independent `R1`/`R2` adversarial review.

---

## The tag families

All tags are HTML comments (`<!-- ... -->`) so they're invisible in rendered markdown but visible in the editor and to grep. Format is always:

```
<!-- TAG: ID — short human note. Cross-ref pointer. -->
```

- `TAG` — the family (uppercase, from the table below).
- `ID` — a stable kebab/caps identifier, prefixed per family (e.g. `AX-`, `GAP-`). Unique across the corpus.
- `note` — one line, human-readable.
- `pointer` — where to look next (`See 07_APPENDIX`, `See 09_RESEARCH`, etc.).

| Tag | Prefix | Means | Lives in | Points to |
|---|---|---|---|---|
| `APPENDIX-REF` | `AX-` | A claim that rests on a citation under review | draft / fulltext | `07_APPENDIX` callout of same ID |
| `GAP` | `GAP-` | A confirmed research gap (no source exists yet) | any | `09_RESEARCH` / research agenda |
| `RISK` | `RISK-` | A framing/logic risk to resolve before publishing (e.g. arguing-from-silence, causal-narrative overreach) | any | the note explaining it |
| `OPEN` | `OPEN-` | An unresolved authorial decision | draft | open-questions list |
| `XREF` | `XR-` | A pointer to a related claim elsewhere in the corpus (non-citation) | any | the target section |

Every `AX-` / `GAP-` / `RISK-` ID should be **bidirectional**: the anchor at the claim and a matching entry at the destination share the same ID.

---

## How to grep

```bash
# Every claim depending on an unverified citation (the publish-gate list):
grep -rn "APPENDIX-REF" CTO/

# A specific claim and its verification record, both ends:
grep -rn "AX-SCOPEKIND" CTO/

# All confirmed research gaps:
grep -rn "GAP:" CTO/

# All framing risks to clear before publication:
grep -rn "RISK:" CTO/

# Everything machine-anchored, any family:
grep -rnE "(APPENDIX-REF|GAP|RISK|OPEN|XREF):" CTO/
```

The publish-gate workflow: before forking the clean version, `grep -rn "APPENDIX-REF" CTO/08_DRAFT*` lists exactly the claims still gated on citations. Resolve or soften each, then split.

---

## Active anchor registry

The source of truth for *status* is each destination file (e.g. `07_APPENDIX`). This list is just an index so a new reader can see the whole anchor namespace at a glance. Keep IDs here in sync when adding new ones.

### `AX-` (citation-dependent claims) → status in `07_APPENDIX`
| ID | Draft location | Claim | Status |
|---|---|---|---|
| `AX-MW2018` | `08_DRAFT` §1 | Transformation model + identity mechanism (Mathias & Williams 2018) | ✅ Verified (full text) |
| `AX-VL2023` | `09_RESEARCH` → draft | Offload success conditions: psych safety + value fit (Van Lancker et al. 2023) | ✅ Verified (full text) |
| `AX-SCOPEKIND` | `08_DRAFT` §3.2 | Scope-vs-kind; C-suite origin dates | ⬜ Unverified |
| `AX-INVESTOR` | `08_DRAFT` §3.3 | Investor-signaling causal chain | ⬜ Unverified + RISK |
| `AX-COMPRESSION` | `10_RESEARCH` Pt2 | $1.1M distributed cost / 4–6:1 ratio (not yet in draft) | ⬜ Unverified + RISK |
| `AX-EQUITY-PREMIUM` | `10_RESEARCH` Pt1 | 20–50% co-founder equity = revealed price of Builder work | ⬜ Unverified |
| `AX-REVERSION` | `11_RESEARCH` Stage 1 | ~50% IC→EM reversion (Weekes/Figma) — most load-bearing number | ⬜ Unverified |
| `AX-VPENG-TIMELINE` | `11_RESEARCH` | 8–15yr IC→VP Eng path vs 18–24mo CTO demand | ⬜ Unverified |
| `AX-CTO-TENURE` | `12_RESEARCH` Sol 2 | ❌ 2.5yr unsupported → rewritten to churn (Russell Reynolds/Korn Ferry) | ✅ Corrected in source |
| `AX-BIFURCATION-COST` | `12_RESEARCH` Sol 3 | CTO+VP Eng $350–600K combined | ⬜ Unverified |
| `AX-COMPETENCE` | `08_DRAFT` §1 | Competence trap + cross-domain overconfidence (replaced TEE as human mechanism) | ⬜ Pending #20/#21 |
| `AX-INDEX78` | `10_RESEARCH`, `00` | ⚠️ "founding CTO OR technical CEO" (corrected from "at seed") | ✅ Corrected in source |
| `AX-ATROPHY` | `08_DRAFT` §2a, `11`, `12` | Skill atrophy after mgmt move (qualitative; dropped false "2–3yr" precision) | ✅ Corrected in source |
| `AX-CURSE` | `13_RESEARCH`, `14_RESEARCH` | Curse of expertise (Camerer 1989 + Hinds 1999 + Gupta 2017) — human replacement for TEE | ✅ Verified (peer-reviewed) |
| `AX-OXYGEN-EVAL` | `15_RESEARCH` | Oxygen = "measure from below"; CTO breaks both above/below anchors | ✅ (#5 verified) |
| `AX-CTO-ISOLATION` | `15_RESEARCH` | 3 blockers to external CTO evaluation (IP, role-incomparability, hierarchy) | ⬜ HBR-loneliness is CEO analog |
| `AX-HIPPO-DECAY` | `15_RESEARCH` | Feedback signal degrades with tenure (authority bias + org filtering) | ⬜ Sunstein/Hastie, Kohavi |
| `AX-STAGE-DURATION` | `15_RESEARCH` | 616-day seed→A median; training retroactive-by-design | ⬜ content site, verify |
| `AX-NOVELTY-BASELINE` | `15_RESEARCH` | Berray 2002 + McKinsey classify by context, not stage-fit | ⬜ verify — novelty rests on it |

### `GAP-` (research gaps) → stated honestly, not verified
| ID | Where | Gap |
|---|---|---|
| `GAP-CTO-TRANSITION` | `11_RESEARCH` tail | Founding-CTO Builder→Multiplier success rate + predictors — unstudied; the framework's central falsifiable test |

### `RISK-` (framing risks) → notes where flagged
| ID | Where | Risk |
|---|---|---|
| `RISK-ASYMMETRY` | `07_APPENDIX` review note #3; `00_/04_` corpus | "0 Strategist findings" used as confirmation = arguing-from-silence |
| `RISK-INVESTOR-CAUSAL` | `08_DRAFT` §3.3 / `07_APPENDIX` `AX-INVESTOR` | Causal narrative, not measured study — publish as "consistent with," not "caused" |
| `RISK-COMPRESSION-RATIO` | `10_RESEARCH` headline / `07_APPENDIX` `AX-COMPRESSION` | ✅ framing resolved (now "~4–6:1 on cash" + methodology note); remaining work is equity-package data, not framing |
| `RISK-TEE-DOMAIN` | `09_RESEARCH` / `07_APPENDIX` #10 | TEE (Mars 2026) is an AI-systems paper — do NOT use as the human failure mechanism; use competence trap + Dunning-Kruger + role-identity attachment |
| `RISK-SURVIVORSHIP` | `16_RESEARCH` + `../*/14_…` success thread | Success cases = presence-as-evidence (mirror of RISK-ASYMMETRY). Mitigate with 3-layer per-claim tagging, never a success checklist |

### `AX-` finding (promoted result, not a citation) → status in `07_APPENDIX`
| ID | Where | Finding | Status |
|---|---|---|---|
| `AX-NO-TRIPLE-MODE` | `16_RESEARCH` headline | No documented CTO navigated all 3 modes as continuous tenure; success = graceful exit | ⬜ 5 cases anecdotal; finding strong, verify cases |

*(OPEN- IDs to be registered here as they're introduced. `XR-ASYMMETRY-DRAFT` tracked inline at its two sites.)*

---

## Rules for adding anchors

1. **Bidirectional or it doesn't count.** A new `AX-`/`GAP-`/`RISK-` anchor must have an entry at both ends sharing the ID. A one-ended anchor is a dangling pointer.
2. **One ID, one concept.** Don't reuse an ID for a different claim. If a claim splits, suffix (`AX-INVESTOR-A`, `-B`).
3. **Register it here.** Add the ID to the registry above so the namespace stays visible.
4. **Note travels with the claim.** The framing caution on a `RISK-` anchor must appear at the claim site, not only in the appendix — a reader editing the draft should see it without leaving the file.

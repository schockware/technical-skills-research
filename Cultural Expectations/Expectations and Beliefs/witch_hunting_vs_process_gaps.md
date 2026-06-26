# Witch Hunting Is Not a Solution
### A Framework for Process-First Accountability
#### Internal Reference — SDLC & Cultural Research

---

## Preamble

This document exists for two contexts that share the same problem.

In SDLC, when a system produces a defect, the instinct is often to find the person responsible and hold them accountable. That instinct feels like justice. It is not. It is a reflex — and it actively prevents the kind of investigation that would stop the defect from recurring.

In cultural and historical research, when we document how groups were marginalized, excluded, or had their labor misattributed, the instinct is to name the people who did it and hold them responsible. That instinct also feels like justice. It is also a reflex — and it also actively prevents the kind of analysis that makes the findings useful, durable, and hard to dismiss.

Both contexts require the same discipline: **follow the process, not the person.**

This document is a tool for both. It is also, frankly, a personal anchor for moments when the evidence is enraging and the drum is right there.

> **How this fits the framework.** This is the **operational form of guard #3** ("rates demands, never people") from [[__DISCLAIMERS_EXPECTATIONS_AND_BELIEFS]] — and it is the *same discipline already practiced* in the Author's Experiences diagnoses, where the verdict was repeatedly located **upstream** ("the manager was not at fault"; "the junior dev is the least culpable party"). "Find the gap the verdict is pointing to, and document that instead" is this corpus's central move stated as a procedure. The "if we replaced that person tomorrow, would it happen again?" test is the clean operationalization of the [[project-brake-location-pattern]] finding: when the answer is *yes*, the brake was never in the person. Companion docs: [[failure_language_framework]], [[language_auditor_prompt]], [[common_vs_normal_definition_doc]]. See [[00_README]] for the map.

---

## The Core Principle

**All system failures are a collection of decisions that produced a measurable defect.**
<!-- ⚑ ACCURACY-FLAG [universal claim — "all"]: Not defended for environmental (power/hardware), stochastic (bit-flip, race condition), or external-cascade failures, which aren't "collections of decisions." RECOMMEND scoping: "Most recurring/addressable system failures are…" or define "system failure" to exclude purely stochastic/environmental events. The discipline (follow process not person) survives the hedge intact. -->


The fault or defect lays in the process that created and maintained the system — not in a single person, not in a single moment, and not in a single decision made in isolation.

This is not a statement of forgiveness. It is a statement of accuracy.

The process produced the conditions. The process failed to catch the warning signs. The process distributed decision-making in ways that made the outcome possible. The process is where the investigation belongs.

---

## What Witch Hunting Actually Is

Witch hunting is a reflex. It is the emotional discharge of institutional anxiety onto the nearest available person.

It feels like accountability. It produces the opposite.

When an investigation terminates at a person rather than following the chain back to the process, it:

- **Closes the loop prematurely** — a person has been found, therefore the cause has been found. It has not.
- **Lets the process escape examination** — the same gap remains. The same conditions persist. The next person to occupy that role inherits the same set-up for failure.
- **Teaches concealment** — if the organization's response to a visible failure is to find someone to burn, the rational response is to make failure invisible. Reporting stops. Data disappears. Incidents compound silently.
- **Selects out the wrong people** — honest reporters, risk-takers, and people who surface problems early learn that visibility is dangerous. They leave or go quiet. The people who remain are better at managing perception than at managing systems.
- **Personalizes a structural problem** — which is the most consequential harm of all, because a personalized problem ends when the person is gone. A structural problem continues until the structure changes.

Witch hunting does not produce accountability. It produces a sacrifice. Those are not the same thing. <!-- ⚑ ACCURACY-FLAG [universal stated as mechanism]: The five consequences above (closes loop, lets process escape, teaches concealment, selects wrong people, personalizes) are sound inferences but cited with no org-behavior evidence. "Does not produce accountability" is absolute; evidence supports "typically does not." This is a VALUE the project owns (process-first) — fine to assert as a value, but where it's framed as a behavioral prediction, hedge to "tends to" or add one traced example. Distinguish the value (own it) from the empirical claim (hedge it). -->


---

## The Decision Chain

Every system failure has a chain. The chain looks something like this:

```
A decision was made
↓
The conditions that made that decision possible were created
by earlier decisions
↓
The process either did or did not have a mechanism
to catch the problem before it compounded
↓
The mechanism either did or did not function as designed
↓
The failure became visible at the point of least
resistance — which is rarely the point of origin
```

The person visible at the end of that chain is often not the person who made the most consequential decision. They are the person standing closest to the defect when it surfaced.

Investigating the chain means asking:
- What decision produced this outcome?
- What made that decision possible?
- What process should have caught it and did not?
- Where in the process did the gap exist?
- Who owned the process — not the person, the process?
- What would need to change to make this outcome less likely?

These are the questions that produce durable answers.

---

## Redirecting a Witch Hunt in Progress

Witch hunts have momentum. They feel productive because they are active — people are moving, names are being named, energy is high. Redirecting them requires specific language, applied calmly and early.

### In the Room

When the conversation is converging on a person rather than a process, redirect with:

**"What condition made that decision possible?"**
This moves the question one step back up the chain without dismissing the observation.

**"What would have caught this earlier?"**
This shifts focus to the process gap rather than the person at the end of it.

**"If we replaced that person tomorrow, would this happen again?"**
This is the clean test. If the answer is yes — and it almost always is — the problem is the process.

**"What did the process expect to happen here, and what happened instead?"**
This reframes the investigation as a gap analysis rather than a blame assignment.

**"Let's document the chain before we draw conclusions."**
This buys time and introduces rigor without directly challenging the reflex.

### What Not to Say

- Do not defend the person being targeted directly — this personalizes the defense and escalates
- Do not dismiss the concern — the underlying frustration is usually legitimate even if the direction is wrong
- Do not call it a witch hunt out loud in the room — name the behavior you want, not the behavior you're redirecting

---

## What the Process Gap Investigation Should Look Like

Once the witch hunt has been redirected, the investigation needs somewhere to go. That somewhere is the process.

### Step One — Document the Chain
Write down every decision that contributed to the outcome, in order, without assigning fault. Who decided what, when, with what information available to them at the time.

*With what information available at the time* is important. Hindsight makes every decision look worse than it was. The investigation is not about what we know now. It is about what the process knew then and what it did with it.

### Step Two — Identify the Gaps
For each decision in the chain, ask:
- Was there a process that should have flagged this?
- Did the process exist and fail to function?
- Did the process not exist at all?
- Was the process circumvented, and if so, why — was it too slow, too unclear, too burdensome?

Gaps are not failures of people. They are failures of design.

### Step Three — Assign Process Ownership
Every gap needs an owner — not a person to blame, but a person or team responsible for closing it. Process ownership is forward-looking. It is about who is accountable for the fix, not who is responsible for the history.

### Step Four — Shore Up
Document the change. Implement it. Verify it. Make the new process visible enough that the next person in the chain can see it before they make the decision, not after.

### Step Five — Close the Loop Publicly
Whatever was investigated, share what was found and what changed. Not the names. The gaps and the fixes. This is what rebuilds trust after a visible failure — not the punishment of a person, but the visible improvement of the system.

---

## The Cultural Research Application

Everything above applies directly to historical and cultural research — including research into how groups were marginalized, excluded, or had their contributions misattributed.

The witch hunting reflex in this context feels like honoring the people who were harmed. It is understandable. When the evidence is clear that specific decisions caused specific harm to specific people, the drum is right there and it deserves to be banged.

But.

**Personalizing a systemic problem lets the system off the hook.**

If the marginalization of women in early computing is reduced to the bad decisions of specific men, then the argument becomes about those men. They can be defended. Their context can be invoked. Their contributions can be weighed against their failures. The research becomes a debate about individuals rather than an indictment of structures.

**The process framing is the stronger argument because it is harder to dismiss.**

"These institutional structures systematically misattributed intellectual labor, restricted access based on gender, and created credential gaps that were then cited as evidence of incapacity" — this is an argument that stands on documented, measurable, structural evidence.

"These specific people were bad" — this is a debate.

The women of early computing are not honored by naming their oppressors. They are honored by documenting what they built, making the gaps that obscured it visible, and producing research rigorous enough to close those gaps.

That is outcome-first research. That is the process gap investigation applied to history.

### The Personal Anchor

For moments when the evidence is enraging and the discipline is hard:

The witch hunt feels like justice but produces a sacrifice.
The process investigation feels slower but produces change.

One of those honors the people the research is about.
The other makes us feel better temporarily.

When the drum is right there — ask first:
*Am I documenting a gap, or am I assigning a verdict?*

If it is a verdict, hold it. Find the gap it points to. Document that instead.

The gap is the contribution. The verdict is the reflex.

---

## Summary

- All failures are collections of decisions that produced a measurable defect
- The fault lays in the process, not in the nearest available person
- Witch hunting terminates the investigation prematurely and teaches concealment
- The correct response is to document the chain, identify the gaps, and shore them up
- This applies equally to SDLC incidents and to cultural and historical research
- The process framing is not softer than the witch hunt — it is more rigorous, more durable, and harder to dismiss
- When the drum is right there: find the gap the verdict is pointing to, and document that instead

---

*Document version: Draft 1.0 — internal use, for review and iteration*

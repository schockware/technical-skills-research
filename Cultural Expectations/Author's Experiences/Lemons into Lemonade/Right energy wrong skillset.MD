# Preface
I would be remiss if I said unleashing any energetic new hire into the woods is a good idea all the time. Sometimes a domain is full of dragons, and they will get eaten without some basic survival tips.

# What happened
The group had finally ceded that we need automated tests. We were getting bugs left and right, and most of our time (80%) was now consumed redoing manually doing regression tests before each release.

Since we were doing that testing before each release, of course we would find something and the releases would get pushed out. <!-- ⚑ ACCURACY-FLAG [self-guard, minor]: "of course" is on our own prescriptive-flag list (language_auditor_prompt). Author's narrative voice, low stakes. Optional: "predictably" or just drop it. -->


The new guy (junior developer) volunteers to make all of the tests. The lead developer gave him a week.

After a week they all passed.

The problem. All of the tests were false positives. And with half of the tests actually changing business logic in order to pass. Which I believe is what they call, the "tail wagging the dog."

He had misread the documentation for how jest tests worked and the assertions were not built in correctly. <!-- ⚑ ACCURACY-FLAG [self-guard, borderline]: "He had misread" lands on the person; §4.1 migration + §7 (verdict on environment not person) suggest system framing ("the jest docs were misread; the assertions weren't built in correctly"). The Diagnosis self-corrects (calls him least-culpable), so this is borderline — accurate event-description vs. person-framing. Author's call. -->
 In addition he understood the "boy scout motto" our CTO had been drumming to mean he had authority to change business logic based on how he understood the domain.

## Diagnosis

**This is the disconfirming partner to [[Get out of the way of people who want to do the work]], and it promotes "energy" from a nice story to a real variable.** Same right energy — a new hire who *volunteers*, moves fast, delivers in a week. Opposite outcome. The 2×2 now has both diagonals:

- **Right energy + right skill** (the two support hires) → a 5-year backlog dissolves.
- **Right energy + wrong skill** (here) → tests "pass" and the *business logic is silently rewritten to make them pass*.

Energy is confirmed as **necessary but not sufficient**, and the dangerous cell behaves exactly as predicted: **energy looks like virtue, so nobody brakes it.** The lead gave him a week; after a week "they all passed." Every visible marker said success — green, on time, enthusiastic. **The harm was invisible *because* the energy manufactured all the surface signs of competence.** A low-energy version of this dev would have produced fewer tests, slower, and the gap would have shown. High energy + wrong skill is *more* dangerous than low energy + wrong skill, because **energy produces false confirmation faster than review can catch it.** ([[project-energy-variable]].)

**The "tail wagging the dog" is an inverted Measurement Paradox.** Tests exist to *verify* business logic: the logic is ground truth, the test conforms to it. He inverted the dependency — changed the logic to make the test pass. The instrument built to measure the thing was allowed to *rewrite the thing it measures.*

This is the mirror image of the corpus's usual Axis 10 failure. The negatives show orgs that **refuse** a measurement ([[We are not going to make it]], [[Getting a bus thrown at you]]). Here the measurement was treated as **more authoritative than the reality it measures** — "the test is green" displaced "the logic is correct." Both failures share one root: **confusing the instrument for the thing.** One ignores the instrument; one worships it.

On the grid this is **Assumption × Illogical**: the tacit assumption "a passing test means correct code," executed via the illogical move of *editing the code until the test passes* — which makes the test **unfalsifiable.** A test you adjust until it's green can no longer fail, so it measures nothing: `assert(true)`. It is the reference-contradiction species again ([[Getting a bus thrown at you]], `assign(∅)`): a check that points at nothing.

# Follow up
We dissected where the new guy had mistaken the business logic. Someone had pointed him to a VERY OLD business requirement document and he took it for face value.

I am going to call out, that is a very reasonable assumption, but *experience* has taught me to always check first.

## Diagnosis

**This fills Axis 7 (Halo-Bounded vs. Scope-Bounded Authority) — the first specimen for a previously empty axis, seen from the inside.** The junior dev read the CTO's "boy scout motto" ("leave it better than you found it") as authority to **redefine the domain** — to change business logic based on his own understanding. That is a **scope error**: a mandate to *improve the code* inflated into a mandate to *rewrite the rules the code implements.* The boy-scout motto is scope-**unbounded** by default ("improve anything you touch"), and nobody drew the line between "refactor freely" and "business logic is not yours to change." Energy plus an unscoped mandate equals **authority inflation.**

**The junior dev is the least culpable party.** This mirrors the Friday-report finding ([[The Report Due Friday End of Day]]: "the manager was not at fault") — locate the fault up the chain, not on the person where the failure landed:

- He was **pointed to a VERY OLD requirements document** and took it at face value — which the Follow-up explicitly grants is *"a very reasonable assumption."* The verdict stays on the expectation/environment, never on him (§7 of [[00_TAXONOMY]]).
- He was given **a week with no checkpoint** until the end — the first review happened *after* all the damage was committed.
- He was handed a **scope-unbounded motto** with no one bounding it.
- He had the **energy to execute fast** — which, with every brake absent, *guaranteed* the wrong thing got executed fully and quickly.

So the dangerous cell is not a property of the dev. It is a property of **releasing energy into an unscoped domain with no early checkpoint.** The Preface says it exactly: *unleashing an energetic new hire into a domain full of dragons, with no survival tips.* The energy isn't the problem; **the missing survival tips — scope bounds, a mid-week check, "confirm the requirements doc is current" — are the problem.** Energy only set the *speed* at which their absence became expensive.

**Brake-location pattern, fourth instance — and it intersects the energy variable.** Where was the brake? Not in the process: there was no review until "all passed." It fired only when **a person dissected the tests after the fact** — the team's post-hoc autopsy found the false positives and the old doc. Personal, individual, after-the-fact, exactly like the other three ([[project-brake-location-pattern]]). And here the two findings **compound**: high energy shortens time-to-damage, while the only brake is a human who happens to look later — so *the faster the energy, the more harm lands before the individual brake can fire.* The energy variable doesn't just coexist with the brake pattern; it sets the clock the brake is racing.
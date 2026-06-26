# Synopsis
Can we figure out where certain gradients of illogical, irrational, and unreasonable are?


# Taxonomy
| Word | Wall | Domain | One-line test |
| :--- | :--- | :--- | :--- |
| **Illogical** | impossible **in principle** | formal logic | No satisfying assignment exists in *any* world. The demand contradicts itself. |
| **Irrational** | impossible **in practice** | physics / biology | Logically coherent, but demands an output from incompatible or absent inputs. "Magic thinking." |
| **Unreasonable** | infeasible **in context** | law / psychology | Real and possible, but violates time, capacity, resource, or social-contract limits. "Elastic thinking." |

# Scenarios
We are going to composite these together and let Claude try and grade them.

## Experience Based Scenarios
### Practitioners
- 3 year old
- Rocket Scientist
- Pediatrition
- PhD Doctor
- Surgeon
- Senior Software Engineer
- Junior Software Engineer
- News Anchor
- A dog

### Activity
- Perform Surgery
- Launch a Satellite Rocket
- Launch a toy rocket
- Drink Water
- Drive a Car
- Write a research paper
- Find a bug in 100,000 lines of code
- Find a bug in 12 lines of code
- Call the White house press secretary and grill them on a political topic
- Eat applesauce with a spoon
- Eat applesauce with their hands

### Composite and Grades - How a Human Does it
*Author grades first, without reading Claude's pass below. One table per activity; grade each practitioner. Use the legend. Divergence between this and Claude's pass is the experiment — it shows where the gradient is fuzzy.*

**Legend:** 🟢 Reasonable · 🟡 Unreasonable · 🔴 Irrational · 🟣 Illogical
*The composite reads: "Expect **[Practitioner]** to **[Activity]**." Fill Grade (and Why if you want). Don't peek below.*

#### Perform Surgery
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical| They can barely navigate a spoon let alone a scalpel. That alone disqualifies them. |
| Rocket Scientist | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Pediatrician | 🟡 Unreasonable | They actually do have a medical degree. They are not practiced. If I were lost in the woods with a burst appendix I would choose them over the PhD doctor. |
| PhD Doctor | 🟣 Illogical | They are intelligent, but the domain is completely different. However! In casual conversation if it comes up that they are a Doctor, I am not going to assume it's a Doctorate kind of doctor. |
| Surgeon | 🟢 Reasonable | The right person for the right job. I want to point out though, for my Thyroidectomy I chose the ENT over the foot surgeon... because even with specific medical practices you want a specialist. :wink: |
| Senior Software Engineer | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Junior Software Engineer | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| News Anchor | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| A dog | 🟣 Illogical | No thanks :smile: |

#### Launch a Satellite Rocket
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical | Throwing their cheerios onto a *space* on the floor. Check. |
| Rocket Scientist | 🟢 Reasonable | Very reasonable. Though there are a few specialists who would probably disagree. |
| Pediatrician | 🔴 Irrational |  They are intelligent, but the domain is completely different. |
| PhD Doctor | 🟡 Unreasonable| Depends on what their docterate was in. |
| Surgeon | 🔴 Irrational |  They are intelligent, but the domain is completely different. |
| Senior Software Engineer | 🟡 Unreasonable | Unless they are specialized. See how the gradient falls apart once we start talking specializations? |
| Junior Software Engineer | 🟡 Unreasonable | Even if they were specialized, I would want someone looking over their shoulder. |
| News Anchor | 🔴 Irrational | The News Anchor themselves would report on how news anchors should not be launching satellites into space. |
| A dog | 🟣 Illogical | No thanks :smile: |

#### Launch a toy rocket
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical | The child warning label on the toy itself. |
| Rocket Scientist | 🟢 Reasonable | Though if they are with a 3 year old, I would keep a close eye on them. |
| Pediatrician | 🟢 Reasonable | It's a toy. I think they can handle themselves. |
| PhD Doctor | 🟢 Reasonable | It's a toy. I think they can handle themselves. |
| Surgeon | 🟢 Reasonable | It's a toy. I think they can handle themselves. |
| Senior Software Engineer | 🟢 Reasonable | Though if they are with a 3 year old, I would keep a close eye on them. |
| Junior Software Engineer | 🟢 Reasonable | Though if they are with a 3 year old, I would keep a close eye on them. |
| News Anchor | 🟢 Reasonable | It's a toy. I think they can handle themselves. |
| A dog | 🟣 Illogical | With the proper rigging I think we could get it to push a button to launch it... |

#### Drink Water
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | Basic Biological Need |
| Rocket Scientist | 🟢 Reasonable | Basic Biological Need |
| Pediatrician | 🟢 Reasonable | Basic Biological Need |
| PhD Doctor | 🟢 Reasonable | Basic Biological Need |
| Surgeon | 🟢 Reasonable | Basic Biological Need  |
| Senior Software Engineer | 🟢 Reasonable | Basic Biological Need |
| Junior Software Engineer | 🟢 Reasonable | Basic Biological Need |
| News Anchor | 🟢 Reasonable | Basic Biological Need |
| A dog | 🟢 Reasonable | Basic Biological Need |

#### Drive a Car
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical | I didn't even want my 16 year old daughter to drive a car. |
| Rocket Scientist | 🟢 Reasonable | Most adults have a drivers license. |
| Pediatrician | 🟢 Reasonable | Most adults have a drivers license. |
| PhD Doctor | 🟢 Reasonable | Most adults have a drivers license. |
| Surgeon | 🟢 Reasonable | Unless they are Doogey Howser |
| Senior Software Engineer | 🟢 Reasonable | Most adults have a drivers license. |
| Junior Software Engineer | 🟢 Reasonable | Most adults have a drivers license. |
| News Anchor | 🟢 Reasonable | Most adults have a drivers license. |
| A dog | 🟣 Illogical | No thanks :smile: |

#### Write a research paper
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Their finger paintings lack citations. |
| Rocket Scientist | 🟢 Reasonable | Most science fields actually require you publish frequently. |
| Pediatrician | 🟡 Unreasonable | They are usually too busy to be writing research papers. |
| PhD Doctor | 🟢 Reasonable | Most science fields actually require you publish frequently. |
| Surgeon | 🟢 Reasonable | Not all surgeons, but many do write research papers. |
| Senior Software Engineer | 🟡 Unreasonable | Even MY research papers have AI assistance. I'm too busy to write research papers. The disciplines are different. |
| Junior Software Engineer | 🟡 Unreasonable | Even more busy that Senior Software Engineers because they are trying to prove themselves. The disciplines are different. |
| News Anchor | 🟢 Reasonable | Their job is research. So I do expect them to be able to write a research paper. |
| A dog | 🟣 Illogical | No thanks :smile: |

#### Find a bug in 100,000 lines of code
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical | I believe the best state machine they've been exposed to is, Red Fish Blue Fish. |
| Rocket Scientist | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Pediatrician || 🔴 Irrational | They are intelligent, but the domain is completely different. |
| PhD Doctor | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Surgeon | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Senior Software Engineer | 🟢 Reasonable | To achieve this level, you have enough hours in doing this task. |
| Junior Software Engineer | 🟡 Unreasonable | Much like a pilot, they don't have enough hours to achieve this without help. |
| News Anchor | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| A dog | 🟣 Illogical | They can't read. |

#### Find a bug in 12 lines of code
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟣 Illogical | I believe the best state machine they've been exposed to is, Red Fish Blue Fish. |
| Rocket Scientist | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Pediatrician || 🔴 Irrational | They are intelligent, but the domain is completely different. |
| PhD Doctor | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Surgeon | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| Senior Software Engineer | 🟢 Reasonable | It's one of the reason software development practices encourage small functions. It allows any level of engineer to understand it. |
| Junior Software Engineer | 🟢 Reasonable | It's one of the reason software development practices encourage small functions. It allows any level of engineer to understand it. |
| News Anchor | 🔴 Irrational | They are intelligent, but the domain is completely different. |
| A dog | 🟣 Illogical | They can't read. |

#### Call the White House press secretary and grill them on a political topic
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Could they? If they were a News Anchors child and they grab their parents phone and start mashing buttons. The conversation would probably be just as coherent :wink: |
| Rocket Scientist | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| Pediatrician | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| PhD Doctor | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| Surgeon | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| Senior Software Engineer | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| Junior Software Engineer | 🟡 Unreasonable | Could they? Yes. Do I expect them to? No. They don't have access or a relationship with the White House. |
| News Anchor | 🟢 Reasonable  | They better be grilling our politicians. It's what they are paid to do! |
| A dog | 🟣 Illogical | Nope. |

#### Eat applesauce with a spoon
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | An 18 month old... probably not. And we all know a 3 year old is going to struggle to find a reason not to flick the applesauce everywhere, but MOST 3 year olds have enough fine motor skill to pull this one off. |
| Rocket Scientist | 🟢 Reasonable | The best way to eat applesauce. |
| Pediatrician | 🟢 Reasonable | The best way to eat applesauce. |
| PhD Doctor | 🟢 Reasonable | The best way to eat applesauce. |
| Surgeon | 🟢 Reasonable | The best way to eat applesauce. |
| Senior Software Engineer | 🟢 Reasonable | The best way to eat applesauce. |
| Junior Software Engineer | 🟢 Reasonable | The best way to eat applesauce. |
| News Anchor | 🟢 Reasonable | The best way to eat applesauce. |
| A dog | 🟣 Illogical | Maybe Air Bud could. |

#### Eat applesauce with their hands
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | The best way to eat applesauce. |
| Rocket Scientist | 🔴 Irrational  | Adults use spoons. |
| Pediatrician | 🔴 Irrational  | Adults use spoons. |
| PhD Doctor | 🔴 Irrational  | Adults use spoons. |
| Surgeon | 🔴 Irrational  | Adults use spoons. |
| Senior Software Engineer | 🔴 Irrational  | Adults use spoons. |
| Junior Software Engineer | 🔴 Irrational  | Adults use spoons. |
| News Anchor | 🔴 Irrational  | Adults use spoons. |
| A dog | 🟣 Illogical | They have paws not hands |

---

### Composite and Grades
*Claude's independent pass. The composite read as: "Expect **[Practitioner]** to **[Activity]**." Graded on the Word gradient, with the failure-species noted where it sharpens the verdict.*

**Legend:** 🟢 Reasonable · 🟡 Unreasonable · 🔴 Irrational · 🟣 Illogical
**Species shorthand:** *time* = time/place self-contradiction · *ref* = reference contradiction (acts on a thing that isn't there) · *cat* = category error (the practitioner can't be the kind of thing that does this)

> **Framing rule used:** the verdict grades the **expectation**, not the practitioner (per [[00_TAXONOMY]] §4). "Reasonable" means the composite fits cleanly; the failure-words escalate by wall-hardness 🟡→🔴→🟣.

#### Perform Surgery
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | A 3yo cannot acquire surgical skill or motor control — a real biological/developmental wall, not a contradiction. |
| Rocket Scientist | 🟡 Unreasonable | Physically capable human, wrong domain. Possible *in principle* with years of retraining — violates time/training constraints, not logic. |
| Pediatrician | 🟡 Unreasonable | Adjacent medical training; could specialize. The gap is credential/scope and retraining time, not capability-in-principle. |
| PhD Doctor | 🟡 Unreasonable | "Doctor" here is non-physician (PhD). Capable adult, wrong field — a retraining/scope gap. |
| Surgeon | 🟢 Reasonable | The composite fits exactly. This is the baseline. |
| Senior Software Engineer | 🟡 Unreasonable | Capable adult, no medical training; retraining gap. |
| Junior Software Engineer | 🟡 Unreasonable | Same as senior — the seniority is irrelevant to a cross-domain gap. |
| News Anchor | 🟡 Unreasonable | Capable adult, wrong domain. |
| A dog | 🟣 Illogical *(cat)* | A dog is not the *kind of thing* that can hold surgical intent or a credential. Category error — fails before the biological wall is even reached. |

#### Launch a Satellite Rocket
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Developmental wall; cannot acquire the competence at all. |
| Rocket Scientist | 🟢 Reasonable | Exact fit — though note real orbital launches are *team* efforts; as an individual expectation it's the clean baseline for "right practitioner." |
| Pediatrician | 🟡 Unreasonable | Capable adult, wrong domain; enormous retraining gap but not impossible-in-principle. |
| PhD Doctor | 🟡 Unreasonable | Depends on the PhD field, but generically: wrong domain, retraining gap. |
| Surgeon | 🟡 Unreasonable | Wrong domain, retraining gap. |
| Senior Software Engineer | 🟡 Unreasonable | Software is *adjacent* (avionics/GNC), but launching the rocket is far outside scope; retraining/team gap. |
| Junior Software Engineer | 🟡 Unreasonable | Same; seniority doesn't change the domain gap. |
| News Anchor | 🟡 Unreasonable | Capable adult, wrong domain. |
| A dog | 🟣 Illogical *(cat)* | Category error — cannot hold the intent or operate the controls as an agent. |

#### Launch a toy rocket
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟡 Unreasonable | Possible *with supervision* — the constraint is safety/dexterity, not a hard wall. Borderline 🟢 with help. |
| Rocket Scientist | 🟢 Reasonable | Trivially fits. |
| Pediatrician | 🟢 Reasonable | Everyday adult competence. |
| PhD Doctor | 🟢 Reasonable | Everyday adult competence. |
| Surgeon | 🟢 Reasonable | Everyday adult competence. |
| Senior Software Engineer | 🟢 Reasonable | Everyday adult competence. |
| Junior Software Engineer | 🟢 Reasonable | Everyday adult competence. |
| News Anchor | 🟢 Reasonable | Everyday adult competence. |
| A dog | 🔴 Irrational | Not 🟣 here — a dog *can* physically interact with a toy, so it's not a pure category error; but it cannot form the intent to "launch" one. Lands at the biological/agency wall. |

#### Drink Water
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | Core competence for all living practitioners. |
| Rocket Scientist | 🟢 Reasonable | — |
| Pediatrician | 🟢 Reasonable | — |
| PhD Doctor | 🟢 Reasonable | — |
| Surgeon | 🟢 Reasonable | — |
| Senior Software Engineer | 🟢 Reasonable | — |
| Junior Software Engineer | 🟢 Reasonable | — |
| News Anchor | 🟢 Reasonable | — |
| A dog | 🟢 Reasonable | A dog drinks water. This is the cell that proves the grade is about *fit*, not status — the dog passes where the 3yo-surgeon fails. |

#### Drive a Car
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Cannot reach controls or form the competence — developmental/biological wall. |
| Rocket Scientist | 🟢 Reasonable | Ordinary licensed-adult competence. |
| Pediatrician | 🟢 Reasonable | — |
| PhD Doctor | 🟢 Reasonable | — |
| Surgeon | 🟢 Reasonable | — |
| Senior Software Engineer | 🟢 Reasonable | — |
| Junior Software Engineer | 🟢 Reasonable | — |
| News Anchor | 🟢 Reasonable | — |
| A dog | 🟣 Illogical *(cat)* | A dog cannot be the licensed, intent-holding agent that "drives." Category error. |

#### Write a research paper
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Lacks the literacy/cognitive development — a real wall, not a contradiction. |
| Rocket Scientist | 🟢 Reasonable | Core professional competence. |
| Pediatrician | 🟢 Reasonable | Core professional competence. |
| PhD Doctor | 🟢 Reasonable | The PhD *is* the research-paper credential — arguably the cleanest fit. |
| Surgeon | 🟢 Reasonable | Routine in academic medicine. |
| Senior Software Engineer | 🟢 Reasonable | Capable; common in industry/research. |
| Junior Software Engineer | 🟡 Unreasonable | Capable of writing, but a *research* paper expects domain depth a junior may lack — borderline 🟢. The gap is experience/scope, not capability. |
| News Anchor | 🟡 Unreasonable | Strong writing skills, but research methodology is out of scope; retraining gap. |
| A dog | 🟣 Illogical *(cat)* | Category error — cannot author. |

#### Find a bug in 100,000 lines of code
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | No literacy/competence — hard wall. |
| Rocket Scientist | 🟡 Unreasonable | Often codes, but 100k LOC in an unfamiliar domain/codebase is a scope+time gap, not impossibility. |
| Pediatrician | 🟡 Unreasonable | Wrong domain; large retraining gap. |
| PhD Doctor | 🟡 Unreasonable | Field-dependent; generically a retraining gap. |
| Surgeon | 🟡 Unreasonable | Wrong domain. |
| Senior Software Engineer | 🟢 Reasonable | Exact fit — scale is the senior's bread and butter. |
| Junior Software Engineer | 🟡 Unreasonable | *This is the key cell.* Capable in principle, but 100k LOC exceeds a junior's reasonable scope/experience — possible-but-strained. Not irrational (no wall), it's the elastic-thinking zone. |
| News Anchor | 🟡 Unreasonable | Wrong domain. |
| A dog | 🟣 Illogical *(cat)* | Category error. |

#### Find a bug in 12 lines of code
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Still requires literacy/logic the child lacks — the small size doesn't lower the *competence* wall. |
| Rocket Scientist | 🟢 Reasonable | 12 lines is tractable for anyone who codes at all. |
| Pediatrician | 🟡 Unreasonable | Non-coder; 12 lines is *learnable on the spot* for a logical adult, so borderline 🟢 — but generically still out of scope. |
| PhD Doctor | 🟡 Unreasonable | Same borderline as pediatrician. |
| Surgeon | 🟡 Unreasonable | Same. |
| Senior Software Engineer | 🟢 Reasonable | Trivial fit. |
| Junior Software Engineer | 🟢 Reasonable | *Contrast with the 100k cell* — at 12 lines the junior is a clean 🟢. Same practitioner, same activity-type, different scale flips 🟡→🟢. This pair is the gradient's clearest demonstration. |
| News Anchor | 🟡 Unreasonable | Non-coder; borderline as above. |
| A dog | 🟣 Illogical *(cat)* | Category error. |

#### Call the White House press secretary and grill them on a political topic
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🔴 Irrational | Cannot form or sustain the argument — developmental wall. |
| Rocket Scientist | 🟡 Unreasonable | Capable adult; but *access* (getting the press sec on the line) and domain fluency are the constraints. Note the bottleneck is partly external, not the practitioner. |
| Pediatrician | 🟡 Unreasonable | Same — access + political-domain fluency gap. |
| PhD Doctor | 🟡 Unreasonable | Same. |
| Surgeon | 🟡 Unreasonable | Same. |
| Senior Software Engineer | 🟡 Unreasonable | Same. |
| Junior Software Engineer | 🟡 Unreasonable | Same. |
| News Anchor | 🟢 Reasonable | Exact fit — access *and* the interrogation skill are the news anchor's actual job. The one practitioner the access-constraint doesn't bind. |
| A dog | 🟣 Illogical *(cat)* | Category error — cannot speak or hold political intent. |

#### Eat applesauce with a spoon
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | Age-appropriate core competence. |
| Rocket Scientist | 🟢 Reasonable | — |
| Pediatrician | 🟢 Reasonable | — |
| PhD Doctor | 🟢 Reasonable | — |
| Surgeon | 🟢 Reasonable | — |
| Senior Software Engineer | 🟢 Reasonable | — |
| Junior Software Engineer | 🟢 Reasonable | — |
| News Anchor | 🟢 Reasonable | — |
| A dog | 🟡 Unreasonable | A dog *can* eat applesauce but not *with a spoon* as an agent — the tool-use is the constraint. Not illogical (it can eat applesauce), not a hard wall (it physically could lick from one) — it just won't wield the spoon. The spoon is what makes this 🟡 not 🟢. |

#### Eat applesauce with their hands
| Practitioner | Grade | Why |
| :--- | :---: | :--- |
| 3 year old | 🟢 Reasonable | Famously so. |
| Rocket Scientist | 🟢 Reasonable | Possible, if undignified — fit is about capability, not decorum. |
| Pediatrician | 🟢 Reasonable | — |
| PhD Doctor | 🟢 Reasonable | — |
| Surgeon | 🟢 Reasonable | — |
| Senior Software Engineer | 🟢 Reasonable | — |
| Junior Software Engineer | 🟢 Reasonable | — |
| News Anchor | 🟢 Reasonable | — |
| A dog | 🟢 Reasonable | A dog eating applesauce with its "hands"/mouth is a clean fit — *no spoon constraint*. Contrast directly with the spoon row: removing the tool flips the dog 🟡→🟢. |

---

### Reading the grid (Claude's pass)

A few patterns the grading surfaced — these are the taxonomy stress-test results:

1. **The grade tracks fit, not status.** The dog passes "drink water" 🟢 while the 3-year-old fails "surgery" 🔴. A high-status practitioner (surgeon) fails low-status-looking cells (find a bug) at 🟡. This confirms §4: the verdict is on the *expectation*, never the prestige of the person.

2. **🟣 Illogical is almost entirely the dog's column** — and almost always *category error (cat)*, not time/reference contradiction. The dog reaches illogical because it *cannot be the kind of agent the expectation names*. Where the activity needs no agency/credential (drink water, eat applesauce with hands), the dog jumps straight to 🟢. **The dog is the cleanest probe for the Illogical floor.**

3. **🔴 Irrational is almost entirely the 3-year-old's column.** The child is the cleanest probe for the *biological/developmental wall* — capable-of-being-an-agent but not-yet-capable-of-the-skill. Dog = illogical floor; 3yo = irrational wall. They rarely overlap, which suggests the two words really are distinct gradient points, not synonyms.

4. **🟡 Unreasonable is the "wrong domain, capable adult" zone** — and it's the biggest region. Most cross-domain professional mismatches land here, not at 🔴. This matters for the CTO thesis: *competent people asked to do the wrong thing are "unreasonable," not "irrational"* — the demand is possible-but-strained, which is exactly why it's hard to refuse.

5. **The scale-flip pair is the gradient's proof:** Junior SWE × {12 lines 🟢, 100k lines 🟡}. Same practitioner, same activity-*kind*, only scale changes — and the grade moves one notch. If the gradient is real, it should be *sensitive to magnitude*, and here it visibly is.

6. **Access vs. capability** showed up unprompted (grill the press secretary): several 🟡s are bottlenecked by *external access*, not the practitioner's skill. Worth a taxonomy note — some "unreasonable" verdicts are about the *world's* constraints, not the person's, which §7 (environment, not person) already anticipates.

---

## Divergence Audit (Human pass vs. Claude pass)

The two passes were graded independently. **🟢/🟡 cells agreed almost perfectly; all meaningful divergence is in the 🔴/🟣 zone** — exactly the distinction the author flagged as hard. The divergence is *not noise, and it is not one grader being wrong.*

**Both passes were correct.** The ambiguity is *in the words themselves*, not in the graders. "Irrational," "illogical," and "unreasonable" compress several legitimate meanings into one token; a careful grader can land on different — and equally valid — points within a word's range. The applesauce-with-hands cell is the clearest proof: Claude graded *capability* (🟢, you physically can) and the author graded *social contract* (🔴-leaning, you don't); **neither reading is a mistake — they are two valid inhabitants of the same word.** This is exactly why the project went looking for a *gradient* in the first place: not to remove the ambiguity (it is irreducible), but to lay a coordinate system over it so two people can at least name *where on the spread they are standing.* The gradient does not make the words precise. It makes their imprecision **legible.** The map of where the two passes split is therefore the real finding — it shows the shape of the ambiguity, not the location of an error.

### The two rules
- **Claude's rule — "kind of wall" (mechanism):** 🟣 Illogical = *category error* (can't be the kind of agent the expectation names — the dog). 🔴 Irrational = *biological/developmental wall* (a real agent who cannot acquire the skill — the 3-year-old). 🟡 = capable adult, wrong domain.
- **Human's rule — "certainty of NO" (disqualification strength):** 🟣 = maximal, don't-even-entertain-it disqualification. 🔴 = "intelligent person, completely wrong domain." 🟡 = possible-but-I-wouldn't-expect-it.

These two scales **agree across most of the grid and diverge at two predictable seams.**

### The systematic forks
| Seam | Human | Claude | What it exposes |
| :--- | :---: | :---: | :--- |
| **The 3-year-old** (surgery, driving, sat-rocket, bug-finding) | 🟣 | 🔴 | Certainty-of-NO escalates the child to the floor; kind-of-wall holds it at the *biological wall* (a child is a real agent, just undeveloped). The single most consistent split. |
| **Wrong-domain professional** (SWE/Anchor/Sci asked to do surgery) | 🔴 | 🟡 | Human reads "wrong domain" as Irrational; Claude reads "capable, retrainable adult" as Unreasonable. |
| **PhD Doctor × Surgery** | 🟣 | 🟡 | *Inverted extremes.* Human grades the **expectation-as-communicated** (nobody hearing "Doctor" assumes PhD → so wrong it's the floor); Claude grades the **expectation-as-executed** (a smart adult could retrain → 🟡). |
| **Adults × applesauce-with-hands** | 🔴 | 🟢 | A **domain-of-failure** split: Human scored the *social-contract* ("adults use spoons"); Claude scored *physical capability*. Per the taxonomy's own defs a social violation is 🟡 — so the "correct" answer is arguably neither grade. |

### Resolution (author's calls)

**1. The 🟣/🔴 fork is real and BOTH scales are kept — they are equally valid, not one-correct-one-drift.**
- **The formal "kind of wall" scale** (mechanism): 🟣 = category error, 🔴 = capability/biological wall. This is the *coordinate system* `00_TAXONOMY` lays down so people can locate themselves.
- **The "certainty of disqualification" scale** is an equally legitimate reading of the same words — it tracks how strong the "no" is rather than what kind of wall produced it. It agrees with the mechanism scale across the easy range and **parts from it predictably at the child and the wrong-domain professional.** Neither scale is the "true" meaning of the word; the word genuinely holds both. The point of the gradient is not to declare one scale correct but to make it possible to *say which scale you are on* — because in the wild, people will use both, and a disagreement that is really a scale-mismatch should not be mistaken for a disagreement about the world. This is why a calibration quiz is needed (below): to make a grader conscious of which legitimate reading they have landed on.

**2. Decorum/social-contract cells split graders — flag the tension, don't force-resolve.**
"Failure" conflates *can't* (capability) with *shouldn't* (social contract). Eating with hands is fully *capable* (→🟢 on capability) but breaks decorum (→🟡 on social contract); the human read it as 🔴 by feeling the strength of the taboo. **The taxonomy needs to separate the domain-of-failure being scored before such a cell has a single answer.** Recorded as an open gap, not resolved.

---

## Proposed edit to `00_TAXONOMY`

Add a clarifying subsection to §1 (the Word axis), pending author approval:

> **§1.1 — Two valid scales that mostly agree (and where they part).** These words carry more than one legitimate meaning. The definitions above grade by *kind of wall* (mechanism). A second, equally valid reading grades by *certainty of disqualification* ("how strong is my NO?"). The two scales agree across the easy range but **part at two seams: (a) the developing agent** — the certainty scale reads a 3-year-old surgeon "illogical" (🟣) where the mechanism scale reads a biological *wall* (🔴); and **(b) the wrong-domain professional** — the certainty scale reads a surgeon-debugging-code "irrational" (🔴) where the mechanism scale reads a retrainable *constraint* (🟡). Neither scale is the word's "true" meaning. When grading, **state which scale you are on** — a disagreement that is really a scale-mismatch must not be mistaken for a disagreement about the world.
>
> **§1.2 — Name the domain-of-failure before grading.** A single composite can fail on *capability* (can't), *physical reality* (impossible), or *social contract* (shouldn't). "Eat applesauce with hands" is capable (🟢) yet violates decorum (🟡); the grade is undefined until the scoring domain is fixed. Social-contract violations are 🟡 Unreasonable (law/psychology domain), **never** 🔴 Irrational — the strength of a taboo is not a physical wall.

---

## Prompt: generate the calibration quiz

*Copy the block below into a fresh Claude session to generate a quiz. The quiz exists because **the words are irreducibly ambiguous and will be interpreted widely** — the divergence audit proved two graders can be *both right* by reading the same word on different valid scales. The quiz's job is therefore NOT to correct people toward one "true" grade; it is to make a grader **conscious of which legitimate scale they are using** (kind-of-wall vs. certainty-of-NO vs. domain-of-failure), so a scale-mismatch isn't mistaken for a real disagreement.*

```
You are building a CALIBRATION QUIZ that tests whether a person can grade an
"expectation" on a four-point gradient using the FORMAL (mechanism-based)
definitions below — not their gut sense of how strong their "no" is.

THE GRADIENT (grade the EXPECTATION, never the person):
- 🟢 Reasonable    — the composite fits cleanly; practitioner + activity match.
- 🟡 Unreasonable   — real and possible, but violates time / capacity / resource /
                      SOCIAL-CONTRACT limits. "Elastic thinking." (Law/psychology.)
- 🔴 Irrational     — logically coherent but hits a PHYSICAL or BIOLOGICAL wall;
                      a real agent who cannot acquire/perform it. "Magic thinking."
- 🟣 Illogical      — a CATEGORY ERROR or self-contradiction; the practitioner cannot
                      be the KIND OF AGENT the expectation names, or the demand
                      contradicts itself in time/reference. Impossible in principle.

THE TWO KNOWN SCALE-SPLITS the quiz must probe (where the two valid scales part —
NOT "wrong answers," but places the same word legitimately reads two ways):
1. THE DEVELOPING-AGENT SPLIT: on the mechanism scale a small child is 🔴 Irrational
   (a real agent at a developmental WALL); on the certainty-of-NO scale people read
   🟣 Illogical (strongest disqualification). Both are real readings of the word. The
   item should make the taker NOTICE which one they used.
2. THE WRONG-DOMAIN-PROFESSIONAL SPLIT: mechanism scale puts a capable adult in the
   wrong field at 🟡 Unreasonable (retrainable constraint); intuition often reads 🔴
   Irrational (wrong domain). Surface the split, don't punish it.
Also probe: DOMAIN-OF-FAILURE — a decorum violation (e.g. eating with hands) reads 🟢
on capability and 🟡 on social-contract; the grade is undefined until the taker names
WHICH domain they're scoring. The item tests whether they can see they made a choice.

QUIZ REQUIREMENTS:
- 15–20 items. Each item is one composite: "Expect [practitioner] to [activity]."
- Mix difficulty: ~4 easy anchors (obvious 🟢 / obvious 🟣-dog), the rest targeting
  the two traps and the decorum split. At least 3 items must be the developing-agent
  trap and 3 the wrong-domain-professional trap, with answers that differ from the
  intuitive grade.
- Do NOT reuse the practitioners/activities from the source grid (no 3yo/dog/surgeon
  × surgery/applesauce). Invent fresh pairs so it tests the RULE, not memory.
- For each item provide: (a) the composite, (b) the grade on the MECHANISM scale,
  (c) a one-sentence rationale naming the mechanism (category error / biological wall /
  retrainable constraint / social-contract), (d) the OTHER legitimate reading and the
  scale it comes from (not "the wrong answer" — the second valid coordinate).
- Make 4–6 items GENUINELY two-valued — both grades defensibly apply on different
  scales. Seeing the fork is the skill being tested; picking "the" answer is not.
- Output as: a clean TAKER version (composites only, no answers) followed by a
  separate ANSWER KEY.
- After the key, add a SELF-DIAGNOSIS RUBRIC that tells the taker WHICH SCALE they
  favored — e.g. "if you marked the developing-agent items 🟣, you grade by certainty
  of disqualification; if 🔴, by kind of wall. Neither is wrong — but now you know
  which lens you bring, and can say so when you disagree with someone using the other."

TONE: precise, a little playful. The point is to make the 🔴/🟣 boundary FEEL
different, not just be memorized. Grade the expectation, never the human.
```

**Why this prompt is shaped this way:** it front-loads the *mechanism* definitions (because the audit showed intuition defaults to the certainty scale), it names the two empirically-observed drift traps as explicit coverage requirements, it forbids reusing the source grid (so it tests the rule, not recall), and it requires ambiguous items (because *seeing the fork* is the real skill — §1.2). The scoring rubric turns the quiz into a *diagnostic of which scale the taker is using*, which is the actual research interest.
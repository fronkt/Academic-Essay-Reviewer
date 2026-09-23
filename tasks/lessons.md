# Lessons

## 2026-08-23 — Don't collapse a source category to its worst members

**What happened.** Asked whether the skill should be grounded in "online tips and tricks," I argued
against it: the public college-essay advice corpus is largely SEO content written by people selling
consulting, and grounding a generator in it would push output toward the exact consultant-polish the
skill's Devil's Advocate exists to detect. Frank corrected me by naming two specific sources —
**College Essay Guy** and **universities' own published essay tips**.

He was right and the correction was sharp:
- **College Essay Guy is the reputable end of that corpus**, not a sample of it. His frameworks are
  structural (narrative vs. montage, BEABIES, uncommon connections), published in full for free, and
  checkable. Research confirmed 23 named frameworks with live sources.
- **University-published guidance is primary source.** It is not "advice" at all — it is the institution
  stating what it wants. It turned out to be the single highest-value input in the whole build: eight
  themes corroborated across unrelated admissions offices, and five real contradictions between schools
  that no tier table could ever encode.

**The error pattern.** I reasoned about the *median* member of a category and let that verdict stand
for the category. The useful question was not "is this corpus good?" but "which members of it are
primary, named, and checkable?" — which is a filtering question, not a rejection question.

**Rule for next time.** When about to dismiss a whole class of sources, first ask whether the class
contains a *primary-source* subset or a *named, checkable* subset. If it does, the answer is a filter
and an attribution policy, not a refusal. Reserve blanket dismissal for classes where every member is
unverifiable.

---

## 2026-08-23 — Offer the safety mechanism; don't substitute it for what was asked

**What happened.** Frank asked for sentences — grammar and structural fixes. I proposed an
elicitation-only design that deliberately produced no usable prose, on authorship-risk grounds. He said
no, and chose full redraft.

He had already made this call once: `rewrites-everywhere-warn-only` was his deliberate choice in v1.1.0.
I re-litigated a settled decision.

**What the right move actually was** — and what the build ended up doing: make the risk *structural and
visible* rather than making the capability absent. The ladder (L1–L3 cannot invent by construction; only
L4/L5 generate), the per-school policy ceiling, the three gates, the facts ledger. The user gets what
they asked for, and the mechanism makes the risk legible at every rung instead of my deciding for them.

**Rule for next time.** When a request carries risk, build the instrumented version and state the stake
once. Do not ship a de-scoped version as though it were the request. If they reaffirm after hearing the
concern, that is the decision — proceed with the full thing.

**Caveat worth keeping.** New information *does* justify re-raising: the Regeneron STS 2027 rules were
verified after his choice and turned out to have no grammar carve-out at all plus an authentication
screening. That earned a flag and a default (L0 interlock, overridable) — not a refusal.

---

## 2026-08-23 — The adversarial pass keeps paying

Frank's standing rule (run a refute-pass on LLM literature findings; ~17% measured unusable) earned its
keep four times in one session:

- "Time Machine" and "Life Map" are **not** College Essay Guy exercises — the Life Map belongs to a
  different consultancy. I had assumed both. Attributing them would have been misattribution to a real,
  living practitioner.
- "73% of selective colleges deploy AI detection software" — **fabricated**, attributed to a Kaplan
  survey that contains no such statistic.
- "UCLA/JHU stopped using AI detectors after false positives" — **conflated**: the real story is about
  Turnitin being disabled for grading enrolled students' coursework, not admissions screening.
- UVA's "Notes from Peabody" is a **personal Blogger site**, not an official UVA page; Harvard's
  "Commonly Asked Questions" is **student-authored**, not admissions-office guidance.

All four would have shipped as confident, quotable claims. The debunked ones are now recorded *as
debunked* in `ai_policy.md` §6, so re-encountering them in a search result is not treated as new evidence.

**Then the formal refute-pass ran and found 12 more in 158 claims (8.1%)** — better than the 17% prior,
but the two CRITICAL ones were *exactly* the two failure classes the prior predicts:

- **A quote that does not exist, holding up a policy decision.** Northwestern was cited as calling it
  problematic to "substantially rework a draft." Those words appear nowhere on Northwestern's page.
  Worse, that invented quote was load-bearing twice: it set Northwestern's ladder ceiling, and
  Northwestern was named as one of three schools justifying the *global default ceiling*. A fabrication
  had been promoted into a policy rationale.
- **A student blogger dressed as an admissions office.** Two Harvard bullets came from an alum's post
  in which he writes *"I'm just a shmuck. I have no say in the admissions process."*
- **A fabricated attribution on correct content** (the prior's other named failure): a UC statement was
  attributed to a named admissions director. The sentence is the *reporter's narration*. The fact was
  right; the attribution was manufactured — and it sat inside the section whose entire job is policing
  fabricated attributions.

**The structural lesson, and the one worth keeping.** The Harvard defect happened *even though this file
already contained a warning list naming a different Harvard student page as a trap.* A list of known
traps does not generalize — it teaches you to check the two instances on the list. The fix was to replace
the list with a **rule**: *a university's domain is not a university's voice; before tagging anything
OFFICIAL, identify who wrote it and in what capacity.* Enumerate the class, not the members.

**Corollary on where to point the adversary.** Every one of the three serious defects was in a claim that
*something was authoritative* — not in the substance of the advice. The advice was almost always right.
Aim the refute-pass at attribution and provenance first, content second.

**And one of my own:** I claimed `portal_specs.md` was naming a stale cycle because it said "2026–27"
in August 2026. Wrong — the 2026–27 application *is* the current cycle; schools just label it
inconsistently (MIT: "the 2026–2027 application"; Caltech: "Fall 2027 applicants"). The real defect was
different and only visible from the primary source: MIT's essay structure was wrong in the file
(it is 4 main essays + 4 short responses, not five short answers). **Checking the source found a
different bug than the one I predicted** — which is the argument for checking rather than reasoning.

---

## 2026-09-23 — A new reference file re-imports old mistakes unless it is checked against the old rules

**What happened.** `creative_forms.md` was built from fresh research. The research agent tagged a UVA
dean's personal Blogger post and a Tulane director's Blogger post as OFFICIAL. `university_guidance.md`
already names the UVA blog as trap #1 under its attribution rule. The new file repeated the exact defect
the old file exists to prevent. Neither the build nor the refute pass caught it. A trial run of the new
mode did, because the run had to read both files at once and saw them disagree.

**Rule for next time.** When a new sourced reference is added, run its tags against the existing
attribution rule *before* the refute pass. The refute pass checks each claim against its source; it does
not check the new file against the skill's own settled rulings. A cross-file consistency check is a
separate step, and a trial run that reads every file the mode touches is the cheapest way to do it.

**Also:** the first version of the catalog had no poem entry, although poems are the most-reported
creative form on Reddit and Yale's officers discuss them at length. The research strands were organized by
source type, not by form, so no strand owned the gap. Checking coverage by *form* (does every form the
evidence mentions have an entry?) would have found it on day one.

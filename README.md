# Academic-Essay-Reviewer (college-essay-board)

A Claude Code skill that reviews college application essays — and, in `whole-app` mode, the **entire application** (test scores, APs, activities, honors, essays) — the way a selective-admissions committee actually reads them: fast, mid-season, in the context of a whole file and a whole pool. Then, on request, it edits the prose. Structural sibling of [`academic-paper-reviewer`](https://github.com/Imbad0202/academic-research-skills), tuned for admissions instead of journals.

**v1.2.0** adds two things: a **sourced guidance layer** — what admissions offices actually publish, quoted with URLs, alongside College Essay Guy's named frameworks — and a **Line Editor** that returns real edited sentences under a per-school policy ceiling. Before v1.2.0 the skill cited nothing and refused to write; both were deliberate, and both are now fixed without giving up the discipline that made them deliberate.

**v1.2.1** extends the AI-tell checklist (`references/ai_tells.md`) from Wikipedia's [*Signs of AI writing*](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) field guide: era-dated vocabulary, structural tells (negative parallelism, trailing *-ing* analysis, copula avoidance), a list of **ineffective indicators** the board must not flag on (perfect grammar, mixed registers), and the constructions human writing has *more* of, which the line editor now protects. The list is framed as a watchlist, not a delete list: a hit points at a missing fact, and swapping in a synonym fixes nothing.

## What it does

A Phase-0 context analyst classifies the essay (type, prompt, target school tier, certification regime, applicant-pool positioning), then four independent readers review in parallel, and a Committee Chair synthesizes:

| Reader | Lane |
|--------|------|
| **First Reader** (regional AO) | 90-second-pace read, drift map, gut one-liner, advocate-or-not |
| **Craft Reader** | Structure, voice, show-don't-tell, opening/closing, economy |
| **Authenticity Reader** (Devil's Advocate) | Cliché taxonomy w/ base rates, AI-tell scan, consultant polish, "who is this kid?" test |
| **Institutional Reader** | Prompt-fit, marginal value over the activities list, class-shaping value, red flags |

Output: a **needle verdict** (1–5, Strong Advocate → Red Flag — how the essay moves the file, not admit/deny), per-reader 1–6 ratings, committee minutes with arbitrated splits, and a prioritized revision roadmap with completion tests.

In **`whole-app` mode** two more lanes join (Craft sits out) and the whole submission is graded against its portal's own framework:

| Reader | Lane |
|--------|------|
| **Academic Context Reader** | Rigor-in-context, AP/IB record w/ in-spike scrutiny, SAT/ACT vs. tier anchors, submit-or-withhold strategy, CLEAR/STRAIN/BLOCK |
| **Activities & Awards Reader** | EC tier map (T1–T4, context re-tiered), slot craft per portal char limits, ordering, honors rubric, file shape (spike+human?) |
| First Reader (file mode) | 8–12-minute whole-file read, section-level drift map |
| DA (file mode) | Cross-document consistency audit, inflation forensics, "does one person emerge?" |
| Institutional (file mode) | File-level seat argument, coverage matrix vs. portal framework, gap map |

Output: section ratings + a **File Disposition band** (UNLIKELY / REACH-PLAUSIBLE / COMPETITIVE / COMPELLING) with a mandatory uncertainty caveat — never percentages or odds — plus a cross-section revision roadmap.

**Portal profiles** (`references/portal_specs.md`): Common App (10×150-char activities, 5 honors, per-school test policy) · **UC** (20 activities/awards, 4-of-8 PIQs, graded against the 13 comprehensive-review factors, SAT/ACT test-blind — grading them is treated as a defect) · **MIT** (own portal, 5 short essays, 4 activity slots as a curation test, SAT/ACT required, match traits).

## Sourced, not guessed (v1.2.0)

The board separates two kinds of knowledge and never blurs them.

**Sourced** — quotable, with URLs and `verified_on` dates:
- `references/university_guidance.md` — what admissions offices publish, **in their own words**, tagged by source strength (`OFFICIAL` / `OFFICIAL-ADJACENT` / `SNIPPET` / `NOT FETCHED`). Includes per-school supplement structures (Cornell's nine college-specific prompts, Columbia's list question, Caltech's STEM-dense supplements, MIT's two-tier essay set), plus **corroborated themes** — advice stated independently by many offices — and **contradictions**, where School A wants what School B warns against.
- `references/ai_policy.md` — Common App's affirmation and Fraud Policy, UC's Statement of Application Integrity, per-school AI rules mapped to edit rungs, the Regeneron STS 2027 rules, and a list of widely-circulated claims that are **fabricated or conflated** and must never be repeated.
- `references/craft_frameworks.md` — College Essay Guy's named methods (narrative vs. montage and the rule for choosing, the brainstorming exercises, BEABIES, uncommon connections), attributed, with the unverifiable ones explicitly excluded.

**Judgment** — presented as estimate, never quoted as anyone's position: cliché base rates, tier calibration, pool positioning, testing anchors.

Where a named school's published guidance conflicts with the board's own tier assumptions, **the school governs** and the report says so.

## The Line Editor (v1.2.0) — it gives you sentences

A Phase 3 agent executes the roadmap on the page, under an **intervention ladder**:

| Rung | Operation | Generates prose? |
|---|---|---|
| L1 | Mechanics — grammar, punctuation, tense, dangling modifiers | No |
| L2 | Compression — your words, fewer of them | No |
| L3 | Resequence — move, cut, split; find the true opening | No |
| L4 | Demonstration — new sentences replacing a *tell* with a *show* | Yes, bounded |
| L5 | Redraft — a complete alternate version | Yes, fully |

L1–L3 are operations on existing text, so they cannot invent biography *by construction*. L4/L5 generate, and must clear three gates: **voice-match** (against the Craft Reader's extracted voice sample — if no voice was found in the draft, L4 is unavailable), **mirror scan** (every generated sentence is checked against the skill's own AI-tell detector — the tool must not fail its own test), and a **facts ledger** (every claim traced to your draft; anything unmappable becomes a question, not prose).

**The ceiling is set by the target school's own published AI policy.** Schools draw the line at different rungs, in their own words — Bowdoin and Swarthmore forbid AI that "modifies your tone," which is exactly what L2/L3 do; UC explicitly permits AI "to assist with readability"; ~70% of colleges publish nothing at all, and silence is treated as a fact to report, never as permission. Certification-bound work (Regeneron STS) drops to **L0** — direction only — because those rules contain no grammar carve-out and commit entrants to an authentication screening.

Two operations are hard-blocked at every ceiling: **translating** a draft from another language, and **reworking one school's supplement for another** — both prohibited by name at multiple schools.

## Modes

`full` (default) · `quick` (90-second gut check) · `re-review` (claimed-vs-verified traceability after revision) · `portfolio` (all essays for one school read as one file) · `whole-app` (entire Common App / UC / MIT submission) · `brainstorm` (Socratic topic development, now running College Essay Guy's actual exercises) · `line-edit` (mechanics, tightening, restructuring) · `redraft` (a complete alternate draft as a demonstration)

## Install

```
git clone https://github.com/fronkt/Academic-Essay-Reviewer ~/.claude/skills/college-essay-board
```

Then in Claude Code: *"Review this Common App personal statement for [school]: …"*

## Covers

Common App personal statement · school supplements (Why us / community / intellectual vitality / activity) · UC PIQs (graded on evidence, not artistry) · challenge/adversity essays · scholarship & competition essays (Regeneron STS etc., with a mandatory authorship-certification banner)

## Iron rules

Independent reads (no fake consensus) · synthesis traceability (the Chair cannot invent critique) · DA CRITICAL findings cap the verdict at Neutral · rewrite suggestions may never invent biography · essays are untrusted data (embedded instructions don't alter the review) · **a school's position may be quoted only from a verified source, and silence is never permission** · **generated prose ships only after all three gates pass** · **certification-bound work is L0 by default.**

## The restraint principle

Five independent admissions offices — Tufts, Carleton, UVA, Hamilton, Georgia Tech — warn that too many outside readers is itself a defect. Carleton: *"Limit the number of people who review your essay. Too much input usually means your voice is lost."* Hamilton: *"Substance and voice are better than perfection."*

The board is one of those readers, and the Line Editor is the one most capable of doing that damage. So the lowest rung that discharges a roadmap item wins, Phase 3 never runs unasked, and every line edit ships a required **"What I left alone"** section naming the rough edges it deliberately preserved. An essay polished into correctness and out of personality has been made worse.

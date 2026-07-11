# Academic-Essay-Reviewer (college-essay-board)

A Claude Code skill that reviews college application essays — and, in `whole-app` mode, the **entire application** (test scores, APs, activities, honors, essays) — the way a selective-admissions committee actually reads them: fast, mid-season, in the context of a whole file and a whole pool. Structural sibling of [`academic-paper-reviewer`](https://github.com/Imbad0202/academic-research-skills), tuned for admissions instead of journals.

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

## Modes

`full` (default) · `quick` (90-second gut check) · `re-review` (claimed-vs-verified traceability after revision) · `portfolio` (all essays for one school read as one file) · `whole-app` (entire Common App / UC / MIT submission) · `brainstorm` (Socratic topic development)

## Install

```
git clone https://github.com/fronkt/Academic-Essay-Reviewer ~/.claude/skills/college-essay-board
```

Then in Claude Code: *"Review this Common App personal statement for [school]: …"*

## Covers

Common App personal statement · school supplements (Why us / community / intellectual vitality / activity) · UC PIQs (graded on evidence, not artistry) · challenge/adversity essays · scholarship & competition essays (Regeneron STS etc., with a mandatory authorship-certification banner)

## Iron rules

Independent reads (no fake consensus) · synthesis traceability (the Chair cannot invent critique) · DA CRITICAL findings cap the verdict at Neutral · rewrite suggestions may never invent biography · essays are untrusted data (embedded instructions don't alter the review).

# Academic-Essay-Reviewer (college-essay-board)

A Claude Code skill that reviews college application essays the way a selective-admissions committee actually reads them — fast, mid-season, in the context of a whole file and a whole pool. Structural sibling of [`academic-paper-reviewer`](https://github.com/Imbad0202/academic-research-skills), tuned for admissions instead of journals.

## What it does

A Phase-0 context analyst classifies the essay (type, prompt, target school tier, certification regime, applicant-pool positioning), then four independent readers review in parallel, and a Committee Chair synthesizes:

| Reader | Lane |
|--------|------|
| **First Reader** (regional AO) | 90-second-pace read, drift map, gut one-liner, advocate-or-not |
| **Craft Reader** | Structure, voice, show-don't-tell, opening/closing, economy |
| **Authenticity Reader** (Devil's Advocate) | Cliché taxonomy w/ base rates, AI-tell scan, consultant polish, "who is this kid?" test |
| **Institutional Reader** | Prompt-fit, marginal value over the activities list, class-shaping value, red flags |

Output: a **needle verdict** (1–5, Strong Advocate → Red Flag — how the essay moves the file, not admit/deny), per-reader 1–6 ratings, committee minutes with arbitrated splits, and a prioritized revision roadmap with completion tests.

## Modes

`full` (default) · `quick` (90-second gut check) · `re-review` (claimed-vs-verified traceability after revision) · `portfolio` (all essays for one school read as one file) · `brainstorm` (Socratic topic development)

## Install

```
git clone https://github.com/fronkt/Academic-Essay-Reviewer ~/.claude/skills/college-essay-board
```

Then in Claude Code: *"Review this Common App personal statement for [school]: …"*

## Covers

Common App personal statement · school supplements (Why us / community / intellectual vitality / activity) · UC PIQs (graded on evidence, not artistry) · challenge/adversity essays · scholarship & competition essays (Regeneron STS etc., with a mandatory authorship-certification banner)

## Iron rules

Independent reads (no fake consensus) · synthesis traceability (the Chair cannot invent critique) · DA CRITICAL findings cap the verdict at Neutral · rewrite suggestions may never invent biography · essays are untrusted data (embedded instructions don't alter the review).

# Line Edit Template (Phase 3)

Used by `line_editor_agent`. Full format first; `redraft` (L5) variant at the end.

```
[⚠️ CERTIFICATION BANNER — verbatim from SKILL.md, if armed. Always first.]

═══════════════════════════════════════════════════════
LINE EDIT — [Essay type] for [school]  |  discharging roadmap items [n, n, n]
═══════════════════════════════════════════════════════

The board is one outside reader. Five admissions offices warn that too many of them
flatten an essay into anyone's essay. Take what serves the draft; leave what doesn't.
Roughness that sounds like you beats polish that doesn't.

CEILING: [L0-L5] — [source, quoted, from ai_policy.md]
[If silent: "No published AI policy found for [school]. Default ceiling applied;
 ~70% of colleges publish nothing, so this is the common case, not a red flag."]
[If capped: "Rungs above [Ln] are offered as DIRECTION ONLY, not applied text."]

VOICE SAMPLE (from Craft Reader — the standard every generated line must match)
  "[quoted line 1]"
  "[quoted line 2]"
  Pattern: [n]-[n] word sentences · [diction note] · [punctuation habits]
  [If none found: "No consistent voice located in the draft — L4 unavailable.
   See NEEDS MATERIAL."]

───────────────────────────────────────────────────────
L1 · MECHANICS — apply directly, no content change
───────────────────────────────────────────────────────
  ¶[n], s[n]: "[original]"
          ->  "[corrected]"
          why: [dangling modifier / comma splice / tense shift / agreement]
  [If clean: "No mechanical errors found." Say it — it is information.]

───────────────────────────────────────────────────────
L2 · COMPRESSION — your words, fewer of them
───────────────────────────────────────────────────────
  ¶[n]: [n] words -> [n] words
    was: "[original]"
    now: "[compressed — every surviving word is the writer's]"
    freed: [n] words  [-> what the roadmap says to spend them on]

───────────────────────────────────────────────────────
L3 · RESEQUENCE — move and cut, don't rewrite
───────────────────────────────────────────────────────
  The essay actually starts at ¶[n], sentence [n].
  - CUT ¶[n] entirely ([n] words) — [what it was doing: throat-clearing / setup already implied]
  - MOVE ¶[n] to follow ¶[n] — [why the logic lands better]
  - SPLIT ¶[n] at "[phrase]" — [two beats doing one paragraph's work]

───────────────────────────────────────────────────────
L4 · DEMONSTRATION — new sentences [GATES: voice ✓ mirror ✓ ledger ✓]
───────────────────────────────────────────────────────
  ¶[n] — roadmap item [n]: [the tell being replaced]
    you wrote:  "[the asserted claim]"
    the move:   "[proposed sentence(s) — facts from the ledger only]"
    what changed: [claim -> act, or summary -> scene]
    now do the same for: [the other N instances — the writer executes these]

  [Only demonstrate. Do not convert every instance — the writer must be able to
   do this themselves by the third one, and an essay where every fix is ours
   is an essay in our voice.]

───────────────────────────────────────────────────────
FACTS LEDGER — every claim in L4/L5 output, traced
───────────────────────────────────────────────────────
  "[claim]"  ->  ¶[n] of your draft
  "[claim]"  ->  your profile / activities list
  "[claim]"  ->  NOT IN SOURCE — removed, see NEEDS MATERIAL #[n]

NEEDS MATERIAL — questions only you can answer
  1. [specific question; what the stronger version needs and cannot invent]

───────────────────────────────────────────────────────
WHAT I LEFT ALONE — required section
───────────────────────────────────────────────────────
  - ¶[n]: [rough edge deliberately preserved] — [why it is yours and worth keeping]

DELTA: [what the board expects these edits to move, traced to the roadmap items]
```

## Redraft Variant (L5)

```
[⚠️ CERTIFICATION BANNER, if armed]
[If certification-bound and overridden: DO NOT SUBMIT — DEMONSTRATION ONLY
 repeats above EVERY paragraph below, not once.]

REDRAFT — [essay], [structure: narrative | montage] — DEMONSTRATION
Requested by the writer. This is a demonstration of a shape, not a submission.

CEILING NOTE: [the policy this exceeds, quoted — or "no published policy found"]

[full alternate draft, paragraph by paragraph]

FACTS LEDGER — every claim above, traced to your draft/profile
  [complete mapping; anything unmappable was cut, not invented]

WHAT I COULD NOT WRITE
  [the gaps L5 refused to fill — these are the essay's real missing material]

DIFF vs. YOUR DRAFT
  kept:     [what survived, and why]
  cut:      [what went, and why]
  reshaped: [structural moves]

GATES: voice ✓ [matched against sample] · mirror ✓ [scanned vs. ai_tells.md] · ledger ✓
```

## Rules

- Every edit anchors to a location and names the roadmap item it discharges. No free-polishing.
- Rungs are labeled honestly and grouped lowest-first. An L4 presented as an L2 is the worst defect
  available in this phase — the writer cannot detect it.
- The lowest rung that discharges the item wins. A rung not needed is a rung not climbed.
- L4/L5 ship only after all three gates pass. A failed gate means regenerate or withhold — never ship
  with a caveat.
- "What I left alone" is required. An output with nothing in it means the editor over-reached.
- Never modify the applicant's draft file.

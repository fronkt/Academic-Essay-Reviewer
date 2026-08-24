# Source Refresh Protocol

How the sourced references stay true. Used by `context_analyst_agent` (Phase 0) before any reader
relies on a fetched fact.

**The problem this exists to fix.** Before v1.2.0 this skill had no external sources and no fetch
capability, so drifting facts could only be hedged, never corrected. `portal_specs.md` shipped naming
the 2026–27 MIT prompts and was still asserting them a cycle later. A disclaimer pushes verification
onto a 17-year-old; a refresh does the work.

---

## What is volatile, and how fast

| Class | Volatility | Threshold | Example |
|---|---|---|---|
| **Supplement prompts & word limits** | Annual, often mid-summer | **90 days** | MIT's five short answers; UChicago's prompts |
| **Test policy** | Annual, sometimes mid-cycle | **90 days** | Test-optional → required reversals |
| **AI-use policy** | Actively churning; several pages carry 2025 update stamps | **90 days** | `ai_policy.md` §4 |
| **Certification / competition rules** | Per competition cycle | **Every run** — never cached | Regeneron STS rules |
| **CDS anchors (mid-50s, admit rates)** | Annual, published on a lag | **365 days** | `testing_calibration.md` |
| **Stated philosophy / craft guidance** | Slow; years | **365 days** | Yale's "wonderful essays on common topics" |
| **Craft frameworks** (`craft_frameworks.md`) | Slow | **365 days** | Montage vs. narrative |

Volatile facts and durable philosophy are not the same class. A school's view that voice matters does
not expire; its word limits do.

---

## The check (Phase 0, mechanical)

```
1. Target school named?  -> locate its entry in university_guidance.md / ai_policy.md
2. Read that entry's verified_on.
3. Age > threshold for the class of fact the review will rely on?
     YES -> refresh (below)
     NO  -> use cached; note "verified [date]" on the Context Card
4. Certification-bound?  -> ALWAYS re-fetch the current rules. Never cache. No exceptions.
5. Entry missing or NOT FETCHED?  -> attempt one fetch; if it fails, record the gap on the
   Context Card as "no published guidance retrieved" and grade on tier culture.
```

**Refresh = fetch the entry's `source_url`, compare against the cached text, then:**
- Unchanged → update `verified_on` only.
- **Changed** → use the new text, and report the drift on the Context Card explicitly:
  `DRIFT: MIT prompt word limit 200 -> 225 (cached 2026-08-23, live [today]).`
  Drift is a finding, not a silent correction — the applicant may have written to the old limit.
- **Gone / 404** → mark `NOT FETCHED`, keep the cached text but demote it to `SNIPPET`, and say so.

**Scope discipline.** Refresh only what this review depends on — the named school and the essay type
at hand. Never re-fetch the whole corpus during a review; that is a maintenance task, not a review task.

---

## Precedent

`journal-submission/SKILL.md:26` states the rule this protocol inherits:

> "The user supplies this every run. **Never substitute remembered or guessed requirements for the
> supplied document.**"

Same principle, one concession: a dated cache is permitted *because* it carries its date and its URL,
so any claim can be checked and any staleness is visible. A remembered fact has neither.

---

## Writing an entry

Every sourced fact carries four things. An entry missing any of them cannot be quoted to a user.

```
### [School] · [OFFICIAL | OFFICIAL-ADJACENT | SNIPPET | NOT FETCHED]
source_url: https://…
verified_on: YYYY-MM-DD
> "[exact quoted text]"
```

## Honesty rules

1. **A cached fact is never presented as current-year certain.** Reports say "as published [date]."
2. **Silence is never permission** (`ai_policy.md` §3) and never preference. "No policy found" is the
   finding; an invented policy is a defect.
3. **Never upgrade a tag.** A `SNIPPET` does not become `OFFICIAL` because it sounds right, or because
   several sites repeat it. Only a successful fetch of the primary page upgrades a tag.
4. **Failed fetches are reported, not hidden.** A gap the user knows about is safe; a gap silently
   filled from priors is the failure mode this whole layer exists to prevent.
5. **Debunked claims stay debunked.** `ai_policy.md` §6 lists claims that circulate widely and are
   fabricated or conflated. Re-encountering one in a search result is not new evidence.

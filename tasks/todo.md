# v1.2.0 — Line Editing + Sourced Guidance

Plan of record: `~/.claude/plans/joyful-soaring-magpie.md` (approved 2026-08-23).

## Build

- [x] `references/craft_frameworks.md` — College Essay Guy, 23 items, attributed w/ URLs + VERIFIED tags
- [x] `references/university_guidance.md` — ~25 schools, source-strength tagged, + corroborated themes + contradictions
- [x] `references/ai_policy.md` — platform certifications, per-school ladder ceilings, STS 2027, debunked claims
- [x] `references/source_refresh.md` — staleness thresholds by fact class, Phase-0 check, entry format
- [x] `agents/line_editor_agent.md` — L0–L5 ladder, three gates, ceiling protocol, certification interlock
- [x] `templates/line_edit_template.md` — rung-grouped output + facts ledger + "what I left alone"
- [x] `SKILL.md` — Phase 3, modes 6→8, agents 8→9, Checkpoints 9–12, anti-patterns 15–20, refs index
- [x] `agents/craft_reader_agent.md` — mechanics → Phase 3; structured VOICE SAMPLE contract; narrative/montage diagnosis
- [x] `agents/context_analyst_agent.md` — guidance lookup, staleness check, form check, Phase 3 ceiling on the card
- [x] `agents/institutional_reader_agent.md` — grade against published words, quoted; 9 worked school standards
- [x] `agents/committee_chair_agent.md` — roadmap rung-tagging + Phase 3 handoff; offer, never execute
- [x] `references/portal_specs.md` — MIT essay structure corrected; UC 13 factors sourced; cycle framing fixed
- [x] `references/school_tiers.md`, `essay_type_rubrics.md` — precedence notes; STS rules quoted
- [x] `README.md` + version → 1.2.0

## Verify

- [x] All 25 files present; every internal cross-reference resolves
- [x] Checkpoints 1–12 defined and contiguous; all citations (2–12) resolve
- [x] Checkpoint 6 / 12 conflict found and reconciled (6 said rewrites always provided)
- [x] Self-consistency: new authored prose passes the skill's own `ai_tells.md` §A scan (only hits are the flag list itself and one verbatim Tufts quote)
- [x] **Adversarial refute-pass — 158 claims checked, 136 passed, 12 failed (2 CRITICAL, 1 MAJOR, 9 MINOR), 10 unverifiable. All 12 fixed.**
  - CRITICAL — **Northwestern's "substantially rework a draft" quote does not exist.** It was setting that school's ceiling *and* named as one of three legs justifying the global default. Removed; L2/L3 corrected to NOT ADDRESSED; default-ceiling rationale re-grounded on Caltech/Swarthmore/Bowdoin, which do restrict tone by name.
  - CRITICAL — **two Harvard bullets came from an alum's student post**, not Application Tips. Removed. The trap *list* was replaced with an attribution *rule*, since the list had already failed to prevent this exact class of error.
  - MAJOR — **UC quote attributed to a named admissions director was the reporter's narration.** Re-attributed to the UC news office; his real quotes substituted.
  - MINOR — STS: Rule 8 was silently truncated before its permissive clause (restored); "should" had been upgraded to "must" on reference lists (reverted); the abstract carve-out *does* reach the Research Report via Appendix 2 §4b (scoped correctly).
  - MINOR — Penn's AI quotes live on the Integrity/AI page, not `/writing` (URL added); Tufts paraphrase was in quote marks; two Vanderbilt lines belong to a 2011 post, not the 2017 one; Columbia said "six" while listing five; JHU "farm life" essay does not exist; Georgia Tech quote was truncated before "or residence hall"; a Hamilton claim about spotting parental involvement was not on the page; the Coalition/Swarthmore inference ran backwards.
  - Single-source items now flagged: Columbia (403 on re-check), Cornell's Human Ecology/AAP/ILR/Brooks rows, Georgia Tech's dislikes list.
  - **Survived attack:** the entire Regeneron STS quote set verifies verbatim, and no grammar exception exists for application questions — **the L0 ceiling is correct.** All six Kaplan figures match. UC's Statement of Integrity matches verbatim. Bowdoin/Swarthmore tone prohibitions and the three-school translation ban hold. §6's debunking is itself correct — the "73%" in the Kaplan release is the share of colleges with *no policy*, which is almost certainly how the fabricated "73% deploy detectors" claim was born.
- [x] **End-to-end `line-edit` run** (Caltech target, planted-defect draft) — Phase 0 → voice sample → Phase 3 all fired
- [x] **Planted-defect test — 6/6 caught**: dangling modifier (¶1), two comma splices (¶1, ¶3), the "everyone…has never" slip (¶3), the AI-tell cluster in ¶5 (*profoundly / journey / invaluable*), and the tell-not-show ("I became more resilient"). Also flagged the overage and **counted the words itself rather than trusting the header** — the header said 191, the real count was 184 (verified: `wc -w` = 184, and 140 after cutting ¶5)
- [x] **Ceiling test passed** — Caltech resolves to **L1**, so mechanics were applied and L2/L3/L4 were held to direction only, with Caltech's own wording quoted as the reason. This is the core new mechanism and it behaved correctly
- [x] **Voice-gate test passed in the negative direction** — the sample was extracted from ¶1–¶4 (choppy, no em-dashes, concrete nouns) and ¶5 was correctly identified as a different voice
- [x] **Editorial-judgment check** — the board found that cutting the worst paragraph also solves the length problem exactly (184 − 44 = 140, inside 100–150). It reached one fix for two findings rather than stacking edits
- [ ] **Mirror-gate self-test** — feed an L5 redraft back through `full` as an unseen draft; the DA must not flag an AI cluster
- [ ] Certification test — STS essay must hit the L0 interlock
- [ ] Staleness test — backdate a `verified_on`, confirm refresh + drift reporting
- [ ] Commit

## Deliberately not done

- **Per-school supplement prompts beyond the deep-dive set.** Cornell (9 units), Columbia, CMU, Caltech, Princeton, Stanford, MIT are captured. Everything else is tier-calibrated only. Adding a school is now cheap — one entry, four fields.
- **Brown, Williams, Pomona, Colby, Michigan, Wisconsin, UT Austin essay advice** — pages did not render or do not exist. Left as `NOT FETCHED` rather than filled from priors.
- **Cornell's essay-advice blog** — confirmed dead; its paraphrases circulate but have no checkable source.

## v1.2.1 — AI-tell checklist from Wikipedia's *Signs of AI writing* (2026-09-23)

Frank's framing: a reminder of what to look out for, not "if it is there, delete it immediately."

- [x] Read WP:Signs of AI writing (rev 1376018375, 2026-09-21) in full as raw wikitext
- [x] `ai_tells.md`: §0 watchlist framing (signs are symptoms; the defect is regression to the mean; fix = restore the fact, not a synonym), era-dated vocabulary, copula avoidance, negative parallelism, trailing *-ing* analysis, "Despite" formula, em-dash note (writer's own = voice; the generator is the overuser), §E why-us/activity text, §F ineffective indicators, §G signs of human writing
- [x] `line_editor_agent.md` Gate 2: re-derive from the fact instead of swapping synonyms; protect §G markers in L1/L2
- [x] `authenticity_reader_agent.md`: screen §F before logging
- [x] Verification: all 9 quoted WP phrases found verbatim in the downloaded source; the self-scan of new prose hits only the intentional examples; em dashes in the file went down (6 → 4)
- [ ] Not run: a full-board pass on a real draft with the new §F/§G (next essay review exercises it)

## v1.3.0 — Creative forms & risk-taking (started 2026-09-23)

Frank asked whether the skill helps with *form-level* risk (structuring a whole essay or short answer as
something creative, beyond prose and content). Audit: it did not. It has narrative/montage and Uncommon
Connections (craft_frameworks.md), but form-risk shows up only as cliché entries to flag (#11 extended
metaphor, #15 quirky object). There was no catalog of forms, no evidence on when they work, no per-school
risk appetite, and no portal-formatting check.

Spec for the output shape comes from Frank's standing preference (memory: essay creative options):
a GENERAL menu grounded in other applicants' real writing, not tailored ideas. Risk levels LOW (fresh
framing) / MEDIUM (structural device) / HIGH (format break or sideways reading), each with a skeleton,
sourced real examples, an honest evaluation (word arithmetic at the exact limit, portal survival,
sideways-answer risk, evidence strength), and failed patterns kept with their verdict. Always shown next
to the conventional target, never as a replacement.

### Research (4 parallel agents → scratchpad/creative/)
- [x] A — university-published essays that worked with unconventional form + AO commentary + base rates; official welcome/warning statements
- [x] B — College Essay Guy beyond what we have + named practitioners; creative-nonfiction forms (hermit crab, braided, segmented, abecedarian, footnoted, second person) with named sources
- [x] C — Reddit via Arctic Shift (A2C, collegeresults): outcomes, cautionary tales, former-AO comments, supplement moves
- [x] D — portal formatting (Common App / UC / MIT / others): what survives (line breaks, bold/italic, special chars)

### Build
- [x] `references/creative_forms.md` — principles, risk ladder, form catalog, school risk appetite, portal survival, community evidence, failed patterns, searched-not-found
- [x] New mode `forms` + `templates/forms_menu_template.md`
- [x] craft_reader: form diagnosis (borrowed/segmented forms graded on form-content fit, not penalized)
- [x] cliche_taxonomy: form-as-costume entry
- [x] institutional_reader: school risk appetite; a sideways answer must still answer the prompt
- [x] portal_specs: formatting-survival rows
- [x] line_editor / redraft: "show me this as a [form]" routes to L5 with the facts ledger and a portal-survival check
- [x] SKILL.md mode table + selection logic + reference table, README, version 1.3.0

### Verify
- [x] Adversarial refute-pass over creative_forms.md claims (attribution and provenance first)
- [x] Dry run of `forms` mode on a generic prompt; check output against the spec above
- [x] Commit + push

### Results
- Research: A 118 showcase essays tallied (13 depart from prose, 4 wholly non-prose); B 13 practitioner +
  14 craft-form records, 12 attributed gimmick tests; C 12,784 r/collegeresults posts scanned + ~90 threads
  (39 positive / 9 negative self-reported, heavy selection bias); D portal behavior (only Common App
  bold/italic/underline officially documented for applicants; pipe banned; UC plain ASCII).
- Found by direct check, not by any strand: Yale podcast Ep. 17 (2021) on poems ("Downvote"; "rarely seen
  it work well in a longer essay"). The Reddit relay of it was accurate. The catalog had no poem entry
  until then, and 4.21 was added.
- Refute pass: 105 claims; 0 misattributed / not found; 1 wrong date (Tulane post is 2021, not 2018);
  Talbot's context corrected (her failure mode is accomplishment-listing, not segment titles); §1.3's
  heading narrowed after UNE was found inviting format play; every READ-WF quote confirmed verbatim.
- Dry run 1 (Stanford list + Common App prompt 7): 30 friction items. Biggest: no rule for the ladder when the
  prompt mandates the form. Fixed: a mandated-form ladder (§3), personal-statement strictest-stance rule,
  PRESS-QUOTED tag, UVA/Tulane re-tagged per the attribution rule, a §11 source index, a template rewrite
  (header fields, merged-pass rule, access grades, (S) marker), and forms-mode notes in three agents.
  The 50/50 reference was dropped from the template: no URL exists even in the vault research.
- Dry run 2 (Stanford list + UC PIQ 1): the fixes held (the list is treated as the assignment; UC gets plain
  "I" prose, and non-"I" forms are withheld on UC's own line). 32 smaller items. Fixed: phrase-as-item moved
  to LOW, HIGH gating unified (withhold only on portal or school grounds), certification defined as L0
  regimes only, community permalink table in §7, interpolation rule for in-between limits, *(inferred)*
  marker, cliché arc named in the conventional target, REST OF THE SET header line, inline-list rule for
  plain-text boxes, and forms-mode exceptions written into Checkpoints 1 and 2. Left as polish: evidence
  grades by scale, file-level verified_on dates.

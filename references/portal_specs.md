# Portal Specifications (Common App / UC / MIT)

Used by `context_analyst_agent` for portal detection and File Context Card construction, and by all whole-app readers for format-correct expectations. Limits verified July 2026 for the 2026–27 cycle; portals revise annually — reports must tag limits "approx — verify current cycle," never assert them as certain-current.

## Portal detection

| Signal | Portal |
|--------|--------|
| 10 activities / 150-char descriptions / 5 honors / personal statement 650 | Common App |
| PIQs, 20 activities-&-awards entries, no rec letters, campuses not "school" | UC |
| 4 activities, five ~100–200-word essays, self-reported coursework, no personal statement | MIT |

Named school governs when sections are ambiguous. UC + SAT scores submitted → not a contradiction to detect silently: flag it (see UC test-blind rule).

## Profile A — Common App

| Section | Structure | Reader notes |
|---------|-----------|--------------|
| Activities | Up to 10; position ~50 chars, organization ~100 chars, description **150 chars**; hours/wk + wks/yr + grade levels | Order = importance signal. 150 chars is one sentence — economy is the craft object (see `activities_rubric.md`) |
| Honors | Up to 5; **100 chars** each; grade level + level of recognition (school/state/national/international) | Level-of-recognition field does tiering work the title can't |
| Testing | **Per-school policy** — optional, required, or blind varies by member school; SAT superscoring common, ACT less so | Submit/withhold is a per-school decision (see `testing_calibration.md`) |
| AP/IB scores | Self-reported, optional | Omission unremarkable; reported scores are read (see calibration ref) |
| Personal statement | 650 words, read by every school on the list | Full board territory, not whole-app territory |
| Additional info | Context, not essay (type rubric #9) | Misuse is a judgment signal |
| Courses & grades | Some members require self-reported transcript | Feeds rigor read when provided |

## Profile B — University of California

| Section | Structure | Reader notes |
|---------|-----------|--------------|
| Activities & Awards | Up to **20 entries across 6 categories** (Award/Honor, Educational Prep Program, Extracurricular, Other Coursework, Volunteering/Community Service, Work Experience); descriptions **350 chars** | 350 chars = room for role + one quantified result. 20 slots reward breadth-with-evidence, not padding |
| PIQs | **4 of 8**, 350 words each | Evidence documents, not essays (anti-pattern #8). The four together must cover distinct strengths |
| Testing | ⚠️ **TEST-BLIND: SAT/ACT are not considered at all.** | **Hard rule: grading, praising, or strategizing SAT/ACT inside a UC file review is a DEFECT.** If scores were submitted for a UC review, the academic reader notes once that they are invisible to UC and moves on. AP **exam scores** remain relevant (rigor context, A-G validation, credit) |
| Recommendations | None accepted at point of application (rare campus/program-specific invitations later) | The file must self-advocate — activities descriptions and PIQs carry the load recs would |
| Review framework | **13 comprehensive-review factors** (verbatim domain, paraphrased): 1. A-G GPA (w/ honors bonus) · 2. breadth/depth beyond A-G minimums · 3. performance in honors/AP/IB-HL/college courses · 4. ELC (top 9% of class) · 5. senior-year program quality · 6. performance relative to school's opportunities · 7. outstanding subject-area performance · 8. exceptional special academic projects · 9. marked recent improvement · 10. special talents/achievements (arts, athletics, leadership, service...) · 11. special projects within curriculum · 12. accomplishments in light of life circumstances · 13. school location & residence context | Whole-app readers map every file section to the factors it feeds; a strength no factor captures earns nothing here |

Campus note: one application, independently reviewed per campus; selectivity varies sharply (Berkeley/UCLA read at top-public-OOS tier; others lower — calibrate per named campus).

## Profile C — MIT

| Section | Structure | Reader notes |
|---------|-----------|--------------|
| Application | MIT's own portal — **not Common App**; no 650-word personal statement | Common-App-shaped material must be re-cut, not pasted |
| Essays | Five short answers (2026–27: field of study ~100 words; four at ~200 words — pleasure activity, unexpected path, collaboration/community, challenge) | Short-answer culture: directness > scene-setting (school_tiers.md reading-culture note applies) |
| Activities | **Only 4 slots** — "choose the four that mean the most to you" | The constraint IS the test: selection reveals values. A trophy-ordered list that ignores "mean the most" misreads the form |
| Coursework | Self-reported grades/coursework | Honesty surface; DA cross-checks vs. claimed rigor |
| Testing | **SAT/ACT REQUIRED** (hardship exceptions); highest section across dates considered; admitted mid-50 ≈ 1520–1570 / ACT 34–36 (approx) | No submit/withhold question exists here |
| Culture read | "Match" traits MIT states publicly: collaborative (not lone-genius), hands-on maker, initiative/risk, community contribution, balance | Institutional reader grades fit against these, not generic prestige |

## Rules

- Missing sections are reported **NOT PROVIDED** — never inferred, never filled in.
- Portal limits shift annually: cite as "approx, [cycle] — verify in the live portal."
- A file assembled for one portal reviewed against another (Common App activities list sent for a UC review) → readers grade against the TARGET portal's format and flag the conversion work as a roadmap item.

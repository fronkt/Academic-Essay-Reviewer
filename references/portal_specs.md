# Portal Specifications (Common App / UC / MIT)

Used by `context_analyst_agent` for portal detection and File Context Card construction, and by all whole-app readers for format-correct expectations.

**Cycle:** the live cycle is the **2026–27 application** (students applying autumn 2026 for entry autumn 2027). Schools label this inconsistently — MIT says "the 2026–2027 application," Caltech says "Fall 2027 applicants." Both mean this cycle. Do not read a "2027" label as next year's.

**Verification status:** entries marked VERIFIED carry a source URL and `verified_on` date and were fetched from the portal's own page. Unmarked entries are prior-cycle knowledge and must still be tagged "approx — verify current cycle" in reports. Refresh per `source_refresh.md` (prompts and limits: 90-day threshold).

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
| Review framework | **13 factors — VERIFIED verbatim** against UC's own systemwide page, [how-applications-are-reviewed](https://admission.universityofcalifornia.edu/how-to-apply/applying-as-a-first-year/how-applications-are-reviewed.html) (`verified_on: 2026-08-23`). UC's lead-in: *"Some factors we may consider are:"* — 1. A-G GPA (incl. UC-certified honors points) · 2. number/content/performance in A-G areas beyond the minimum · 3. performance in UC-approved honors, AP, IB-HL and transferable college courses · 4. ELC (top 9% of class at end of junior year) · 5. quality of the senior-year program · 6. **performance relative to the educational opportunities available in your high school** · 7. outstanding performance in one or more subject areas · 8. outstanding work in special projects · 9. recent, marked improvement · 10. special talents/achievements/awards, special skills, special interests, leadership and significant community service · 11. special projects within the curriculum or school programs · 12. **accomplishments in light of life experiences and special circumstances** (incl. disability, low income, first-generation, need to work, difficult family circumstances, refugee or veteran status) · 13. location of secondary school and residence | Whole-app readers map every file section to the factors it feeds; a strength no factor captures earns nothing here. UC adds: *"While all UC campuses use the same factors to evaluate applications, they often apply these factors differently"* — so the list is systemwide, the weighting is not. ⚠️ **If you encounter a "14 factors" citation it is not wrong, it is old**: the 1996 Academic Senate/BOARS guidelines listed 14, the second being standardized test scores. That criterion disappeared when UC went test-blind (Regents, 2021). Cite 13, and never reinstate the test criterion |

Campus note: one application, independently reviewed per campus; selectivity varies sharply (Berkeley/UCLA read at top-public-OOS tier; others lower — calibrate per named campus).

## Profile C — MIT

| Section | Structure | Reader notes |
|---------|-----------|--------------|
| Application | MIT's own portal — **not Common App**; no 650-word personal statement | Common-App-shaped material must be re-cut, not pasted |
| Essays | **Two tiers, not one** (verified verbatim from [mitadmissions.org](https://mitadmissions.org/apply/firstyear/essays-activities-academics/), page states "For the 2026–2027 application"; `verified_on: 2026-08-23`). **Four main essays, ~100–200 words each**: (1) field of study that appeals most + what led to the interest; (2) "in what ways have you done something different than what was expected in your educational journey?"; (3) how personal/academic experiences shaped the problems you want to tackle and the impact you aim to make on your community; (4) "how did you manage a situation or challenge that you didn't expect?" Plus an open **additional-information** box. **Four short responses, 40–50 words each**: what you do just for fun · someone you admire and why · a topic you could talk about for hours · generalist or specialist, and why | Short-answer culture: directness > scene-setting. **The 40–50-word items are not miniature essays** — a scene-setting opener consumes the whole budget. Grade them as direct answers. Note the *generalist vs. specialist* item is a self-characterization question, not an achievement question |
| Activities | **Only 4 slots** — "choose the four that mean the most to you" | The constraint IS the test: selection reveals values. A trophy-ordered list that ignores "mean the most" misreads the form |
| Coursework | Self-reported grades/coursework | Honesty surface; DA cross-checks vs. claimed rigor |
| Testing | **SAT/ACT REQUIRED** (hardship exceptions); highest section across dates considered; admitted mid-50 ≈ 1520–1570 / ACT 34–36 (approx) | No submit/withhold question exists here |
| Culture read | **MIT's eight named components, verbatim from [what-we-look-for](https://mitadmissions.org/apply/process/what-we-look-for/)** (`verified_on: 2026-08-23`): alignment with MIT's mission · collaborative and cooperative spirit · initiative · risk-taking · hands-on creativity · intensity, curiosity and excitement · the ability to prioritize balance · the character of the MIT community. MIT's own framing: *"it's really the match between the applicant and the Institute that drives our selection process"* | Institutional reader grades fit against these **by name and quotation**, not generic prestige. Two lines carry unusual weight: *"If you enjoy working alone all the time, that's completely valid, but you might not be particularly happy at MIT"* — lone-genius framing is a fit defect; and on scale, *"we're not looking for applicants to have cured all infectious diseases… Tutoring a single kid in math changes the world"* — small, real impact is explicitly sufficient. See `university_guidance.md` |

## Rules

- Missing sections are reported **NOT PROVIDED** — never inferred, never filled in.
- Portal limits shift annually: cite as "approx, [cycle] — verify in the live portal."
- **Formatting survival** (line breaks, bold/italic, special characters, the Common App pipe ban, UC's plain-text rule, UT Austin's line-based limit) lives in `creative_forms.md` §6. Run its plain-text test before praising any form that depends on layout.
- A file assembled for one portal reviewed against another (Common App activities list sent for a UC review) → readers grade against the TARGET portal's format and flag the conversion work as a roadmap item.

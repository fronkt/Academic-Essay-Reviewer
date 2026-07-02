# School Tier Calibration Table

Used by `context_analyst_agent` to set the board's bar, and by all readers to anchor ratings. **Default tier when no school is named: T20-selective.** Reports must state which room they're grading for.

Admit rates are approximate and shift year to year — treat as calibration anchors, not facts to assert to the user as current.

| Tier | Examples | Approx. admit | What the essay must do | Verdict calibration |
|------|----------|---------------|------------------------|---------------------|
| **T10 / hyper-selective** | Harvard, Stanford, MIT, Princeton, Yale, Caltech | <8% | Nearly everyone in the room is academically qualified; the essay is a primary differentiation surface. It must give a reader a REASON to fight — a person they can retell. | 5/5 is rare (a few per reader per season). Competent-and-pleasant = 3. Pool-median execution of a common topic = 3 at best. |
| **T20-selective** (DEFAULT) | Duke, Northwestern, JHU, Rice, Vanderbilt, Cornell, top LACs (Williams, Amherst, Swarthmore), CMU (esp. SCS) | 6–15% | Same holistic weight as T10 with marginally more room; essays regularly decide between interchangeable transcripts. | As T10 with slightly wider 4-band. |
| **Top publics (OOS-competitive)** | UC Berkeley, UCLA, UMich, Georgia Tech, UVA, UNC | 10–25% (OOS harder) | UCs: PIQs are **information-gathering documents scored on evidence** — points for demonstrated activity, leadership, and use of opportunity; artistry is nearly irrelevant, and burying evidence under literary framing is a DEFECT. Others: essay supports a mostly numbers-forward read. | Grade PIQs on evidence-density per the type rubric. A beautiful evidence-thin PIQ rates 2. |
| **Flagship / honors** | Purdue, UIUC, OSU, Wisconsin, UW (+ honors colleges & competitive majors: CS, engineering, nursing) | 25–60% (majors vary hugely) | Base admission is largely stats-driven; the essay matters at the margins — honors, competitive-major gates, scholarships. Clarity and genuine interest in the named program beat lyricism. | Solid-and-specific = 4. The bar is "no reason to doubt," not "reason to fight." |
| **Selective LACs (non-top-tier)** | Oberlin, Macalester, Occidental | 25–45% | Fit and demonstrated interest weigh heavily; the essay should show the student sees THIS community accurately. | Specificity of fit drives the rating more than craft. |
| **Likely / safety** | (applicant-relative) | >50% | Do no harm; show enough interest that yield models believe you'd come. | 3 is fine; flag only red flags and effort so low it insults the school. |
| **Scholarship / competition** | Regeneron STS, Coca-Cola Scholars, Coolidge, Cameron Impact | n/a (juried) | Juries re-read against the program's stated criteria (STS: scientific rigor, the applicant's OWN thinking and role, potential as a scientist). Voice matters, but the writer's demonstrated intellectual contribution governs. **Certification regimes common — Context Analyst must check authorship/AI rules and arm the banner (STS: always).** | Rate against the program's criteria, not college-admissions taste. For STS essays: the inside of the scientific thinking is the content; polish is secondary. |

## Reading-culture notes (apply when the school is named)

- **MIT**: short-answer format rewards directness and concrete specifics; scene-setting throat-clearing is a proportional-cost defect at 200–250 words. Warmth and "makers" culture — collaborative framing lands better than lone-genius framing.
- **UC system**: no "essay" — four PIQs of 350 words. Scored on evidence against the 13 published criteria. First-person declarative beats narrative craft. Never grade a PIQ as a personal statement (SKILL.md anti-pattern #8).
- **Stanford / UChicago-style prompts** (roommate letter, weird prompts): the prompt IS an intellectual-vitality and personality test; a safe, formal answer fails the prompt even if well-written.
- **Georgia Tech / Purdue-type "Why this major?"**: evidence of sustained, specific engagement with the field; generic passion statements rate 2.
- **Honors colleges & competitive-major gates**: read closer to T20 than to the parent flagship — calibrate up one tier.

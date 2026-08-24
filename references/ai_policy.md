# AI-Use & Authorship Policy — the Ladder Gate

Used by `line_editor_agent` to set the **rung ceiling** for a given essay, and by
`context_analyst_agent` to arm the certification banner. This file is the authority for what the
board may and may not hand back as prose.

**This file governs a real submission with real consequences.** Every policy below was fetched from
a primary source and is quoted. Where a school is silent, this file says SILENT — it never infers
permission. Where a claim could not be verified, it is listed in §6 as debunked or unverified and
must not be repeated to a user.

`verified_on: 2026-08-23` · refresh per `source_refresh.md`

---

## 1. The rung ceiling — how the gate works

`line_editor_agent` uses the intervention ladder (L1 mechanics · L2 compression · L3 resequence ·
L4 demonstration · L5 redraft). **The ceiling is set by the strictest regime the essay is bound by**,
not by the most permissive one:

```
1. Is the essay certification-bound (STS / competition)?   -> §5 governs. Usually L0.
2. Is a target school named with a published policy?       -> §4 governs that school.
3. School named but SILENT on AI?                          -> §3 default ceiling.
4. No school named?                                        -> §3 default ceiling.
```

**Default ceiling when the target is silent or unknown: L3**, and L4/L5 only on explicit request
with the risk stated. Rationale in §3.

The line editor **states the ceiling and its source** at the top of every Phase 3 output:
`CEILING: L3 — Bowdoin forbids AI that "rewrite[s] portions of your work or modif[ies] your tone."`

---

## 2. The platform baselines

### Common Application

Two **separate** documents, routinely conflated. The distinction matters.

**(a) The affirmation the applicant signs at submission** —
https://www.commonapp.org/application-affirmations/

> "I certify that all information submitted in the admission process — including this application
> and any other supporting materials — is my own work, factually true, and honestly presented…
> I understand that I may be subject to a range of possible disciplinary actions, including admission
> revocation, expulsion, or revocation of course credit, grades, and degree should the information
> I have certified be false."

**This certification text does not mention AI at all.** It says "my own work."

**(b) The Fraud Policy** (last updated August 2023) — https://www.commonapp.org/fraud-policy/
Fraud includes:

*Verification note: both Common App pages are JavaScript-rendered and resisted direct fetching. The
text below was read from the site's own page-data feed and independently corroborated — Brown's
integrity page reproduces the AI clause verbatim, and Yale's AI policy quotes it. Treat as confirmed,
but re-fetch if the wording ever matters to a decision.*

> "Submitting plagiarized essays or other written or oral material, or intentionally misrepresenting
> as one's own original work: (1) another person's thoughts, language, ideas, expressions, or
> experiences or (2) **the substantive content or output of an artificial intelligence platform,
> technology, or algorithm**…"

⚠️ **"Substantive" is load-bearing.** The policy bans AI-generated *substantive content* — it does not
ban AI use categorically, and it publishes **no carve-out list**. Every "grammar checking is fine"
statement comes from an individual member college interpreting this text, not from Common App itself.
Do not tell a user that Common App blesses grammar tools.

Consequences: investigation, disclosure of findings to the colleges on the applicant's list, and
account suspension or termination.

### University of California

UC's **Statement of Application Integrity** (last updated August 2023) —
https://apply.universityofcalifornia.edu/docs/StatementOfIntegrity.pdf

> "The personal insight responses should reflect the student's own ideas and experiences, be
> independently written by the student and reflect the student's personal writing style. **Students
> may receive advice on content and editing, including the use of generative artificial intelligence
> software to assist with readability, but content and final written text must be their own.**
> Students must not plagiarize… UC conducts regular screenings to verify the integrity of the
> responses, may request authentication of the content or writing as the student's, and will take
> action when it is determined that the integrity of the response is compromised."

This is the **most permissive official carve-out found anywhere**: "readability" plausibly reaches
past pure grammar into clarity and flow — i.e. L1 and arguably L2. It still requires that
"final written text" be the student's own, so **L4/L5 remain out**.

### Coalition / Scoir

**No platform-level AI policy found.** Coalition for College publishes general counseling advice
(https://www.coalitionforcollegeaccess.org/mycoalition-counselor-all/ai-and-the-college-essay) but
it is advice, not a binding rule, and it directs students outward to each college's own policy.
**Treat Coalition/Scoir as delegating to the member institution** — but treat that as a finding about
what could not be located, not as proof of absence. Swarthmore in fact points the other way:
*"We also recommend reviewing policies from the application platforms students use to apply to
Swarthmore (Coalition by SCOIR, Common Application, and QuestBridge), **as they may have their own rules
that limit the use of AI tools.**"* A school telling students the platforms may impose limits is not
corroboration that they impose none. If a Coalition/Scoir rule surfaces, it governs.

---

## 3. The base rate: most schools are silent

Kaplan surveyed admissions officers at 220 colleges by email, July–August 2025:

| Use | Official policy ALLOWS | Official policy BANS | **No policy at all** |
|---|---|---|---|
| AI writes the essay | 2% | 30% | **68%** |
| AI for brainstorming | 27% | 4% | **69%** |
| AI feedback on a self-drafted essay | 21% | 5% | **73%** |

Also: 50% of admissions officers hold an unfavorable attitude toward GenAI in essays; 14% favorable.

**Silence is the modal condition, not an edge case.** Two consequences the board must honor:

1. **Silence is not permission.** An applicant bound by a silent school is still bound by the
   Common App affirmation ("my own work") and Fraud Policy ("substantive content"), neither of which
   defines a bright line. The honest report says: this school has published nothing; here is the
   platform baseline; here is the risk you are accepting.
2. **The default ceiling is set to the strictest *explicit* standard, not the most permissive.**
   A tool cannot know which of ~1,000 member schools will read the essay, and the applicant may
   reuse the draft. The strict line is drawn by **Caltech, Swarthmore and Bowdoin** — the three that
   restrict AI from altering *voice or tone*, which is what compression and resequencing do. Holding
   to their line is the defensible default; holding to Georgia Tech's looser "edit" language is not.
   (Northwestern is *not* one of these three: it prohibits generation, translation and cross-school
   rework, but says nothing about compressing your own prose. Do not cite it for that proposition.)

---

## 4. Per-school published policies

Only schools with a **fetched primary source** appear. Absence from this table means SILENT or
NOT RESEARCHED — never "permitted."

| School | Brainstorm | Mechanics (L1) | Compress/Resequence (L2–L3) | Generate (L4–L5) | Ceiling |
|---|---|---|---|---|---|
| **Brown** | not addressed | **OK** — "spelling and grammar review… as any other platform that supports basic proofreading" | not addressed | **Prohibited** "under any circumstances" | **L1** |
| **Bowdoin** | OK — "brainstorm ideas or reflect on possible essay topics" | **OK** — "review grammar or provide feedback after you have written a draft" | **FORBIDDEN** — "rewrite portions of your work or **modify your tone**" | Forbidden — "draft, write, or generate your responses" | **L1** |
| **Swarthmore** | OK | **OK** — "feedback on readability, spelling, and mechanics" | **FORBIDDEN** — "using AI to **modify the tone** of your writing"; "rewrite a significant portion" | Forbidden | **L1** |
| **Caltech** | OK — "generating questions or exercises to help kick start the brainstorming process" | **OK** — "review grammar and spelling of your completed essays" | Unethical — "replacing your unique voice and tone with AI generated content" | Unethical — "relying on AI generated content to outline or draft an essay" | **L1** |
| **Northwestern** | OK | **OK** — "reviewing the grammar, punctuation, and spelling of your completed essays" | **NOT ADDRESSED** | Prohibited — submitting AI output as your own writing; submitting AI's completion of your outline; **translating**; **reworking one school's supplement for another**. *"You wouldn't ask another person to write your essays for you"* | **L1**, conservatively — L2/L3 are **undefined here, not banned** |
| **Yale** | OK — "seek general advice or topic suggestions at the start" | **OK** — "using an AI platform to review one's grammar or spelling… does not constitute application fraud" | not addressed | **Fraud** — may result in "admission revocation or expulsion" | **L1** |
| **UC** | OK ("advice on content") | **OK** | **Arguably OK** — "assist with readability" | Prohibited — "final written text must be their own" | **L2** |
| **Georgia Tech** | OK | OK | OK — uses the verb **"edit"**: "use it to brainstorm, edit, and refine your ideas" | Ambiguous — "your ultimate submission should be your own"; copy-paste banned | **L3** |
| **Penn** | OK | OK | OK — organizing your thoughts; *"getting help is not the same as losing ownership"* | Forbidden by its own test: *"If you couldn't explain, in an interview or conversation, how you arrived at what you wrote, or speak to it in your own words, it isn't ready to submit."* | **L3** |
| **MIT** | SILENT | SILENT | SILENT | SILENT | default |
| **Princeton** | SILENT — no policy page exists | SILENT | SILENT | SILENT — but see below | default |
| **Stanford** | SILENT | SILENT | SILENT | SILENT | default |
| **Columbia** | SILENT | SILENT | SILENT | SILENT | default |
| **Cornell** | SILENT | SILENT | SILENT | SILENT | default |
| **CMU** | SILENT | SILENT | SILENT | SILENT | default |
| **Michigan** | SILENT (no verifiable policy) | SILENT | SILENT | SILENT | default |

**Silent does not mean unconcerned.** Princeton publishes no AI policy but its "Helpful Tips" page states
it *"may withdraw the application or revoke the admission of any student whose essays have been written by
another source"*, and Dean Karen Richardson is quoted on Princeton's own blog: *"Any essay one writes with
the help of AI is not going to be nearly as good or authentic as one that an applicant composes on their
own."* A school with no AI page still has a fraud policy and a certification. Six of the eight
highest-profile schools researched publish nothing — consistent with the ~70% base rate in §3.

Sources: [Brown](https://admission.brown.edu/apply/how-apply/integrity-application-process) ·
[Bowdoin](https://www.bowdoin.edu/admissions/apply/ai-policy/index.html) ·
[Swarthmore](https://www.swarthmore.edu/admissions-aid/admissions-guidance-usage-artificial-intelligence) ·
[Caltech](https://www.admissions.caltech.edu/apply/first-year-applicants/supplemental-application-essays/ethical-use-of-ai-guidelines-for-fall-applicants) ·
[Northwestern](https://admissions.northwestern.edu/apply/advice/ai.html) ·
[Yale](https://admissions.yale.edu/ai-policy) ·
[Georgia Tech](https://admission.gatech.edu/first-year/application-review) ·
[Penn](https://admissions.upenn.edu/how-to-apply/preparing-your-application/integrity-AI-in-admissions-process)
— note Penn's AI language lives on its **Integrity/AI** page, *not* the `/writing` page cited in
`university_guidance.md`; a student following the wrong link cannot verify any Penn claim

**Caltech's page explicitly governs the Fall 2027 cycle** — the current one. Its stated test is the
best plain-language articulation of the boundary and is worth quoting to users directly:

> "Ask yourself whether it would be ethical to have a trusted adult perform the same task you are
> asking of ChatGPT. Would a teacher be able to review your essay for grammatical and spelling
> errors? Of course! Would that same teacher write a draft of an essay for you to tweak and then
> submit? Definitely not."

Caltech enforcement: "Failure to comply… may result in the rescission of your admission."

### Three edge cases that are multiply confirmed and non-obvious

The board must hard-flag these; an applicant is unlikely to guess any of them.

1. **Translation is prohibited** — named independently by **Caltech** ("translating an essay written
   in another language"), **Swarthmore** ("using AI or another tool to translate your writing from
   another language into English") and **Bowdoin**. Three unrelated offices converging makes this a
   real rule, not a quirk. The board must never translate a draft.
2. **Tone modification is prohibited** at Swarthmore and Bowdoin *by name*. This is precisely what
   L2/L3 do — which is why the ladder is gated per school rather than assumed safe.
3. **Cross-school essay recycling via AI is prohibited at Northwestern** — "using generative AI to
   rework a supplemental essay that was written for one school for another school." Note this sits
   in direct tension with Northwestern's own permission to reuse language *within* one application
   (see `university_guidance.md` contradictions). Reuse by hand: fine. Reuse via AI rework: not.

---

## 5. Certification-bound: Regeneron STS 2027

Source: official rules PDF, `sciencetalentsearch.smapply.org` → `Regeneron_STS_Official_Rules_2027.pdf`

**This is the strictest regime in this file and it is materially stricter than every university above.**

Entry Rule 8 (complete — the permissive second half is included deliberately; an earlier draft of this
file truncated it without an ellipsis):
> "Students may not use generative Artificial Intelligence (AI) to write Regeneron STS application
> questions, draft the Research Report or generate citations. **Students are responsible for
> personally drafting all responses to application questions.** Use of AI tools for student research
> projects is permitted, and should be disclosed and appropriately cited. See acceptable AI usage
> chart on page 34."

Entry Rule 9: "the inappropriate use of AI are prohibited and grounds for the project to fail to qualify."

Entry Rule 10 (outside human help, separate from AI):
> "Any outside support received from teachers, mentors, counselors, relatives, etc. in **reviewing or
> editing responses must be disclosed** in the application."

Entry Rule 12:
> "**All applicants agree to a plagiarism screening through their submission. The screening process
> authenticates essays, research reports and recommendation letters.**"

The Ethics Statement the student signs:
> "I attest that my Research Report and images within are properly credited and cited, and that
> **I did not use AI tools to draft the paper or responses to application questions.**"
> "I attest all content in this submission is exclusively my work in substance and in presentation."
> "**I certify that I have not used AI tools, like ChatGPT, to construct the research report or
> responses to questions in the application.**"

Research Report rule: "The Student Researcher is required to write the paper without the use of
generative AI (ChatGPT or other programs)." On references the rule is advisory in form but severe in
consequence: entrants *"**should** generate their reference lists without the use of AI, which is known
to hallucinate and create fake or altered references. **Discovery of a fake reference will result in
disqualification.**"

### What this means for the ladder

**STS ceiling = L0.** No rung is authorized.

There is **no grammar carve-out for the application questions** — unlike Common App members, UC, Brown,
Yale, Bowdoin, Caltech and Northwestern, all of which explicitly exempt mechanics. An adversarial search
of the full rules found no exception permitting proofreading, grammar, or editing assistance on the
application/essay questions. **The L0 ceiling for essay questions stands.**

⚠️ **One narrow exception exists and it does reach the Research Report.** Appendix 4 permits: *"You write
an abstract. Ask AI to sharpen the language but not modify, add to, or replace the main points"* —
*"Acceptable use without explicit citation only if changes suggested by AI are minor and limited to
grammar and syntax. Must be credited."* Since Appendix 2 §4b makes the **abstract the second page of the
Research Report**, this carve-out is not confined to "the research project" as an earlier draft of this
file claimed. It is still the narrowest possible exception — one component, grammar and syntax only,
minor only, and **credited** — and it does not touch the application questions.

The certification names ChatGPT specifically and covers both the report and the application questions.
Combined with Rule 12's active authentication screening, the honest reading is: **treat STS essay
questions and the Research Report as a zero-AI-assistance zone.** Brainstorming questions that produce
no essay-usable prose remain available; everything else does not.

`essay_type_rubrics.md` §8 already records the user's own standing rule to the same effect. These agree.

**Interlock behavior** (SKILL.md Checkpoint 11): on a certification-bound essay the line editor
refuses L1–L5 by default and offers L0 only. If the user explicitly overrides, output is produced with
the banner AND `DO NOT SUBMIT — DEMONSTRATION ONLY` stamped on every paragraph, and the report states
the certification text being overridden, verbatim.

---

## 6. Debunked and unverified — do NOT repeat these

These circulate widely. An adversarial pass could not source any of them. Repeating one would be the
exact failure mode this skill exists to prevent.

| Claim | Status |
|---|---|
| "73% of selective colleges deploy AI detection software; 91% have trained staff to spot machine-generated language" | **FABRICATED.** Attributed to the Kaplan survey; the actual Kaplan release contains no such statistic |
| "A 2025 NACAC survey found ~20% of admissions offices use or pilot detection software" | **UNVERIFIED.** Repeated across SEO sites; not locatable in any NACAC publication |
| "UCLA, UC San Diego and Johns Hopkins stopped using AI detectors after ~4% false positives" | **CONFLATED.** The real, reported story is about **Turnitin's AI detector being disabled for grading enrolled students' coursework** — not admissions-essay screening. Do not present it as admissions practice |
| "Common App has confirmed it does not scan applications with AI detection software" | **UNVERIFIED.** The Fraud Policy describes a human-report-driven investigation and is silent on automated detection |
| "Georgetown prohibits AI across undergraduate admissions" | **UNVERIFIED for undergraduate.** Confirmed only on a *graduate* program page; the undergraduate requirements page contains no AI mention |
| "Columbia has a Generative AI Policy for applicants" | **CONFLATED.** Columbia's `/artificial-intelligence` page is about its AI *research programs*; its policies page covers document authenticity with no AI mention. The claim appears to conflate Columbia's academic Honor Code for *enrolled students* with applicant guidance. Do not attribute it to Columbia admissions |
| CMU's AI policy quote ("supplementary tool to enhance your writing…") | **UNVERIFIED.** Surfaced only via a third-party aggregator, never from cmu.edu. Do not quote |
| Paraphrased "Cornell essay tips" from its admissions blog | **DEAD SOURCE.** Cornell retired the blog; the URL 404s and the subdomain redirects to the homepage. Search engines still surface paraphrases of it. They have no checkable source — do not quote |

### What IS confirmed about detection

- **UC actively screens.** The Statement of Integrity: "UC conducts regular screenings to verify the
  integrity of the responses, may request authentication." Method unspecified.
- **STS actively screens.** Rule 12 — plagiarism screening that "authenticates essays."
- **UC does not use AI to evaluate.** Reported as fact by the University of California's own news
  office (Apollonia Morrill, 31 Oct 2024): *"Though UC doesn't use artificial intelligence in its
  application review process, AI may be helping students complete their applications."* ⚠️ **This is
  the article's narration, not a quotation from any named official** — an earlier draft of this file
  attributed it to Robert Penman (executive director of undergraduate admissions, UC Davis) and that
  attribution was fabricated. Penman's actual words in the same piece: *"A personal insight question
  written by AI is not going to be very good, because it's not going to teach us anything about the
  student,"* and *"That can't be generated by a machine, it really has to come from the student."*
  Quote those; cite the narration to the news office.
- **Penn does not use AI to evaluate**: "Artificial Intelligence does not" make admissions decisions.
- **Swarthmore does not use AI to evaluate**: "Real people will be reading your application."
- Several offices (Yale, Swarthmore, Northwestern) describe **human pattern recognition** by readers who
  see thousands of essays as the real mechanism. Note: a school saying it does not use AI to *evaluate*
  is NOT the same as saying it does not use a detector to *flag*. Never conflate the two.

**Framing rule inherited from `ai_tells.md`:** a reader's suspicion does not require proof. The board
never tells a user "you will not get caught" — that is not the standard, and it is not the risk that
matters. The risk is that a voiceless essay loses on the merits whoever wrote it.

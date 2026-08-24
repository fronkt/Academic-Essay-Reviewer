# University-Published Essay Guidance — Primary Source

What admissions offices say, **in their own words**, about what they want from an essay.

Used by `institutional_reader_agent` (fit is graded against the school's stated preference, quoted —
not against inferred culture), `context_analyst_agent` (Context Card reader flags), and
`line_editor_agent` (structural direction).

**Why this file outranks `school_tiers.md` on questions of taste.** `school_tiers.md` sets *how high*
the bar is. This file records *what the school says it is looking for*. Where they conflict for a named
school, this file governs and the report says so.

## Source-strength tags — these are load-bearing

| Tag | Meaning | May a reader attribute it to the school? |
|---|---|---|
| `OFFICIAL` | Fetched from the admissions office's own page/blog | Yes — "X says…" |
| `OFFICIAL-ADJACENT` | Authored by an admissions officer or the university's news office, but not on the admissions site | Yes, **with the caveat named** |
| `SNIPPET` | Search-result summary only; the page itself did not render | No. Use as a lead, never as a quote |
| `NOT FETCHED` | Could not retrieve | No. Report the gap; never fill it from memory |

⚠️ **Never attribute a quote to a university unless it carries `OFFICIAL` or `OFFICIAL-ADJACENT`.**
A fabricated or misattributed admissions quote is the worst defect this skill can produce — it would be
repeated back to an admissions officer by a student who trusted it.

`verified_on: 2026-08-23` · refresh per `source_refresh.md`

---

## The attribution rule

**A university's domain is not a university's voice.** `.edu` sites host student bloggers, alumni
guest posts, news-office articles, and graduate-program pages — all of which read like institutional
guidance and none of which is. This is the single most common way a quote in this file goes wrong, and
it has now happened repeatedly, including *after* a warning list naming two specific instances was
already in this file. A list of known traps does not work; the rule does:

> Before tagging anything `OFFICIAL`, identify **who wrote it and in what capacity.** If the answer is
> a student, an alum, a reporter, or a graduate program — it is not the admissions office's position,
> however sound the advice is and whatever domain it sits on.

Known instances, kept as worked examples rather than as the whole list:

1. **UVA's "Notes from Peabody" (Dean J)** is a personal Blogger site (`uvaapplication.blogspot.com`),
   self-identified as unofficial. Tag `OFFICIAL-ADJACENT`; cite as "a UVA admissions dean writes…",
   never "UVA says…"
2. **Harvard hosts at least two student-written essay-advice pages** — "Commonly Asked Questions:
   College Essays" (Class of '18) and "My Very Unofficial Tips on Writing Your College Essay" (an alum
   who calls himself "just a shmuck" with "no say in the admissions process"). Harvard's actual official
   page is **"Application Tips."** Quotes were wrongly pulled from the second of these; see the entry.
3. **UC's news office (universityofcalifornia.edu/news) is not UC admissions**, and its article
   *narration* is not a quotation from the officials it interviews. See `ai_policy.md` §6.
4. **Graduate-program pages are not undergraduate admissions.** A Georgetown graduate page and an MIT
   Chemistry page were both nearly cited as institution-wide policy.

---

## Part 1 — By school

### MIT · OFFICIAL
https://mitadmissions.org/apply/process/what-we-look-for/ · blogs at mitadmissions.org/blogs

- Collaboration is the stated core: *"The core of the MIT community is collaboration and cooperation"* —
  and they say it may not suit students who prefer working alone. **Lone-genius framing is a fit defect here.**
- Risk tolerance: *"we want to admit applicants who are not only planning to succeed but who are also
  not afraid to fail."* Hands-on: *"Innovation is risky and messy! Getting your metaphorical or literal
  hands dirty."*
- **"MIT is NOT all about work"** — they explicitly want evidence of things pursued for pleasure, and a
  prompt asks for exactly that, adding: *"This is not a trick question. Answer it honestly!"*
  → A relentlessly achievement-focused MIT application misreads the form.
- Chris Peterson (Director of Communications) on craft: leans on Orwell's rules (cut every possible word,
  active voice, no clichéd figures of speech, short words over long) and Vonnegut's (*"sound like yourself"*).
  **He explicitly warns against essay-advice books** like *50 Winning College Essays from Ivy League
  Students*, saying they reproduce the *"lifeless, imitative style"* Orwell criticized.
  His test: imagine someone asked you the prompt casually in the casserole line at a family reunion —
  answer *"introspectively… without fear of judgment or needing to impress them."*
- On context: *"Every MIT admissions decision is not entirely about you… it is, in some fundamental way,
  about other people."*

### Yale · OFFICIAL
https://admissions.yale.edu/advice-putting-together-your-application · /essays

- Two guiding questions: *"Who is likely to make the most of Yale's resources?"* and *"Who will contribute
  most significantly to the Yale community?"*
- **The single most useful line for grading topic choice**: *"We've read wonderful essays on common topics
  and weak essays on highly unusual ones."* And: *"Your perspective — the lens through which you view your
  topic — is far more important than the specific topic itself."*
- *"If an essay doesn't sound like the person who writes it, it cannot serve very well as a personal statement."*
- Applicants are read *"within their own context"* relative to their school's resources.

### Princeton · OFFICIAL
https://admission.princeton.edu/apply/before-you-apply/helpful-tips · admission.princeton.edu/blogs

- *"Tell us your story. Show us what's special about you."* Essays give context for achievements rather
  than restating the résumé.
- Strong explicit warning: Princeton *"may withdraw the application or revoke the admission of any student
  whose essays have been written by another source"* — including essays found online or written by parents,
  counselors or teachers.
- Dean Karen Richardson, quoted on Princeton's own blog: *"Any essay one writes with the help of AI is not
  going to be nearly as good or authentic as one that an applicant composes on their own."*
- What they look for: *"curious minds, intellectual spark, a willingness to step outside of one's comfort
  zone and a true desire to learn about and from others."*
- ⚠️ **Two opposite standards inside one application.** The **graded written paper** must be *"expository,
  thesis-driven analytical writing rather than science research, creative writing, personal narratives or
  papers mostly focused on data analysis."* The board must never apply personal-essay standards
  ("voice", "show don't tell") to a graded paper, or vice versa.

### Penn · OFFICIAL
https://admissions.upenn.edu/how-to-apply/preparing-your-application/writing

- *"Your writing is a window into how you think, what you value, and how you see the world."*
- **The recognition test** — the cleanest statement of the voice standard anywhere in this file:
  *"If someone who knows you came across your writing without your name on it, would they know you wrote it?"*
  → This is directly operationalizable by `craft_reader_agent`'s voice check and by the L4/L5 voice gate.
- *"We don't need you to summarize the rest of your application in your statement or short answers."*
- Warns against not fully or directly answering the specific prompt.

### Harvard · OFFICIAL — *entry trimmed after re-verification; read the note*
https://college.harvard.edu/guides/application-tips

Only two lines here are Harvard's admissions office:
- *"Look at it as an opportunity to write about something you care about, rather than what you think the
  Admissions Committee wants to hear."*
- *"Your topic does not have to be exotic to be compelling."*

⚠️ **Two lines were removed from this entry after an adversarial re-check.** *"The personal essay is the
only place in your entire application where the admissions officers have the ability to hear your own
voice"* and the "don't try to impress" advice are **not** on Application Tips. Both come from a Harvard
College *student story* — "My Very Unofficial Tips on Writing Your College Essay," by an alum who writes
in the piece: *"To clarify again: I'm just a shmuck. I have no say in the admissions process."*
They are not Harvard's position and must never be quoted as such.

### Tufts · OFFICIAL — unusually generous, worth reading in full
https://admissions.tufts.edu/blogs/inside-admissions/post/5-essay-writing-tips-to-get-you-through-december/ ·
/deconstructing-the-why-tufts-essay/

- *"Your writing serves to give a human element to your application file, creating a connection between
  you and the reader."*
- Essays are read **as a package**: avoid repetition across them; they want *"the multiple interests and
  experiences that make you a multifaceted human being."* → direct authority for `portfolio` mode.
- **Depth over breadth**: *"Describing a single experience/interaction/memory/source of inspiration with
  vivid detail and deep reflection can often have the most powerful and original impact."*
- **Register permission**: *"The language, style, and spirit of your essays certainly can and should be
  authentic to how you speak in real life."* Tufts warns against writing in *"the same tone as a research
  paper or book report"* (an earlier draft of this file compressed that into a shorter pseudo-quote —
  use the real wording). Author: Sean Ashburn, Director of Communications & Outreach.
- On feedback: limit readers to 2–3, ideally *"one person who's a particularly strong writer and one person
  who knows you REALLY well."*
- "Why Tufts" quality ladder (0–3): worst is misspelling "Tufts" or naming another school; weak answers
  cite generic features ("offer biology and are near Boston"); strongest connect distinctive Tufts programs
  to personal values and name the moment the student decided.

### Carleton · OFFICIAL — unusually candid about reader psychology
https://www.carleton.edu/admissions/apply/steps/essay/

- Distinguishes applicants *"who believe in what they are saying versus those who simply say what they
  think we want to hear"* — an office stating plainly that it can tell the difference.
- *"Don't try to take on too much. Focus on one event, one activity, or one 'most influential person.'"*
- *"Don't do a history report. Some background knowledge is okay, but do not re-hash what other authors
  have already said."*
- *"Limit the number of people who review your essay. Too much input usually means your voice is lost."*
- Wants vulnerability: describe when you *"stumbled, and what happened next."*

### Hamilton · OFFICIAL — the bluntest page in this file
https://www.hamilton.edu/admission/apply/college-essays-that-worked/tips-for-a-good-college-essay

- *"It goes without saying that your essay needs to be written by you."*
- *"Be real and be yourself; unless you want to be a theatre major, it is way too hard to try to be what
  you think we want."*
- **"Substance and voice are better than perfection."** ← quote this to any applicant over-polishing.
- Dislikes: thesaurus overuse, over-editing into *"a research paper"* — and, two-sided, being *"too casual
  or to over-share."* On outside readers the page says only: *"It is ok to have someone else look over the
  essay… but don't over-edit."* (An earlier draft added a claim that Hamilton says it can spot parental
  involvement. That is not on the page — removed.)

### Vanderbilt · OFFICIAL
https://admissions.vanderbilt.edu/vandybloggers/2017/10/tips-for-writing-your-college-essay/

- Method worth passing to a stuck writer: *"turn on the recording device on my phone, and just start talking."*
- **The identification test**: *"If we threw your essay in with everyone's in your senior class, your friends,
  teachers, and parents should be able to tell us which one was yours."*

⚠️ Two further lines belong to a **different Vanderbilt post** — "Guest Blog: Tips For Writing Your Personal
Essay," 22 Nov 2011, by Mary Comfort Stevens
([link](https://admissions.vanderbilt.edu/vandybloggers/2011/11/guest-blog-tips-for-writing-your-personal-essay/)).
Right school, right office, wrong document; an earlier draft cited them to the 2017 post, where a student
clicking through would not find them:
- *"It's not the topic that matters, it's how you use it as a means to reveal yourself."*
- Reassurance for applicants who feel unremarkable — the original wording is *"an ordinary high school
  senior with an ordinary life devoid of excitement, glamour, tragedy, or obvious essay fodder."*

### Rice · OFFICIAL
https://admission.rice.edu/blog/in-the-know/writing-supplemental-essays

- Move from generic claims (*"I'm passionate about biomedical engineering"*) to *"specific experiences,
  interests and thoughts."*
- The application is a narrative arc; the supplement provides *"closure that bridges the gap."*
- Distrust superficial fit reasons — *"proximity to family or campus size… doesn't necessarily reflect
  deep exploration."*
- Unusually candid: *"If you're really struggling to answer a school's supplemental prompts… it's worth
  reevaluating your reasons"* for applying at all.

### Johns Hopkins · OFFICIAL
https://apply.jhu.edu/college-planning-guide/essays-that-worked/

- *"The essays are a place to show us who you are and who you'll be in our community."*
- *"The most important thing to remember is to be original as you share your own story."*
- Their published annotated admits consistently pair **ordinary subjects** with deep reflection — the
  house style is small-topic/deep-handling, not impressive-topic. The current set: "The Secret Ingredient
  is Connection" (baking), "Developing Roots" (trees), "The Two Sides of America," "Clean Closet,"
  "In the Belly of the Ship."

### Duke · OFFICIAL
https://admissions.duke.edu/what-we-look-for/

- Unusually transparent: the essay is named as **one of five** stated evaluation factors —
  rigor, performance, recommendations, extracurriculars, and *"quality of thought and expression in the
  application essay."*
- *"Get creative, be concise, and don't forget to proofread."* *"Craft your short writing as carefully as
  the longer personal essay."*

### Dartmouth · OFFICIAL
https://admissions.dartmouth.edu/glossary-question/how-do-i-impress-dartmouth-my-essays

- *"Make sure your essays illustrate your personality!"* — humor, passion, intellectual curiosity,
  self-awareness, social awareness. *"Help us envision what you'll bring to Dartmouth."*

### Georgia Tech · OFFICIAL
https://sites.gatech.edu/admission-blog/ · https://admission.gatech.edu/first-year/application-review

- Rick Clark (10 Sept 2025): colleges are looking for *"your true voice—the one you'll bring with you to a
  college classroom or residence hall."* (Earlier drafts truncated this before "or residence hall.")
- `SNIPPET` — Clark's dislikes (*"five easy steps to the perfect essay"* formulas, inflated vocabulary,
  over-editing by too many reviewers, hiring professionals, reverse-engineering what schools want) could
  **not** be tied to a specific post on re-check. Real in substance, not citable to a URL — use as a lead,
  and do not put quotation marks around any of it.
- Julissa Ortiz (`SNIPPET`): *"read your essay out loud to ask yourself if it sounds like you."*
- The official review page confirms review is *"selective, holistic"* but **does not disclose reader counts
  or weighting** — do not claim GT publishes those.

### UNC Chapel Hill · OFFICIAL
https://admissions.unc.edu/application-advice-from-our-admissions-counselors/
Three tips: *"Share specific details." "Write a draft or two." "Ask your friends to read your essay."*

### Stanford · OFFICIAL
https://admission.stanford.edu/apply/first-year/apply.html
- *"The essays are your chance to tell us about yourself in your own words; there are no right or wrong
  answers and you should allow your genuine voice to come through."* Framed as writing to *"a friend,
  future roommate, and classmate."*

### University of California · OFFICIAL
https://admission.universityofcalifornia.edu/how-to-apply/applying-as-a-first-year/personal-insight-questions.html

- Structure: 8 questions, answer **any 4**, max **350 words** each.
- **Equal weighting, stated outright**: *"All questions are equal. All are given equal consideration in the
  application review process."* → the board must never advise "save your best for #1."
- *"Show us your personality — just as you would in real life."* *"Use specific, concrete examples to support
  the points you want to make."*
- Explicit dislike: do not make the response *"a list of accomplishments, activities, awards or work."*
- ⚠️ **Polish expectation, against the grain of most schools here**: *"Grammatical and spelling errors can be
  distracting to the reader."* UC is the clearest case where L1 mechanics has affirmative institutional value.
- Role: *"This is one of many pieces of information we consider in reviewing your application."*

### UVA · OFFICIAL-ADJACENT (personal blog — see trap #1)
uvaapplication.blogspot.com — "Notes from Peabody," by an admissions dean
- *"We don't spend time to count the words in essays. We are more interested in reading them!"*
- *"Too many cooks in the kitchen spoils the broth."*
- Published "essays that worked" collections are *"extraordinary"*; most successful real essays cover
  *"pretty normal topics."*

### UChicago · OFFICIAL-ADJACENT (university news office, not admissions)
https://news.uchicago.edu/story/uncommon-approach-yields-creative-college-essays
- Grace Chapin, senior admissions counselor: *"We want the students to write about things that don't show
  up in a workshop on writing college essays."*
- *"You can't write it the day before it's due, so we see extremely high-quality writing from the applicants"*
  — the uncommon prompts function as a deterrent to formulaic or outsourced writing.
- Prompts are largely crowd-sourced from current and former students.

### Notre Dame · SNIPPET
Emily LaPlaca (admissions counselor): choosing topics based on what you think they want to hear is not the
best use of the opportunity; *"It is abundantly clear when you have rushed through your essays just to check
a box."* Warns against forced humor, reusing personal-statement content in supplements, and copy-pasting
answers across schools. **Lead only — do not quote as Notre Dame policy until re-fetched.**

### Emory · OFFICIAL (tips) / SNIPPET (AI framing)
https://apply.emory.edu/apply/first-year/tips/index.html — *"We get inspired hearing about you."*
*"We hope you use your essay to give us a compelling glimpse of the real you."*

### Cornell · OFFICIAL
https://admissions.cornell.edu/apply/first-year-applicants/cornell-first-year-writing-supplement

⚠️ **Structural fact most guidance gets wrong: Cornell has no university-wide supplement.** You apply to
one of **nine** first-year admitting units and answer *that unit's* prompt. Grading a Cornell supplement
against a generic "Why Cornell" standard is a category error. Prompts below verified 2026-08-23:

| Unit | Length | Prompt focus |
|---|---|---|
| **Arts & Sciences** | 650 | *"Describe an intellectual passion, question, or idea that has captured your attention… What specific aspects of our liberal arts curriculum would you draw on to explore and connect your varied interests?"* |
| **Human Ecology** | 550 | An experience connecting you to the CHE mission + your intended major; what it taught you about your community's needs and the impact you can make |
| **CALS** | 350 ×2 | (1) what interests you about the major, w/ experiences; (2) what draws you to CALS specifically |
| **AAP** | 650 | Major-specific: Architecture (a design project), Fine Arts (artist statement on practice/voice), Urban & Regional Studies (cities/communities) |
| **Engineering (Duffield)** | 200 ×2 + 100 ×4 | "Why engineering?" / "Why Duffield?" + four short answers: joy, unique contribution, meaningful activity, meaningful award |
| **SC Johnson — Dyson & Nolan (Hotel)** | 650 | Shared prompt: *"What kind of business student are you?"* Nolan leans entrepreneurship; Dyson leans community-minded impact |
| **ILR** | 650 | Topics/issues you care about, showing alignment with ILR's study of *"people, policies, and workplace issues"* — not club name-dropping |
| **Brooks School of Public Policy** | 650 (+350 for DC Start) | Interest in policy and what draws you to Brooks |

Cornell's stated evaluation criteria, near-identical across unit pages: **Academic Preparation /
Intellectual Potential · Character** (honesty, open-mindedness, initiative, collaboration, empathy,
curiosity) **· Involvement · Fit** with both Cornell and the specific college.

**Confirmation status** — the nine-unit structure, and the Arts & Sciences, CALS, Engineering and
SC Johnson rows, were confirmed by two independent fetches. **Human Ecology (550), AAP, ILR, Brooks and
the evaluation criteria are single-source** — treat the word limits on those four as approximate and
re-verify against the unit page before telling a student to write to them.

⚠️ Cornell's essay-advice blog post is a **confirmed dead link** — the admissions blog was retired in a
site redesign, and the old subdomain redirects to the homepage. Search engines still surface the dead URL
with paraphrased "Cornell tips." **Those paraphrases have no verifiable source — never quote them.**

### Columbia · OFFICIAL — single-source, re-verification blocked
https://undergrad.admissions.columbia.edu/apply/process/columbia-questions — page states
*"Updated Tuesday, July 28, 2026"*, so this is current-cycle.

⚠️ Retrieved once via a browser session; **an adversarial re-check hit HTTP 403 on every route.** The
prompts below are therefore single-source, and the re-check did find a transcription error in them (a
miscount, since fixed). The currency stamp, the Marinaccio attribution, the committee-review quote and
the five attributes are all **unconfirmed by a second read.** Re-fetch before quoting any of it to a
student, and treat the word limits as approximate until you do.

- **The list question (100 words):** titles of *"texts, resources and outlets that have contributed to
  your intellectual development outside of academic courses"* — books, journals, websites, podcasts,
  essays, plays, presentations, videos, museums. Instructions are explicit: comma/semicolon separated,
  no numbering, no italics, and *"No author names, subtitles or explanatory remarks are needed."*
  → **Grading note: this is a list, not an essay.** Annotating it, or curating it to impress, misreads
  the form. A reader flagging "no analysis" here would be wrong.
- **Five short answers, ≤150 words each**: lived experience → contribution to Columbia's
  *"multidimensional and collaborative environment"*; a disagreement and what you took from it;
  navigating adversity; why Columbia; what attracts you to your areas of study.
  (An earlier draft said "six" while listing five — the count is five.)
- **Columbia's own stated purpose**: these *"provide insight to your intellectual curiosity, habits of
  mind, love of learning and sense of self… an essential part of our holistic and contextual review."*
- Process (signed by Dean **Jessica Marinaccio**): holistic, contextual, **committee-based** —
  *"no candidate is admitted… without discussion and examination of the application by multiple
  admissions officers."* Five attributes, explicitly *"not… a strict checklist or rubric"*:
  **academic preparation · curiosity · engagement with others · individual voice · knowledge of Columbia.**

### Carnegie Mellon · OFFICIAL
https://www.cmu.edu/admission/admission/admission-consideration
(the `admission.enrollment.cmu.edu` domain now 301-redirects here)

**Three required essays, 300 words max each — university-wide, the same for every college:**
1. What passion or inspiration led you to your intended area of study?
2. *"How will you define a successful college experience?"*
3. *"Consider your application as a whole. What do you personally want to emphasize… Highlight something
   that's important to you or something you haven't had a chance to share. **Tell us, don't show us
   (no websites please).**"*

That last clause is CMU's own explicit warning and is worth quoting to any applicant tempted to link a
portfolio. Note also: **there is no separate "Why CMU" essay** — prompt 1 does the college-fit work.
Engineering applicants are admitted directly to a department; CFA requires auditions/portfolios.
No college-specific essay guidance for SCS, Tepper, MCS or Dietrich exists on CMU's site.

### Caltech · OFFICIAL
https://www.admissions.caltech.edu/apply/first-year-applicants/supplemental-application-essays
and `/essay-writing-advice` — page governs the **Fall 2027 cycle** (the current one)

- **STEM academic interest** (150–200) · **Scholarly character** (choose 1, ≤200) framed by
  *"How do you learn when there is no easy answer?"* · **Scientific drive** (choose 2 of 3, ≤200 each)
  framed by *"How does STEM come alive in your life through learning, pursuing, or making?"* ·
  **Fun question** (100–150): what you'd be excited to *"do, share, teach, make, start, or contribute."*
- Guidance, and it inverts the usual advice: *"there is no way to write about too much STEM in your
  supplemental questions."* Also *"Embrace your own voice and personality!"*, current passions over
  childhood-inspiration stories, and — because **Caltech has no interviews** — the essays are the only
  place admissions *"hears your voice."* Faculty review the most competitive files, so
  *"feel free to get technical."*
- Warns against: choosing an unpopular major to stand out, procrastinating past revision time, generic
  enthusiasm, listing activities.
- ⚠️ **Do not import general-admissions advice here.** "Don't make it all about academics" is standard
  counsel almost everywhere and is *wrong at Caltech*, in Caltech's own words.

### Princeton — supplement specifics · OFFICIAL
https://admission.princeton.edu/apply/princeton-specific-questions · `/graded-written-paper`

- 250-word academic essay (different text for A.B. vs. B.S.E.); a 400–500-word "Your Voice" question
  (*"What lessons have you learned in life thus far? What will your classmates learn from you?"*);
  a 250-word service/civic-engagement question; three ≤50-word rapid questions (a new skill, what brings
  you joy, current "soundtrack" song).
- **Graded written paper** requirements, verbatim: from *"an academic course in English, social studies
  or history"*, preferring *"expository, thesis-driven analytical writing rather than science research,
  creative writing, personal narratives or papers mostly focused on data analysis"*, from the last three
  years, *"at least one page in length"*, originally in English, submitted with prompt, grade and any
  teacher comments. Purpose: to *"assess the student's written expression in an academic setting."*
  → See contradiction #5. A STEM applicant's instinct to submit a research paper is **explicitly wrong** here.
- Dean Karen Richardson on how files are actually read: *"We have laughed at your funny anecdotes, cried
  (yes, cried) over some of the situations you have trusted us enough to share and thought about how you
  might add to this vibrant community."*

### Stanford — supplement specifics · OFFICIAL
https://admission.stanford.edu/apply/first-year/apply.html · `/apply/overview/index.html`

- **Five short questions (3–50 words)**: a significant societal challenge; how you spent the last two
  summers; a historical moment you wish you'd witnessed; elaborate on one activity/job/family
  responsibility; *"List five things that are important to you."*
- **Three short essays (100–250 words)**: an idea or experience that makes you *"genuinely excited about
  learning"*; a note to your future roommate; what would help you *"make a distinctive contribution."*
- Holistic review: *"Each piece in your application is reviewed as part of an integrated and comprehensive
  whole."* Academic bar stated bluntly: *"academic excellence, which means flawless or nearly flawless
  grades in rigorous courses."* Named criterion: **"intellectual vitality."** Activities: *"exceptional
  depth of experience in one or two activities"* over breadth. And explicitly: *"no minimum GPA
  requirement, nor is there a specific number of AP or honors courses"* required.

### Brown · essay-advice page NOT FETCHED (integrity/AI page IS captured — see `ai_policy.md`).
### Williams · Pomona · Swarthmore (essay advice) · Colby · Michigan · Wisconsin · UT Austin · NOT FETCHED / SNIPPET only.

---

## Part 2 — Corroborated themes

Stated **independently by unrelated admissions offices**. These outrank any single consultant's advice and
outrank the model's priors. A reader citing one of these is citing institutional consensus.

1. **Write what matters to you, not what you think we want to hear.** The most repeated idea in the entire
   corpus — Yale, Harvard, Cornell, Notre Dame, Carleton, UVA, Georgia Tech.
2. **The topic does not matter; the handling does.** Harvard (*"does not have to be exotic"*), Yale
   (*"wonderful essays on common topics"*), Vanderbilt, JHU, Hamilton, MIT, UVA.
   → Direct institutional support for `cliche_taxonomy.md`'s salvage-conditions model: a common arc is
   **not automatically fatal**. The board must never rate an essay down for topic alone.
3. **The voice-recognition test.** Penn (*"would they know you wrote it?"*), Vanderbilt (*"tell us which one
   was yours"*), Tufts (*"authentic to how you speak in real life"*), Georgia Tech (*"read it out loud"*).
   → This is the standard the L4/L5 **voice gate** enforces. It is not a stylistic preference; four
   independent offices state it as the test.
4. **Over-editing destroys the essay.** Tufts (2–3 readers max), Carleton (*"your voice is lost"*),
   UVA (*"too many cooks"*), Hamilton (*"sound like a research paper"*), Georgia Tech.
   → **The most important theme for this skill to respect about itself.** Five offices independently warn
   that too much outside input is a *defect*. A board that hands back heavy rewrites is one of those cooks.
   This is the institutional case for the ladder's restraint, and it belongs in the Phase 3 preamble.
5. **Do not restate the résumé.** Penn, UC (*"not a list of accomplishments"*), Dartmouth, Princeton.
6. **Depth over breadth — one moment, not a survey.** Tufts, Carleton, JHU, Georgia Tech.
7. **Answer the actual question asked.** Penn, Cornell, Carleton.
8. **AI assists, never authors.** Every school with a policy. See `ai_policy.md`.

---

## Part 3 — Contradictions

Real disagreements between real offices. **The named school governs.** These are exactly what a tier table
cannot encode, and why this file exists.

| # | Tension | Resolution rule |
|---|---|---|
| 1 | **Essay weight.** UVA's dean frames it as a tiebreaker that turns a reader into an advocate. Duke names it one of five factors. UC says PIQs are *"one of many pieces of information"* and *"all questions are equal"* | Calibrate advice to the named school. Never import UVA's tiebreaker framing into a UC review |
| 2 | **Reusing content.** Northwestern explicitly permits reusing language between your own personal essay and supplement. Notre Dame calls reuse a *"missed opportunity"*; Tufts warns against overlapping topics across its prompts | Named school governs. Note that Northwestern permits *human* reuse but prohibits *AI-assisted* cross-school rework (`ai_policy.md` §4) |
| 3 | **Polish vs. authenticity.** UC: *"grammatical and spelling errors can be distracting."* Georgia Tech and Hamilton warn against thesaurus prose and research-paper polish | Not truly opposed — they name opposite failure modes. UC worries about sloppiness; GT/Hamilton about inauthenticity. Grade against the one that school names |
| 4 | **AI permissiveness.** Penn: *"getting help is not the same as losing ownership."* Bowdoin forbids AI even to *"modify your tone."* Yale calls generated content fraud | Strictest binding regime governs. See `ai_policy.md` §1 |
| 5 | **Voice vs. analysis inside one school.** Princeton wants personal voice in the essay and *"expository, thesis-driven"* prose in the graded paper | Grade each document against its own stated purpose. Never apply essay standards to a graded paper |

---

## Reader instructions

1. When a school is named, **open its entry first**, and grade prompt-fit and tone against what it says —
   quoting the line you are grading against.
2. If the school is `NOT FETCHED` or absent, say so plainly: *"No published guidance retrieved for this
   school; grading against tier culture per `school_tiers.md`."* Never invent a preference.
3. When a corroborated theme (Part 2) supports a finding, cite it — an objection backed by five offices
   is stronger than one reader's taste, and the applicant can verify it.
4. When a contradiction (Part 3) is in play, name it and say which school governs. Do not average.
5. Check `verified_on` against `source_refresh.md` thresholds before relying on prompts or limits.

# T2 dry run — `college-essay-board` v1.3.0, `forms` mode

Run 2026-09-23. Skill followed as written: SKILL.md (mode table row, mode selection), `agents/context_analyst_agent.md`
("Forms mode"), `agents/craft_reader_agent.md`, `agents/institutional_reader_agent.md`,
`templates/forms_menu_template.md`, `references/creative_forms.md`. Other references were opened only where those files
point: `university_guidance.md` (prompt verification, school entries), `ai_policy.md` (certification, task 3),
`source_refresh.md` (staleness), `essay_type_rubrics.md` (#6 UC PIQ), `school_tiers.md` (the Stanford reading-culture
note cited in `creative_forms.md` §3), `craft_frameworks.md` §1.4 (template §4), `cliche_taxonomy.md` #21 (template §4),
`portal_specs.md` (via the SKILL.md reference table for the context analyst). Nothing under `research/` was opened. No web access.

No applicant profile and no draft, so both menus are general. Every T1 ("fit to this writer") is the writer's call.
Marker convention: *(S)* = the catalog's own SKILL SYNTHESIS. *(inference)* = this run's reasoning. The template has no
marker for the second kind (see friction log F-17).

---

## MENU 1

```
FORMS MENU — "Five things important to you" · Stanford · 3–50 words

PROMPT (verbatim):   "List five things that are important to you."   verified: 2026-08-23, university_guidance.md
                     "Stanford — supplement specifics · OFFICIAL" (https://admission.stanford.edu/apply/first-year/apply.html);
                     31 days old, inside the 90-day prompts-and-limits threshold (source_refresh.md). Matches the user's text.
FORM REQUIRED?:      yes: the prompt asks for a list. creative_forms.md §3 names "Stanford's ... five-things list" as
                     prompt-mandated, so it is graded on execution. The list itself is never the risk.
LIMIT:               3–50 words. The minimum is shared across Stanford's five short questions (university_guidance.md);
                     a five-item list clears it by construction. Counted how: Common App, "Words; counting method
                     undocumented" (§6). Trust the portal's counter. Hand-typed numerals ("1.") may or may not count.
PORTAL:              Common App (Stanford's member questions)
FORMATTING SURVIVES: Treat as PLAIN TEXT. Per §6, the Common App documents styling only for "long answer questions",
                     so short-answer boxes are plain text. Single line breaks: not documented, so a one-item-per-line list
                     is RISKY (4.11), and inline separators (commas or semicolons) are the safe form. Characters: Windows-1252.
                     Dashes, curly quotes and • survive; emoji, non-Latin scripts, arrows and ✓ garble. NEVER use the pipe
                     "|": it "causes portions of your responses to disappear" (Common App, OFFICIAL, July 2026).
SCHOOL STANCE:       "there are no right or wrong answers and you should allow your genuine voice to come through"
                     (Stanford, OFFICIAL, 2026–27; creative_forms.md §5 / university_guidance.md). Stanford has published
                     nothing on form or risk as such. Its stance is a voice line, and the prompt itself mandates the form.
                     personal statement: n/a (a school-specific short answer)
CERTIFICATION:       none. Stanford is SILENT on AI (ai_policy.md §4). The platform baseline still binds: the Common App
                     affirmation ("my own work") and Fraud Policy ("substantive content"). Not certification-bound.
WHAT THE PROMPT TESTS: values revealed by selection: what the writer cares about, legible from five choices alone, in
                     the writer's own voice. Stanford's published words are "genuine voice". The "personality test"
                     reading is school_tiers.md JUDGMENT, not Stanford's.
```

*Header check:* no field was inferred except WHAT THE PROMPT TESTS, which is analytic by nature. I did not pause for
correction (see F-20).

## 1. The conventional target (always first)

Five plain items, written inline, each specific enough that no other applicant could have written it. A proper noun, a
named object, a particular practice or person-by-role beats a category word. The craft is **selection** (§3 mandated-list
LOW row: "specific over generic, nothing any applicant would list", *(S)*). "Conventional is not formal" (§3, *(S)*): a
stiff, dutiful list fails a Stanford-style prompt even when it is correct (school_tiers.md, JUDGMENT). At 50 words you have
roughly 9–10 words per item at most, and nothing obliges you to use them. **For most writers the conventional target is
the right call.** Ordering the items (MEDIUM-1) costs zero words, so it is the cheapest step up.

## 2. Options by risk level

Because the form is mandated, the levels below measure **distance from a plain list** (creative_forms.md §3,
mandated-list column). The LOW/MEDIUM/HIGH tag on each block is the §3 mandated-list level. It is not the catalog entry's
own level, and those two sometimes disagree (F-1, F-8).

### LOW — fresh framing

```
NOT-THE-OBVIOUS-CATEGORY LIST  ·  risk: LOW  ·  catalog: creative_forms.md §4.5 (+ §3 mandated-list LOW row)
  Move:        Five plain items, but they are not all the same kind of thing. Mix a concrete noun, a verb-phrase
               habit, a named place, a person by role, an idea stated as a phrase, instead of five abstract values.
  Why it can work here: 4.5 names the failure: "DON'T use Top 50 adjectives". The obvious word is the failure, and
               the list-item version of that rule is (inference). T3: selection is the subject of the prompt, so
               varied kinds of items show range. T4: it still reads instantly as a list. T7: no scaffolding. T10: inline
               commas survive plain text. T1: the writer's call. T6 and T8 cannot be judged without material (F-18).
  Skeleton:    [a physical thing, named exactly — brand, model, or the one detail that makes it yours];
               [a habit, as a verb phrase with its time or place];
               [a person, by relationship or role + one identifying detail — not a name alone];
               [an idea or question you keep returning to, as a noun phrase];
               [a small, unglamorous thing no brochure would list]
  Real examples: none found for this prompt (searched: creative_forms.md §4, §7, §10; §10 records "no showcase essay,
               officer comment, or community report specific to it"). Nearest analogues:
               - CEG on USC's three-word question: "Get creative. These don't all need to be adjectives.", sample
                 answer "Hungry, Petrichor, Retrouvailles" (PRACTITIONER, READ-WF, verified 2026-09-23 per §0;
                 https://www.collegeessayguy.com/blog/university-southern-california-usc-supplemental-essays)
               - CEG, "Mulan" as a one-word answer to "3-5 words to describe you" (PRACTITIONER, READ-WF; §11 does not
                 say which CEG page this is — F-10)
               - three Brown ED admits used a phrase instead of three adjectives (COMMUNITY, self-reported; outcomes
                 are the posters' claims; no URL in §11 — F-10)
  Evaluation:
    Words/chars:   0 scaffolding. 50 content words, about 10 per item; 45–50 if hand numerals are counted.
    Portal:        survives as written (inline, comma/semicolon separated)
    Answers the prompt? yes. The five items are the literal answer; each must visibly be "a thing important to you".
    Evidence:      moderate (4.5: "moderate (practitioner and community)"). None for this prompt.
  Fails when:  the variety is performed (items chosen to look eclectic instead of because they matter), or one item is
               a joke that doesn't also answer; "Terse only works if it still tells the reader something" (4.5).
```

```
HUMOR AS THE CARRYING VOICE  ·  risk: LOW (conditional)  ·  catalog: creative_forms.md §4.3
  Move:        A plain list where the specifiers carry the writer's actual comic register. The items are sincere and
               the phrasing is funny.
  Why it can work here: Stanford asks for "genuine voice", and for a funny writer, funny is the genuine voice (Yale's
               Hannah: "if you are someone who's funny and light, then the voice that comes through in your essay
               should be funny and light", OFFICIAL, READ). T7: humor rides inside the specifiers, so no extra words.
               T10: plain text. T1: decisive here, and the writer's call. 4.3's evidence is "strong, but only for
               writers who are funny."
  Skeleton:    [item 1: plain noun] + [a specifier with the writer's own deadpan or exaggeration];
               [items 2–4: plain, sincere, specific];
               [item 5: plain noun] + [a specifier that lands the tone]. Keep it to 1–2 funny items (inference).
  Real examples: none for this prompt. Catalog: JHU "Intercom Enthusiast" (2016), "On Potatoes" (2020), "A Study in
               Ambidexterity" (2017), "Growing Strawberries in a High School Locker" (2016). A commentary credits what
               the humor reveals: "Most importantly, it gave us insight into his personality" (OFFICIAL, READ-WF;
               4.3 doesn't say which essay — F-12). https://apply.jhu.edu/hopkins-insider/ + intercom-enthusiast/ ·
               on-potatoes/ · a-study-in-ambidexterity/ · growing-strawberries-in-a-high-school-locker/.
               All are full essays, not 50-word lists.
  Evaluation:
    Words/chars:   0 scaffolding; comic specifiers cost 2–6 words where used (inference), inside the ~10-per-item ceiling.
    Portal:        survives as written
    Answers the prompt? yes, as long as every item is still a real answer. A joke item that stands in for an answer is
                   the Georgia Tech failure: "If you are tempted to not spend time on the answer or to get a little
                   snarky in your response, don't." (OFFICIAL, 2019;
                   https://sites.gatech.edu/admission-blog/2019/07/12/will-saying-im-a-blueberry-get-me-into-college-supplemental-essays-101)
    Evidence:      strong, but only for funny writers (4.3); none at this prompt or scale
  Fails when:  the writer isn't funny (CEG: "If you're not funny, no need to start now."); snark; outrageousness
               mistaken for risk (Parke Muth: "being outrageous is different than taking a risk").
```

Not selected at LOW: 4.1 organizing conceit (at 50 words "the image only" *(S)*; one image carrying five items becomes a
MEDIUM frame) · 4.2 sideways-but-literal (for a mandated list, "an answer read sideways" is a HIGH move under §3; see
HIGH-3) · 4.4 riddle device (50: "a riddle line only" *(S)*, and a riddle line would use up one of the five slots).

### MEDIUM — structural device

```
ORDERED LIST WITH A TURN  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.11 (+ §3 mandated-list MEDIUM row)
  Move:        The order carries meaning. Items escalate (small → large, private → public, concrete → abstract), or
               four share a register and the fifth breaks it and recasts the first four.
  Why it can work here: §3 MEDIUM: "Arrangement carries meaning: order, juxtaposition, a turn in the last item";
               Kolongowski: "Their story lives in the rhythms, in the juxtapositions, in the crescendos." T3: a list
               prompt's only structural variable is order, so the form echoes the task exactly. T4: still an obvious list.
               T7: order costs nothing. T5: the turn must connect back to the four (F-18). T1: writer's call.
  Skeleton:    items 1–4: [four concrete things in one register, ordered from ___ to ___]
               item 5: [the turn: one thing of a different kind or scale that changes how the first four read]
  Real examples: none for this prompt or at 50 words (§10). Craft sources: Jill Kolongowski on list essays
               (CRAFT, READ, https://brevity.wordpress.com/2021/11/05/of-list-essays/); John Proctor, "the force that
               drives the essay is at least as much concept as plot" (CRAFT, READ,
               https://numerocinqmagazine.com/2010/05/13/7-things-i-learned-from-reading-15-list-essays/). At
               application scale: Hamilton, Alexander Wear '18, "Life from Seven Feet Up", headed "I learned…" lessons
               (OFFICIAL showcase, READ, https://www.hamilton.edu/admission/apply/2014-essays-that-worked). That is a
               full essay, not a 50-word list.
  Evaluation:
    Words/chars:   0 scaffolding. If item 5 runs 12–18 words, items 1–4 share 32–38 (8–9 each) (inference).
    Portal:        survives inline. A vertical list would need line breaks, which are undocumented in short-answer
                   boxes, so do not depend on them.
    Answers the prompt? yes. The turn item must still be a thing important to the writer, not a punchline about the
                   other four.
    Evidence:      moderate (4.11: "craft strong, showcase moderate"). Nothing at this scale.
  Fails when:  the order is arbitrary, so the reader can't see it (T4). Or it's an inventory: "the assumption that the
               list itself is interesting. It almost never is." (Mark Moody glossing Harry Bauld, SECONDHAND,
               https://www.msquaredcounseling.com/post/on-harry-bauld-and-the-college-essay)
```

```
REPEATED FRAME  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.11 (anaphora, Brainard) / §4.4 (repetition device)
  Move:        Each item opens with the same one- or two-word frame, so the repetition becomes a rhythm and the
               last return can shift.
  Why it can work here: 4.4 (repetition helps "the reader see exactly what she hears"). T3: only if the frame
               itself says something about how the writer values things (inference). T7 is the binding test at 50
               words: see arithmetic. T10: text-only, so it survives. T1: writer's call.
  Skeleton:    [frame word(s)] [item 1]; [frame] [item 2]; [frame] [item 3]; [frame] [item 4];
               [frame, altered once] [item 5]
  Real examples: none for this prompt. Joe Brainard, *I Remember* (anaphora; named in 4.11; no tag or URL in §11,
               F-10). Connecticut College, Nancy Owusu '28, repeats her own name as a barrage of household commands
               (OFFICIAL showcase, READ, https://www.conncoll.edu/admission/apply/essays-that-worked/nancy-owusu-28/).
               That is a full essay.
  Evaluation:
    Words/chars:   frame cost 5 × 1–3 words = 5–15 words (10–30% of 50); content 35–45, 7–9 per item. At a 3-word
                   frame the scaffolding takes nearly a third of the budget, which fails T7 (inference).
    Portal:        survives as written
    Answers the prompt? yes, if the frame doesn't turn the items into sentences about something else
    Evidence:      weak at this scale (craft and a full-length showcase only; 4.4 grades the device "moderate" overall)
  Fails when:  "the device is the whole idea" (4.4); the frame is longer than the items; a list-of-sentences that
               becomes a mini-essay.
```

Not selected at MEDIUM: 4.6 stamped segments, 4.7 braid, 4.8 refrain, 4.9 hybrid insert, 4.10 delayed reveal, 4.12
reverse chronology (all "50: no" in the catalog *(S)*). Juxtaposition is folded into MEDIUM-1.

### HIGH — format break or sideways reading

Stanford does not lock the format the way Columbia does (§3: "HIGH is off the table where the school locks the format"),
and the portal can carry inline text, so HIGH options are shown with thin evidence stated.

```
LIST AS VERSE  ·  risk: HIGH  ·  catalog: creative_forms.md §4.21 (poem; "≤50 or an insert" row)
  Move:        The five items set as five short lines of verse, with rhythm or sound doing some of the meaning.
  Why it can work here: 4.21 scale: "≤50 or an insert: the only place Yale's officers report it working (S from
               Yale's 'shorter pieces')". T4: recognizable only if the lineation survives, or a slash fallback reads
               as verse. T7: 0 words of scaffolding. T0: what does the verse say that a plain list can't? The writer
               must be able to answer that. T1: writer's call; T2 (name why you chose it) applies strongly.
  Skeleton:    [item 1, 2–6 words] / [item 2] / [item 3] / [item 4] / [item 5, the line that lands]
               (sound or rhythm links: [repeated consonant | parallel syntax | a rhyme you didn't force])
  Real examples: none for this prompt. Yale, Episode 17 (OFFICIAL, READ,
               https://admissions.yale.edu/posts/2021-05-26-episode-17-the-choices-game): John, "for some of the
               shorter pieces, there have definitely been some", and also "choosing to write in poem format should not
               be your ticket to standing out"; Hannah, "Downvote." These are Yale officers on Yale's pieces, not
               Stanford's stance. Community: a Tufts extracurricular-essay poem admit (u/admissionsmom's son) and
               two why-Brown poems rejected (COMMUNITY, self-reported; no §11 URL).
  Evaluation:
    Words/chars:   0 scaffolding; about 45–50 content words. Slashes may or may not count as words (range).
    Portal:        needs a plain-text fallback. Lineation is "RISKY everywhere" (§6/4.21) and single line breaks in
                   short-answer boxes are undocumented, so use " / " inline or accept that the lines may collapse.
    Answers the prompt? yes, if the five things are still countable. Name them as nouns, not imagery about them.
    Evidence:      weak for this use. 4.21's own grade is "official negative, with a short-piece exception", and that
                   exception comes from another school.
  Fails when:  the energy goes "into the structure of the response" and away from the content (Yale's Hannah, 4.21);
               the verse obscures what the five things are; the lines collapse in the portal and it reads as a
               run-on.
```

```
MICRO-SHELL (BORROWED LIST GENRE)  ·  risk: HIGH  ·  catalog: creative_forms.md §4.13 (50: "micro-shells only")
  Move:        The five items are presented inside a borrowed list form that comments on why they matter: a label, a
               packing or inventory list, a classified ad.
  Why it can work here: 4.13 scale: "50: micro-shells only (a label, a classified ad) (S)". A list-genre shell
               stays a list, so it still does the assignment (inference). T4 is decisive: Adrian, "Make your form
               easily recognizable—otherwise you'll just baffle your reader" (CRAFT, READ). T3: the shell must imply
               why these five, e.g. by necessity or by what you'd keep (inference). T1: writer's call.
  Skeleton:    [genre label, 1–4 words, instantly recognizable]:
               [item 1]; [item 2]; [item 3]; [item 4]; [item 5]
               [optional closing shell line, 2–5 words, in the genre's own voice]
  Real examples: none for this prompt. Brenda Miller's definition: "Hermit crab essays adopt already existing forms as
               the container for the writing at hand, such as the essay in the form of a "to-do" list…" (CRAFT, READ,
               https://brevitymag.com/craft-essays/the-shared-space/). Community short-answer twists that "still
               answer the question": a QuestBridge short answer as an obituary, Brown's "teach a class" as a mock
               course-catalog entry (COMMUNITY, self-reported; outcomes are the posters'; §7 synthesis #1 is SKILL
               SYNTHESIS, weak; no §11 URL).
  Evaluation:
    Words/chars:   header plus closing = 3–9 words (6–18%); 41–47 left for five items, 8–9 each (inference).
    Portal:        survives as written if kept inline. Don't depend on a vertical layout.
    Answers the prompt? only if the shell doesn't displace the items. The five things must be plain and countable
                   inside it.
    Evidence:      weak (community anecdote plus the catalog's scale synthesis; 4.13's "3 of 64 JHU essays" are
                   full-length essays and don't transfer to 50 words)
  Fails when:  "cute pets" (Rebecca Fish Ewan: hermit crab essays "without proper care, are at risk of devolving
               into cute pets", CRAFT, READ); the shell is chosen first and the items are made to fit it (T6).
```

```
SELF-AWARE FIFTH ITEM  ·  risk: HIGH  ·  catalog: none. creative_forms.md §3 mandated-list HIGH row ("an item that
                                           comments on the list") has no §4 entry (F-8)
  Move:        Four plain items; the fifth is a real thing that also comments on the act of choosing or on what the
               other four have in common.
  Why it can work here: §3 HIGH names the move. T3: the prompt is about selection, so an item about selection echoes
               it (inference). T9 is the whole risk. T1: writer's call.
  Skeleton:    [item 1]; [item 2]; [item 3]; [item 4];
               [item 5: a concrete thing that is ALSO the thread through 1–4 — named plainly, not explained]
  Real examples: none found (searched: creative_forms.md §3, §4, §7, §10)
  Evaluation:
    Words/chars:   items 1–4 about 28–36 words; item 5 about 10–16 (inference)
    Portal:        survives as written
    Answers the prompt? risk of reading as a non-answer. Item 5 must itself be "a thing important to you". If it is
                   only commentary, the list has four things. Penn's "page 217" chapter-title answer is the
                   warning (PRESS-QUOTED, a Penn officer via the *Christian Science Monitor*, 2000: "It was not a
                   hit"; https://www.csmonitor.com/2000/0208/p14s1.html).
    Evidence:      none
  Fails when:  item 5 is a meta-joke about the prompt (Georgia Tech: snark, "don't"); it explains the other four
               instead of being a fifth.
```

Not selected at HIGH: "phrases instead of items" (§3 HIGH: a single phrase makes the five hard to count, T9; §4.5 files
the same move as LOW, F-1) · 4.14 non-human narrator, 4.17 dialogue/script, 4.19 footnotes (catalog "50: no" *(S)*) ·
4.16 second person ("50: rarely") · 4.18 abecedarian/acrostic (see §3 table) · 4.20 questions (one UChicago self-report,
weak; questions are not "things", T9) · 4.22 typographic (do not use).

## 3. Tried and failed (keep; do not re-propose)

| Pattern | Verdict | Why (source or reasoning) |
|---|---|---|
| A lead-in sentence before the list ("Five things that matter to me are…") | REJECTED for this prompt | T7: a 5–8-word lead-in spends 10–16% of 50 words restating the prompt (inference) |
| An inventory of items any applicant could list | REJECTED | §8 "My Favorite Things": "the assumption that the list itself is interesting. It almost never is." (Moody on Bauld, SECONDHAND); §3 LOW: "nothing any applicant would list" *(S)* |
| Pipe "\|" as the separator | REJECTED | Common App: the pipe "causes portions of your responses to disappear" (OFFICIAL, July 2026, §6) |
| Styling-dependent list (bold labels, emoji, a table, color) | REJECTED | §6: short-answer boxes are plain text; emoji garble; §4.22 "do not use in essay boxes" |
| Acrostic (the five items' initials spell a word) | REJECTED | needs line-initial position or bold to be visible; line breaks and bold are undocumented in short-answer boxes (§6, §4.18; inference extending the UC rule) |
| Mock-refusal or snark ("Only one thing: …") | REJECTED | Georgia Tech 2019: "don't" (OFFICIAL); T9: not five things |
| Playing all of Stanford's short questions for laughs or forms | REJECTED (portfolio) | §8 "stack of jokes" (COMMUNITY, weak); a UVA admissions dean: "if a student wants to do something wacky or funny with one of them, there are two others to balance that out" (OFFICIAL-ADJACENT, 2007, https://uvaapplication.blogspot.com/2007/01/on-taking-risks.html). Take the risk in one piece at most |

## 4. The plain-prose test (for whichever option the writer picks)

Because the list is mandated, apply Q1 to the **departure from a plain list**, not to the list itself (cliché #21:
"A form the prompt *requires* is never this arc").
1. **What does the bend say that a plain list can't?** If nothing, it is costume (cliché taxonomy #21). (T0 is this
   skill's own test, not a quoted source.)
2. **Is it true to the writer?** (T1: humor from someone funny, verse from someone who writes it.) **Does it echo
   the subject?** (T3: selection.)
3. **Does the answer still contain five countable things, each important to you?** Point to them. (T9)
4. **Does it survive the portal and the limit?** Inline, no pipe, no styling, 50 words by the portal's own counter.
   (T7, T10; §6.)
5. **Is there still a why?** Every JHU commentary that praised a form credited what it revealed (§1.2). College Essay
   Guy's "So what?" test (`craft_frameworks.md` §1.4) applies to each item.

---

## MENU 2

```
FORMS MENU — "PIQ 1: Leadership" · University of California (campus not named) · 350 words

PROMPT (verbatim):   "Describe an example of your leadership experience in which you have positively influenced
                     others, helped resolve disputes or contributed to group efforts over time."
                     verified: as given by user. No skill file carries PIQ 1's text: university_guidance.md's UC entry
                     (OFFICIAL, verified 2026-08-23) records only the structure, "8 questions, answer any 4, max 350
                     words each". The one-fetch refresh in context_analyst task 2b / source_refresh.md step 5 was
                     not run (no web access in this test).
FORM REQUIRED?:      no: any form is the applicant's choice
LIMIT:               max 350 words; minimum: none documented in any skill file. Counted how: "UC PIQ | 350 words"
                     (§6); counting method undocumented, so trust the portal's counter.
PORTAL:              UC application
FORMATTING SURVIVES: PLAIN ASCII. UC: paste "in plain text (ASCII)" and "make sure no odd characters or line breaks
                     have appeared" (OFFICIAL, §6). A practitioner reports bold and italic are not saved. Plain-text
                     test (§6): any non-ASCII character becomes "?" on UC, so use straight quotes, and "--" or a hyphen
                     instead of an em dash. Line breaks, even between paragraphs: undocumented. Any structural marker
                     must be carried by WORDS, not layout.
SCHOOL STANCE:       "the UC admissions reader is not looking at style or structure in your response"; "Use 'I' and
                     'my' statements" (UC, OFFICIAL, 2026 PIQ guide, creative_forms.md §5;
                     https://admission.universityofcalifornia.edu/_blocks/how-to-apply/first-year-applicants/new-ada-fy-piq.pdf).
                     Also OFFICIAL (university_guidance.md, verified 2026-08-23): "Use specific, concrete examples to
                     support the points you want to make."; do not make it "a list of accomplishments, activities,
                     awards or work"; "All questions are equal."
                     §5 grading rule 2 (S): "A LOW framing risk is fine; MEDIUM and HIGH forms are a fit finding."
                     personal statement: n/a
CERTIFICATION:       none, per ai_policy.md §4 (UC ceiling L2, not L0). UC's Statement of Application Integrity still
                     binds: "content and final written text must be their own", and "UC conducts regular screenings"
                     (OFFICIAL). Whether this counts as an "explicit AI-use attestation" under context_analyst task 3
                     is undefined (F-4).
WHAT THE PROMPT TESTS: evidence of influence on others: what you did, with whom, at what scale, over what time, with
                     what result (essay_type_rubrics.md #6: evidence-density 45%, directness 25%). The prompt's own
                     three routes are influence, dispute resolution, and sustained group contribution. UC's review
                     factor 10 names "leadership" (portal_specs.md, VERIFIED 2026-08-23).
```

*Header check:* the prompt was given, not inferred, but could not be verified. WHAT THE PROMPT TESTS is analytic. I did not pause (F-15, F-20).

## 1. The conventional target (always first)

Plain first-person prose ("I" and "my", as UC asks) that states the answer in the first sentence or two: the situation and
the influence. Then comes the evidence: specific actions, the number of people, how long, what changed for them. Then one
or two sentences on what the writer now does differently. Literary scene-setting that buries the evidence is a **defect**
here, even though it is a virtue in a personal statement (essay_type_rubrics.md #6). "Over time" is in the prompt, so
duration is part of the evidence. **This is the right call for UC.** UC's reader "is not looking at style or structure", so
every option below is measured by whether it adds evidence, never by whether it's interesting. *(inference)* Rough
allocation: answer 25–45 words, evidence 200–250, result and reflection 60–90.

## 2. Options by risk level

### LOW — fresh framing

```
SIDEWAYS-BUT-LITERAL: AN UNEXPECTED DIRECTION OF INFLUENCE  ·  risk: LOW  ·  catalog: creative_forms.md §4.2
  Move:        Answer exactly as asked, from an angle the pool rarely takes: influence without a title or authority
               (peer to peer, younger to older, newcomer to established group), or the prompt's less-chosen routes,
               "helped resolve disputes" and "contributed to group efforts over time".
  Why it can work here: the prompt text itself lists three routes and doesn't require a title (reading of the prompt,
               not a UC statement). The titled-role arc, "held a title → faced friction → learned lesson", is
               cliché_taxonomy.md #5, VERY HIGH frequency (JUDGMENT, an informed estimate; F-19). T9 is automatic
               because it is literal. T7: no scaffolding. T10: plain prose. T1: writer's call.
  Skeleton:    sentence 1–2: [the group] + [what you had no authority over] + [what you changed], plainly
               body: [the first action you took] → [how others responded] → [what you did next, with numbers or
               duration] → [the dispute or setback, if any, and how it resolved]
               close: [what the group does now that it didn't before] + [one line on what you learned to do]
  Real examples: none for UC PIQs. Pattern examples: a Penn applicant answered the dinner-guest prompt by polling her
               family and choosing them; the officer, "It was wonderful. I could taste the bean soup." (PRESS-QUOTED:
               a Penn officer via the *Christian Science Monitor*, 2000, READ, https://www.csmonitor.com/2000/0208/p14s1.html).
               A UChicago applicant divided humanity into tomato lovers and haters (OFFICIAL-ADJACENT, UChicago News
               2012, READ, https://news.uchicago.edu/story/uncommon-approach-yields-creative-college-essays).
  Evaluation:
    Words/chars:   0 scaffolding; the angle-naming sentence 15–30 words (4–9%) (inference)
    Portal:        survives as written
    Answers the prompt? yes. The first sentence must say how you "positively influenced others" in literal terms.
    Evidence:      moderate (4.2's grade). Nothing specific to UC or PIQs.
  Fails when:  "the angle replaces the answer" (4.2; §8 "page 217"). Or the angle becomes a humility pose with no
               evidence of influence, which scores zero on evidence-density.
```

```
LIGHT ORGANIZING CONCEIT  ·  risk: LOW  ·  catalog: creative_forms.md §4.1
  Move:        One concrete image or system from the activity (a shared object, a schedule, a tool the group used)
               appears once at the start and once at the close. It frames the evidence without replacing it.
  Why it can work here: §5 rule 2 (S): "A LOW framing risk is fine" at UC. T3: the image should come from the
               group's own work. T7: keep it to two brief appearances. T10: prose. T1: writer's call.
  Skeleton:    sentence 1: [the object or system], stated plainly, + the answer sentence
               body: evidence as in the conventional target; the image does NOT return mid-paragraph
               close: [the object or system, changed or used differently now] + [the result for others]
  Real examples: none for UC PIQs. JHU "My Spotify Playlist" (Class of 2027): "reflects on special memories through
               the creative lens of Spotify playlists" (OFFICIAL, READ-WF,
               https://apply.jhu.edu/hopkins-insider/my-spotify-playlist/). "At least 12 of JHU's 57 conventional
               showcase essays work this way" (4.1). These are JHU personal statements, not UC evidence documents.
  Evaluation:
    Words/chars:   image cost 20–40 words (6–11%); above ~15% it starts crowding out evidence (inference, rubric #6)
    Portal:        survives as written
    Answers the prompt? yes, if the answer sentence sits beside the image in sentence 1 or 2
    Evidence:      strong in general (4.1); none transferable to UC, whose reader "is not looking at style or structure"
  Fails when:  "the conceit outruns its accuracy and the person disappears behind it" (4.1; cliché #11), or it grows
               into literary scene-setting that buries the evidence (essay_type_rubrics.md #6: a DEFECT at UC).
```

Not selected at LOW: 4.3 humor (UC OFFICIAL "Show us your personality — just as you would in real life" supports a funny
writer being funny, but it costs evidence words. Writer's call; strong evidence only for funny writers) · 4.4 riddle opener
(withholds the answer at the top of an evidence document) · 4.5 micro-forms (native only to ≤50-word prompts).

### MEDIUM — structural device

*UC note, applying to both blocks:* §5 rule 2 (S) makes MEDIUM "a fit finding" at UC. They are shown because each one can
carry evidence rather than style. Neither earns credit for structure.

```
TIME-STAMPED SEGMENTS  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.6
  Move:        Three or four short prose segments, each opened by a word-carried time stamp (a date, a week number,
               a meeting count, a season). The stamps carry the "over time" arc without a sentence of explanation.
  Why it can work here: "over time" is in the prompt, so the stamps ARE evidence of duration. That passes T3 (the form
               echoes the subject) and arguably earns its place at UC (inference). 4.6: "the marker carries the arc
               without a sentence of explanation." T10: the stamps are words, so they survive if blank lines collapse.
               T5: each segment must show the group changing, not just the writer doing more. T1: writer's call.
  Skeleton:    [stamp 1: e.g. month/week/count]. [the group's starting state + the first thing you did] + the answer
                 sentence, here or in segment 2
               [stamp 2]. [what you did next + how others responded — a number, a name-by-role, a change]
               [stamp 3]. [the dispute or setback + what you did about it]
               [stamp 4, optional]. [where the group is now + what you learned to do]
  Real examples: none for UC PIQs. Hamilton, Claire Lazar '26: "I'm 6." / "I'm 9." … "I'll be 18." (OFFICIAL showcase,
               READ, https://www.hamilton.edu/admission/apply/college-essays-that-worked). Hamilton, Zane Glauber '12:
               a clock-stamped day (OFFICIAL showcase, READ, https://www.hamilton.edu/admission/apply/2008-essays-that-worked).
               JHU "In Pursuit of the Sublime" (2016): "Goal: 40,000." then "Status: N" counts, ending "Not counting
               anymore"; commentary: "The unique format of her essay suited the content" (OFFICIAL, READ-WF,
               https://apply.jhu.edu/hopkins-insider/in-pursuit-of-the-sublime/).
  Evaluation:
    Words/chars:   3–4 segments (inference, between the catalog's "250: 2–3" and "650: 3–5"); stamps 2–5 words each =
                   6–20 words (2–6%); 80–110 words per segment
    Portal:        survives as written (the stamps are text); don't depend on blank lines
    Answers the prompt? only if one sentence states the influence literally: "I [action], and [who] [changed how]".
                   Put it in segment 1 or 2, not the last. Readers who "read the first and last paragraphs" (Georgia
                   Tech, §1.7) are the risk.
    Evidence:      moderate–strong (4.6), all from full-length private-school showcase essays, none from PIQs
  Fails when:  "the segments are a tour of accomplishments (T8, Talbot)". At UC that is also the published dislike, "a
               list of accomplishments, activities, awards or work" (OFFICIAL). Or "the gaps don't connect (T5)".
```

```
REFRAIN THAT CHANGES MEANING  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.8
  Move:        One short line the group actually used (a question, a rule, a phrase) appears two or three times. Its
               last return means something different, and that difference is the evidence of influence.
  Why it can work here: T3: if the writer's influence changed how the group used the line, the refrain is the evidence
               (inference). 4.8: "the last return should change meaning". T7: the line is short. T10: prose. T1: writer's call.
  Skeleton:    open: [the line, as the group said it at the start] + the answer sentence
               middle: evidence paragraph(s) — actions, scale, duration
               [the line again, when it first shifted] + [what caused the shift, i.e. what you did]
               close: [the line, meaning something new] + [the result for others]
  Real examples: none for UC PIQs. Hamilton, Heqing "Amy" Zhang (Class of 2018): one-line letters to and from the future,
               the last one "Hello, future? I'm not afraid. Love, Amy." (OFFICIAL showcase, READ,
               https://www.hamilton.edu/admission/apply/2014-essays-that-worked).
  Evaluation:
    Words/chars:   line 5–12 words × 2–3 returns = 10–36 words (3–10%) (inference; catalog: "250: one return")
    Portal:        survives as written; straight quotes only (ASCII)
    Answers the prompt? only if … a plain sentence outside the refrain states the influence. The refrain alone is style.
    Evidence:      moderate (4.8), none from PIQs
  Fails when:  "the refrain is decoration with no turn" (4.8), or the line is invented for the essay rather than taken
               from the group (T6; that also risks the facts-ledger rule if a draft is later rebuilt around it).
```

Not selected at MEDIUM: 4.7 braid (craft only, no showcase; two strands in ~350 words halve the evidence budget) · 4.9
hybrid insert (lists and lineation RISKY, and UC warns about line breaks) · 4.12 reverse chronology (weak; resists the
forward result "over time" asks for) · 4.10 delayed reveal and 4.11 list spine (in the §3 table).

### HIGH — format break or sideways reading

*UC note:* §5 rule 2 (S): HIGH is "a fit finding". The template shows HIGH unless the portal or stance rules it out, while
creative_forms.md §3 offers HIGH only when the stance "allows it" (F-2). I followed the template. The one block below is
shown with that conflict stated.

```
GROUP GLOSSARY  ·  risk: HIGH  ·  catalog: creative_forms.md §4.18 (glossary) / §4.13 (borrowed-document form)
  Move:        Three or four entries, each a term the group used or that the writer introduced and the group adopted,
               followed by prose showing what the writer did around that term. If the group adopted the writer's
               vocabulary, the glossary is itself evidence of influence.
  Why it can work here: 4.18: "a 3–5-entry glossary is feasible (compare JHU 'Korean Sticky Notes', 4.13)". T3: shared
               language is one visible trace of influence (inference). T4: a "Term: definition." line is instantly
               recognizable. T10: the head terms are words and survive ASCII and collapsed breaks. UC's "Use 'I' and 'my'
               statements" can still hold inside each entry. T1 and T2: writer's call.
  Skeleton:    [one plain sentence: the group, your role or lack of one, what you changed] (the literal answer)
               [Term 1]: [its meaning to the group at the start]. [what you did] + [who/how many responded].
               [Term 2]: [a term you introduced or redefined]. [the dispute or effort it resolved, with duration].
               [Term 3]: [what the group calls it now]. [the result for others] + [what you learned to do].
  Real examples: none for UC PIQs. JHU "Korean Sticky Notes" (Class of 2028): five Korean words with glosses as section
               heads, "Hal-in: Discount." (OFFICIAL, READ-WF, https://apply.jhu.edu/hopkins-insider/korean-sticky-notes/).
               Dinty W. Moore's alphabetized essay: the alphabet's "arbitrary certainty" supplies coherence (Charles
               Green, CRAFT, READ, https://assayjournal.wordpress.com/2018/01/07/charles-green-on-dinty-w-moores-son-of-mr-green-jeans-a-meditation-on-fathers/).
  Evaluation:
    Words/chars:   head terms 3–16 words (1–5%); answer sentence 20–30; 3–4 entries of about 75–100 words (inference)
    Portal:        survives as written (colons and words only; no bold on head terms, since bold is not saved)
    Answers the prompt? only if the opening plain sentence carries the literal answer. Glossary entries define words,
                   and the influence must be stated.
    Evidence:      weak (one showcase glossary, at a school that praises form when content earns it; nothing from
                   PIQs; UC "is not looking at style or structure")
  Fails when:  the terms become a costume over thin evidence (cliché #21; T0: at UC, ask what would be lost as plain
               paragraphs); the entries turn into a tour of titles or projects (T8; UC's "list of accomplishments");
               the shell is picked first (T6).
```

Withheld at HIGH: 4.14 non-human or object narrator and 4.16 second person. UC's published stance rules them out ("Use 'I'
and 'my' statements", OFFICIAL; 4.14's own caution). Layout-dependent shells from 4.13 (recipe steps, test, lab-report
headings, script) are also withheld because the portal is plain ASCII and UC warns about line breaks. Not selected: 4.20
an essay of questions (one UChicago self-report, weak; questions delay the evidence). 4.22 typographic: do not use, and
UC reviews no unsolicited material (4.22's statement, not a UC quote). Letter, poem, script, footnotes and acrostic are in the §3 table.

## 3. Tried and failed (keep; do not re-propose)

| Pattern | Verdict | Why (source or reasoning) |
|---|---|---|
| Self-chosen letter (to the team, a teammate, a successor) | REJECTED | Yale officers, 2020 (OFFICIAL, §8/4.15): Hannah, "just a little too gimmicky"; Mark, "It just often doesn't use the space very well." T7 at 350 words; UC grades evidence, not form |
| Third-person opening with a "that was me" twist; object narrator; second person | REJECTED | UC: "Use 'I' and 'my' statements" (OFFICIAL); Yale's Mark: "it doesn't quite work because I always know that it's you" (OFFICIAL, 2020); Vanderbilt 2008 on the second-person God conversation (OFFICIAL, dated) |
| List or catalog spine of roles, projects or wins | REJECTED for this prompt | UC: not "a list of accomplishments, activities, awards or work" (OFFICIAL); T8 (Talbot: "trying to convince me"); list layout needs line breaks UC may alter (§6) |
| Delayed reveal (influence withheld to the end) | REJECTED for this prompt | essay_type_rubrics.md #6: framing that buries the evidence is a DEFECT for PIQs; 4.10 "250: marginal" *(S)*; Georgia Tech's first-and-last-paragraph readers (§1.7) |
| Poem, screenplay/dialogue, text thread, footnoted essay | REJECTED | scale: 4.17 and 4.19 "250 and 50: no", 4.21 "250: rarely" *(S)*; UC ASCII (no emoji, no superscripts, no centering); CEG: dialogue "can take up a good chunk of your word count without explicitly saying anything about who you are" |
| Acrostic carried by bold letters, or any styling | REJECTED | "breaks on UC" (4.18, §6) |
| Reading "leadership" as being led, or as followership alone | REJECTED (inference) | T9: the prompt asks how *you* "positively influenced others"; Penn's "page 217" non-answer (PRESS-QUOTED) |
| "The true meaning of leadership" lesson stated in the abstract | REJECTED | cliché_taxonomy.md #5 (JUDGMENT): "Lesson is asserted, transferable to any applicant; title does the work"; salvage = "the moment of actual cost … shown not concluded" |

## 4. The plain-prose test (for whichever option the writer picks)

1. **What does the form say that plain prose can't?** If nothing, it is costume (cliché taxonomy #21). At UC, add:
   does the form carry *evidence* (duration, adoption, change) or only style? UC's reader "is not looking at style
   or structure". (T0 is this skill's own test, not a quoted source.)
2. **Is the form true to the writer?** (T1) **Does it echo the subject?** (T3: time, shared language, a changed phrase.)
3. **Does one sentence still answer the prompt literally?** Point to it, and keep it in the first two sentences. (T9)
4. **Does it survive the portal and the limit?** ASCII only, no styling, markers carried by words, 350 by UC's counter.
   (T7, T10; §6 and the arithmetic above.)
5. **Is there still a why?** Every Johns Hopkins commentary that praised a form credited what it revealed (§1.2). College
   Essay Guy's "So what?" test (`craft_frameworks.md` §1.4) applies inside any form.

---

# Friction log

Ordered by how much each item changed or endangered the output. File and section given for each. "Judgment call" = the
skill was silent and I had to decide.

## Contradictions (the skill says two different things)

**F-1. The same move gets two risk levels.** `creative_forms.md` §3 mandated-list table puts "phrases instead of items"
at **HIGH**. §4.5 files the same move (a phrase instead of three adjectives; "Mulan"; the Brown three-word admits) as
**LOW (native)**, for the "describe yourself in three words" question, which §3 itself names as a prompt-mandated form. A
menu for any mandated micro-prompt has to pick one; I followed §3 (the template says mandated levels come from §3) and
left the conflict visible.

**F-2. Opposite defaults for showing HIGH.** `templates/forms_menu_template.md` §2 HIGH: "Withhold a HIGH option only
when the portal cannot carry it (§6) or the school's published stance rules it out (§5). Otherwise show it." In
`creative_forms.md` §3 the ladder's HIGH row says "Offer only when T1–T4 look passable, the portal can carry it (§6),
**and the school's stance allows it** (§5)." One is opt-out, the other opt-in. This decided the UC menu, where the stance
("not looking at style or structure") neither allows nor forbids. Also, §3 requires T1 to look passable, but in forms mode
T1 is always "the writer's call" (craft reader, template), so §3's precondition can never be met in a general menu.
Taken literally, §3 withholds every HIGH option in every general menu.

**F-3. "Fit finding" is undefined in forms mode.** `creative_forms.md` §5 grading rule 2: at UC "MEDIUM and HIGH forms
are a fit finding." Forms mode has "No ratings, no verdict" (template) and no findings section. Does a fit finding mean
show with a warning, demote, or withhold? Judgment call: I showed them with a UC note on each level.

**F-4. Which regimes are "certification-bound" is undefined.** `agents/context_analyst_agent.md` task 3 and SKILL.md
Checkpoint 6 make "schools with explicit AI-use attestations" certification-bound (banner armed, L0 per Checkpoint 12).
UC's Statement of Application Integrity is an explicit AI clause with screening (`ai_policy.md` §2), and Yale calls AI
content fraud. Yet `ai_policy.md` §4 gives UC **L2** and Yale **L1**, and §1 sends named schools with a policy to §4, not
§5. Read literally, task 3 makes UC certification-bound; ai_policy says it isn't. I followed ai_policy. The phrase needs a
definition, or the task-3 wording needs to become "competitions with authorship certifications".

**F-5. Mandated forms: the conventional target and LOW are the same thing.** Template §1 defines the conventional
target as "plain form with specific, voiced content". §3's mandated-list LOW row is "well-chosen plain items; the craft is
selection". For Stanford these are identical, and the template doesn't say how LOW should differ. Judgment call: I made
LOW the §4.5 "not the obvious category" move so it isn't a duplicate of §1.

**F-6. Template §4 Q1 misfires on mandated forms.** "What does the form say that plain prose can't? If nothing, it is
costume (cliché taxonomy #21)." Applied to Stanford's list, this calls the assignment itself costume, but `cliche_taxonomy.md`
#21 says "A form the prompt *requires* is never this arc", and §3 grades mandated forms on execution. The template never
tells you to point Q1 at the *bend*. I added a scoping line.

**F-7. WHAT THE PROMPT TESTS has no admissible source for Stanford** (template header; `creative_forms.md` §5 rule 4;
`school_tiers.md`). Rule 4 says `school_tiers.md` "sets how high the bar is, not what form is welcome". Yet the only Stanford
source for that is `school_tiers.md`'s reading-culture note, which is JUDGMENT and "superseded by `university_guidance.md`
wherever that file has an OFFICIAL entry". Stanford's OFFICIAL entry says nothing about what the list tests. So the field
must be filled from a source the skill ranks below one that is silent. It's workable, but the precedence rule gives no
answer.

**F-8. The block header can't be filled for mandated-form moves.** The template requires `catalog: creative_forms.md
§4.[n]` and "Name the catalog patterns you did not select … per level." For a mandated form the levels come from §3's
table, not from the catalog's intrinsic levels (4.2 is LOW in the catalog but "an answer read sideways" is HIGH under
§3; 4.11 is "native"). And §3's own HIGH move, "an item that comments on the list", has **no §4 entry**, so HIGH-3 had
to say "catalog: none". The per-level "not selected" line is also defined against catalog levels that don't apply.

**F-9. Two owners for SCHOOL STANCE.** Context analyst forms mode lists "the school's published stance on form (§5 …)"
as a card field. The template says "Institutional work (school stance …) goes into SCHOOL STANCE", and the
institutional agent says "your work fills the menu's SCHOOL STANCE line". This is harmless in a merged pass, but only one
of them should own it.

## Missing (the skill needed something it doesn't have)

**F-10. Examples without a §11 URL, although the template requires one.** Template: "carrying its tag …, its access
grade …, and its URL from §11", and "Every 'real example' traces to a catalog entry with a tag and a §11 URL". Gaps found
in this run:
- every COMMUNITY/Reddit report (the Brown three-word admits, "pickin.", the obituary and course-catalog short answers,
  the why-Brown poems, u/admissionsmom). §11 points to `research/creative-forms-2026-09/C_reddit.md`, which forms mode
  never says to open (and this test forbade)
- Joe Brainard *I Remember*, Carol Paik, Tyrese Coleman, Wallace's "Math 1619" (a book): no tag or URL
- CEG quotes in 4.3 and 4.5 aren't mapped to a CEG slug. I inferred the USC page for the USC quote, and could not map
  "Mulan" or "If you're not funny, no need to start now."
- Sherri Geller (4.3) has no tag
- Hamilton URLs are given as relative slugs (`/2008-essays-that-worked`), so I reconstructed the full paths

A community example can't satisfy the template's own rule, so either §11 carries the permalinks or the template exempts
COMMUNITY entries.

**F-11. Dangling cross-references in `creative_forms.md`.** (a) §3 table, note column HIGH: "Penn's thank-you note
written as a paper airplane, **§7**". §7 contains no such example, and §11 has no source for it. (b) §4.5: "*Community
(self-reported, §7):* three Brown ED admits … 'pickin.'". §7 contains neither report; its synthesis #1 mentions only "a
phrase for 'three words'". These cites can't be traced from the skill, which is the exact defect the source-integrity rules
are there to stop.

**F-12. Quotes not tied to a document.** 4.3's JHU line "Most importantly, it gave us insight into his personality" is
from one of four essays, but 4.3 doesn't say which one. Yale's Hannah on humor (4.3) and Mark's "propping up the gimmick"
(T7) aren't mapped to one of the four Yale episode URLs in §11. A menu can't give "its URL" for these.

**F-13. The scale columns don't cover UC's 350 words.** Every §4 entry gives scale at 650 / ~250 / ~50. UC PIQs are 350
(Stanford's short essays are 100–250, MIT's 100–200). Every UC block needed an interpolation (e.g., stamped segments "3–4",
between "250: 2–3" and "650: 3–5"), with no rule for which column governs. Judgment call: I leaned toward the 250 column.

**F-14. No minimum and no fallback wording.** Context analyst forms mode wants "the limit with its minimum and unit". No
skill file documents a UC PIQ minimum, and the template's `LIMIT: [min–max]` has no "none documented" form. Small, but
every UC run will make the same guess.

**F-15. Prompt verification when the prompt isn't in any file.** UC PIQ 1's text is in no reference. The template allows
"as given by user", but context analyst task 2b and `source_refresh.md` step 5 say "attempt one fetch". Forms mode says to
"Skip tasks 4–5", which implies 2b still runs, but it never says what happens when fetching is impossible or skipped.
Does "given but unverifiable" count as "inferred" (and so trigger a pause)? It's undefined. It matters because drift in a
prompt is, in the skill's own words, "a finding".

**F-16. Which context-analyst tasks run in forms mode?** "Skip tasks 4–5" implies tasks 1, 2, 2b, 3, 3b and 6 run. But
the short card has no field for essay type (task 1), tier (task 2), Phase 3 ceiling (3b) or word count (6, which has no
draft to count). Should their results be discarded, or folded into other fields? I computed the ceiling for the
certification line only.

**F-17. No marker for the run's own inference.** The template's only marker is the catalog's *(S)*. A large share of every
block is run-time reasoning: 350-word interpolations, word arithmetic, T3 judgments against a prompt, the "unexpected
direction" angle. It is neither sourced nor catalog synthesis. Unmarked, it reads as sourced. I added "(inference)". The
template should define a marker, because this is the same honesty problem *(S)* exists to solve.

**F-18. Several §2 tests can't be judged without material, but the craft reader says they can.**
`agents/craft_reader_agent.md` (forms note): "T3–T8 and T10 are judged against the prompt and the limit". T6 ("material
before shell") is a process test about the writer's material. T8 ("not accomplishments dressed in a form") depends on
content. T5 (coherence across gaps) needs gaps. All three can only be warnings in a general menu. Meanwhile T0 (the lead
test in the craft reader's own form diagnosis) and T2 are missing from that list. The note needs to say which tests are
judgeable, which are warnings, and which belong to the writer.

**F-19. Nobody owns topic-level cliché risk in forms mode.** The mode table assigns forms mode only to context_analyst,
craft_reader and institutional_reader. The authenticity reader and `cliche_taxonomy.md` are out, apart from #21 via the
template. For UC PIQ 1 the most useful warning is cliché #5 ("The true meaning of leadership/teamwork", VERY HIGH, and the
salvage condition "the moment of actual cost"), and it sits outside the mode's sources. I used it twice, labelled JUDGMENT,
and that stretches "use references only where pointed". Either add the authenticity reader's cliché lookup to forms mode
or state that the conventional-target line may cite `cliche_taxonomy.md`.

**F-20. The pause rule fires on every run.** Context analyst: "Pause for the user's correction only if a field was
inferred rather than given." WHAT THE PROMPT TESTS is always inferred, and FORMATTING SURVIVES is often "unknown". Read
literally, every forms run pauses. The rule should name which fields count (probably prompt, limit, portal, school).
SKILL.md Checkpoint 1 ("After Phase 0: present the Context Card") has no forms-mode exception either. The override lives
only in the agent file and the template.

**F-21. For a list prompt, the portal question the skill can't answer is the central one.** Stanford's list prompt
lives in a short-answer box that §6 says to "treat as plain text", with line breaks "not documented". Whether a vertical
list survives is the most important portal fact for this prompt, and the only guidance is scattered: 4.11 "RISKY if the
list needs one item per line", §6 "use blank-line breaks rather than single ones" (written for essays). There is no
stated default for list prompts. I defaulted to inline separators. A one-line rule ("list prompts in plain-text boxes:
inline, comma or semicolon, never pipe") would stop every run re-deriving it.

**F-22. Evidence grades aren't scale-aware, and evidence isn't school-matched.** §0 grades evidence without regard to
length, but nearly all the showcase evidence is ~650-word private-school essays. 4.13's "3 of 64 JHU essays" says nothing
about a 50-word micro-shell, and JHU's praise of form says nothing about UC, whose reader "is not looking at style or
structure". Judgment call: I downgraded evidence by scale and school and said so. The template's "Evidence: per §0, plus
the catalog's own wording" would otherwise copy "strong" onto blocks where it doesn't apply.

**F-23. "Tried and failed" assumes a session history.** Template §3 is "keep; do not re-propose", which implies
patterns tried in earlier turns. In a first run it's unclear whether to fill it from `creative_forms.md` §8, from
prompt-specific rejections, or leave it empty. I filled it from both.

**F-24. No slot for the rest of the school's set.** Stanford has five short questions plus three short essays, and UC is
"any 4" of 8 with "All questions are equal". The only stated portfolio logic (UVA's Dean J, §1.6) and the community
"don't have both an abstract PS and abstract supplementals" (§7) are about balance across pieces, but forms mode works on
one prompt and has no field for it. I put the caution in §3 as a portfolio row.

## Minor

- **F-25.** The certification line says "bound → no skeleton may be pre-filled", but in forms mode no skeleton may ever
  be pre-filled (template Rules: "General, not tailored"), so certification has no operational effect in forms mode. Say
  so, or give it one (e.g., STS Rule 10's disclosure note from `essay_type_rubrics.md` #8).
- **F-26.** The template's opening says "Source every example and statement from `references/creative_forms.md`", but the
  header necessarily draws on `university_guidance.md` (prompt, UC quotes), `ai_policy.md` (certification) and
  `essay_type_rubrics.md` / `school_tiers.md` (what the prompt tests). The rule should read "every *form* example and
  statement".
- **F-27.** The SCHOOL STANCE block's "personal statement: […]" sub-line has no instruction to omit it for non-PS prompts.
  I wrote "n/a".
- **F-28.** "READ-WF quotes carry 're-check before quoting' unless the verification pass confirmed them" (template) is
  dead code: §0 says the 2026-09-23 pass confirmed *every* READ-WF quote. Harmless, but it invites a pointless caveat.
- **F-29.** `university_guidance.md`'s `verified_on` is file-level (2026-08-23). The Stanford supplement entry has a URL
  but no per-entry `verified_on` in the format `source_refresh.md` says every sourced fact needs ("An entry missing any of
  them cannot be quoted to a user"). Read strictly, the Stanford prompt can't be quoted. I used the file-level date.
- **F-30.** The catalog's evidence wording doesn't map onto §0's four grades: "moderate–strong", "craft strong, showcase
  moderate", "official negative, with a short-piece exception", "strong, but only for writers who are funny",
  "practitioner", "craft only". The template asks for one of four plus the wording. Workable, but every run chooses
  differently.
- **F-31.** Checkpoint 2 (IRON RULE, independent reads) has no forms-mode carve-out in SKILL.md. The template's "One
  merged pass, not independent reader reports" overrides it silently. Add the exception to the checkpoint.
- **F-32.** 4.18: "An acrostic carried by bold first letters breaks on UC and depends on the reader's view on the Common
  App". That applies to long essays. For Common App *short-answer* boxes (plain text per §6) it simply breaks, and the
  entry doesn't say so. I extended it by inference.

## What worked (so the log is calibrated)

- The mandated-form ladder (§3) is the right idea and made the Stanford menu coherent. Without it the menu would have
  treated the list as the risk.
- §10's explicit "Stanford's 'List five things…': no showcase essay, officer comment, or community report" was the
  single most useful line. It made "none found" honest and fast.
- §5 rule 2 plus the UC quotes produced a sensible UC menu almost mechanically: LOW is fine, MEDIUM only where the
  structure carries evidence, and the non-"I" forms are withheld on a quotable ground.
- §6's plain-text test and the pipe ban gave concrete, checkable portal advice (ASCII "?" substitution, no "|") that a
  student can act on.

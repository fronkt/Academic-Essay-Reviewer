# Dry run: `college-essay-board` v1.3.0, `forms` mode

Run date 2026-09-23. Inputs: two prompts, **no applicant profile, no draft**. Sources used: only the skill's
files (`SKILL.md`; `agents/context_analyst_agent.md` (Forms mode section), `craft_reader_agent.md`, `institutional_reader_agent.md`;
`templates/forms_menu_template.md`; `references/creative_forms.md`, `portal_specs.md`,
`university_guidance.md`, plus `school_tiers.md`, `source_refresh.md`, `essay_type_rubrics.md`,
`cliche_taxonomy.md`, `craft_frameworks.md`, `ai_policy.md` where those files point). No web access. The
notes under `research/creative-forms-2026-09/` were **not** opened, because forms mode never routes there.

Conventions in these menus: `(S)` = SKILL SYNTHESIS (the skill's own rule, not anyone's published
position). Access grades from `creative_forms.md` §0 are carried after each tag (READ / READ-WF /
SECONDHAND). READ-WF quotes are marked "re-check before quoting" per §0. Word arithmetic in the
Evaluation blocks is this run's own calculation, not a sourced number.

---

# MENU 1

```
FORMS MENU — "Five things" short question · Stanford · 3–50 words

PROMPT (verbatim):   "List five things that are important to you."
                     Matches university_guidance.md, Stanford supplement specifics (OFFICIAL,
                     verified 2026-08-23; 31 days old, under the 90-day prompt threshold in
                     source_refresh.md, so no refresh was due). THE PROMPT REQUIRES A FORM (a list):
                     per creative_forms.md §3 it is "not a risk at all: it is the assignment", so it is
                     graded on execution only (SKILL.md anti-pattern 21).
LIMIT:               3–50 words. Counted how: "Words; counting method undocumented" on the Common App
                     (creative_forms.md §6). Whether typed numerals ("1.") count as words is undocumented.
PORTAL:              Common App (user-stated)
FORMATTING SURVIVES: Line breaks: not documented (the preview shows "how your essay will look to
                     colleges"). Styling: bold/italic/underline are documented for "the Common App"
                     (help center, 2024, OFFICIAL), but §6 does not say whether a member school's
                     short-answer field carries them, or whether every reader sees them (colleges get
                     "data exports and/or PDF generation"). Treat as UNKNOWN.
                     Characters: Windows-1252 survives (dashes, curly quotes, Western accents); emoji
                     and non-Latin scripts are garbled. NEVER the pipe "|": it "causes portions of your
                     responses to disappear" (OFFICIAL, July 2026).
                     Lists are "risky everywhere" (§6) if they depend on one item per line. A list
                     written inline, with commas, semicolons, or periods, passes the plain-text test (T10).
SCHOOL APPETITE:     "there are no right or wrong answers and you should allow your genuine voice to
                     come through" — Stanford, OFFICIAL, 2026–27 (§5; also university_guidance.md).
                     Stanford's §5 stance: "Prompts mandate forms (a list, a roommate note); voice over
                     correctness." No Stanford formatting instruction for this list was retrieved (unlike
                     Columbia's list, which is format-locked; Columbia's rule does not apply here).
WHAT THE PROMPT TESTS: What you choose and how you name it: values and personality at a glance, read as
                     part of "an integrated and comprehensive whole" (Stanford, OFFICIAL). Stanford names
                     "intellectual vitality" as a criterion. [school_tiers.md calls Stanford-style
                     prompts "an intellectual-vitality and personality test"; that is the skill's
                     JUDGMENT, not a Stanford statement.] Tier: T10 / hyper-selective.
```

## 1. The conventional target (always first)

Five items, each named **specifically** (a concrete noun or short phrase, not a value word), optionally
with a short clause where a stranger would not follow. Written inline, under 50 words. What "good"
looks like: a reader who knows nothing else could guess something true and particular about the writer
from the selection alone. Two sourced principles drive it: College Essay Guy's *"ordinary things with
extraordinary specificity, rather than extraordinary events with ordinary reflection"* (PRACTITIONER,
VERIFIED, `craft_frameworks.md` §1.4), and his micro-answer rule *"DON'T use Top 50 adjectives"*
(PRACTITIONER, READ-WF; `creative_forms.md` §4.5). Because the list form is mandated, **the conventional
target is already a form answer**. For most writers it is the right call. Every option below is a
variation inside the list or a light frame around it, never a replacement for it.
*(The skill defines no conventional target for this specific prompt. This paragraph is this run's
synthesis from §4.5 and `craft_frameworks.md` §1.4. See the friction log.)*

## 2. Options by risk level

> How the ladder is used here (judgment call, see friction log): the list itself is mandated, so it is
> not the risk. LOW/MEDIUM/HIGH measure how far an answer departs from a plain, well-chosen list.

### LOW: fresh framing

```
"THINGS," TAKEN LITERALLY  ·  risk: LOW  ·  catalog: creative_forms.md §4.2 + §4.5
  Move:        Answer with five specific nouns (objects, people, places, practices) where most
               applicants list abstract values.
  Why it can work here: It is a sideways-but-literal reading (§4.2): the prompt says "things", and
               concrete things carry the values without naming them. It passes T9 trivially (it is five
               things). T0 does not apply because the form is mandated. T1 (fit to this writer) is the
               writer's call; this run has no profile.
  Skeleton:    [a specific object you actually use or keep, named precisely]; [a named person or
               relationship, narrower than a category like "family"]; [a practice or routine, as a verb
               phrase]; [an idea or question, in your own words rather than a value word]; [something
               small or unexpected that is honestly important]
               — optional: a clause of about 8 words or fewer after any item a stranger would not
               understand.
  Real examples: none for this Stanford prompt (searched: creative_forms.md §4, §7, §8;
               university_guidance.md Stanford entries). Nearest: CEG on USC's "describe yourself in
               three words": "Get creative. These don't all need to be adjectives.", sample answer
               "Hungry, Petrichor, Retrouvailles"; a one-word answer "Mulan" ("Yeah, that Mulan.")
               (PRACTITIONER, READ-WF; re-check before quoting). Three Brown ED admits answered the
               three-word question with a phrase instead of adjectives (COMMUNITY, self-reported).
               Penn's dinner-guest answer that "chose her own family" ("It was wonderful. I could taste
               the bean soup.", Penn officer quoted in CSM, 2000, READ) shows the sideways-literal move
               at a different prompt.
  Evaluation:
    Words/chars:   No scaffolding. Five items at 1–4 words each use 5–20 words, which leaves 30–45
                   for optional clauses. The 3-word minimum is not a practical constraint.
    Portal:        Survives as written if inline with semicolons. Do not use one item per line or pipes.
    Answers the prompt? Yes. Count to five: exactly five items is the literal answer.
    Evidence:      moderate (practitioner + community; no official commentary on this prompt)
  Fails when:  The obvious word wins (CEG, "DON'T use Top 50 adjectives"). Or a list of objects gives no
               hint of why they matter: "Terse only works if it still tells the reader something"
               (§4.5, on a one-word answer an admissions officer recalled, COMMUNITY).
```

```
HUMOR AS THE CARRYING VOICE  ·  risk: LOW (conditional)  ·  catalog: creative_forms.md §4.3
  Move:        The list is written in the writer's real comic register, or one item lands as a
               true, funny beat among sincere ones.
  Why it can work here: Stanford's line is voice over correctness ("allow your genuine voice to come
               through"). §4.3 scales to "all" lengths. It passes T1 only if the writer is actually funny.
  Skeleton:    [four sincere, specific items] + [one item that is funny because it is true of you, placed
               where it lands, often 4th or 5th]; or all five in your ordinary funny register
  Real examples: none at this prompt or length (searched: §4.3, §7). At 650 words: JHU "Intercom
               Enthusiast", "On Potatoes", "A Study in Ambidexterity", "Growing Strawberries in a High
               School Locker"; commentary: "Most importantly, it gave us insight into his personality"
               (OFFICIAL, READ-WF, years not given in catalog; re-check before quoting).
  Evaluation:
    Words/chars:   No scaffolding. A joke that needs setup can cost 8–15 words, up to 30% of the budget.
    Portal:        Survives.
    Answers the prompt? Yes, if the funny item is also genuinely important. A joke item that is not
                   important is a non-answer for that slot (T9).
    Evidence:      strong at essay length (official commentary), but "only for writers who are funny"
                   (§4.3); none at 50 words
  Fails when:  The writer isn't funny: Yale's Hannah, "if you are someone who's funny and light, then the
               voice that comes through in your essay should be funny and light"; CEG, "If you're not
               funny, no need to start now." Or bathroom humor (Yale's Mark: "it shouldn't be in your
               essay"), or snark (Georgia Tech: "If you are tempted to not spend time on the answer or to
               get a little snarky in your response, don't." OFFICIAL, 2019).
```

### MEDIUM: structural device

```
ORDERED LIST WITH A TURN  ·  risk: MEDIUM (execution risk only; the list is native here)  ·  catalog: §4.11
  Move:        The order of the five carries meaning (small to large, public to private, oldest to
               newest…), and the fifth item re-reads the first four.
  Why it can work here: §4.11 marks list spines "native in list prompts". For Columbia's format-locked
               list, "the craft there is selection and juxtaposition only", and the same craft is
               available here. Jill Kolongowski: "Their story lives in the rhythms, in the
               juxtapositions, in the crescendos." (CRAFT, READ). Tests: T3 (the order echoes the
               subject), T4 (the ordering principle must be legible without explanation).
  Skeleton:    [item 1: the smallest / most public / oldest]; [item 2]; [item 3]; [item 4: moving
               along the same axis]; [item 5: the one that breaks or resolves the order, so the reader
               looks back at 1–4]
  Real examples: none at 50 words (searched: §4.11, §7). At essay length: Hamilton, Alexander Wear '18,
               "Life from Seven Feet Up", headed "I learned…" lessons (OFFICIAL showcase). Joe Brainard's
               I Remember (anaphora). Carol Paik, "A Few Things I Know About Softball" (Fourth Genre,
               2007) (CRAFT).
  Evaluation:
    Words/chars:   No scaffolding words. If the order is not self-evident, making it legible costs a
                   clause of 5–10 words.
    Portal:        Survives inline. Order does not depend on line breaks.
    Answers the prompt? Yes (five things).
    Evidence:      moderate (craft literature strong; official showcase at 650 words only; nothing at
                   50 words)
  Fails when:  It reads as an inventory. Counselor Mark Moody's gloss on Harry Bauld's "My Favorite
               Things" cliché: "the assumption that the list itself is interesting. It almost never is."
               (SECONDHAND). Also fails when the order is invisible and the turn goes unnoticed.
```

```
HIDDEN THREAD (RIDDLE LIST)  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.4 (with §4.11)
  Move:        Five items that look unrelated, with a thread the reader can find (or a closing
               phrase of 10 words or fewer that names it).
  Why it can work here: §4.4 records a riddle opener "listing unrelated objects", and Connecticut
               College's counselors wrote "We were curious to find out how all of those seemingly
               unrelated things were connected!" (OFFICIAL, READ). §4.4 scale at 50 words: "a riddle
               line only" (S). This whole answer is that one line. Tests: T4 and T5 (coherence across the
               gaps).
  Skeleton:    [thing 1]; [thing 2]; [thing 3]; [thing 4]; [thing 5], all tied to [one hidden
               connection] — optional closer: [≤10 words naming the connection]
  Real examples: none at this length (searched: §4.4, §7). At essay length: Connecticut College,
               anonymous riddle opener, one object per woman in the family (OFFICIAL, READ).
  Evaluation:
    Words/chars:   A closer costs 5–10 words, which leaves 40–45 for the items.
    Portal:        Survives inline.
    Answers the prompt? Only if each item is important on its own. If the five matter only because of
                   the sixth thing that connects them, the answer drifts toward "one thing" (T9;
                   this run's reasoning).
    Evidence:      moderate at essay length (official counselor comment); none at 50 words
  Fails when:  "the device is the whole idea" (§4.4). Also fails when the thread is too obscure to find,
               because the reader is puzzled instead of curious (T4).
```

### HIGH: format break or sideways reading

```
MICRO-SHELL (LIST INSIDE A BORROWED DOCUMENT)  ·  risk: HIGH  ·  catalog: creative_forms.md §4.13
  Move:        The five things are written as a real document that holds lists: a to-do list, a
               recipe's ingredient line, a label, or a classified ad.
  Why it can work here: Brenda Miller: hermit-crab essays "adopt already existing forms as the
               container for the writing at hand, such as the essay in the form of a "to-do" list, or a
               field guide, or a recipe." (CRAFT, READ). §4.13 scale at 50 words: "micro-shells only
               (a label, a classified ad)" (S). §7 (S, weak): "The cleanest wins are small, legible
               twists inside short answers that still answer the question". Gates: T0 (what does the
               shell say that a plain list cannot?), T1 (writer's call; no profile), T4 (recognizable in
               one word), T7.
  Skeleton:    [shell label, 1–3 words, naming the document]: [item 1 in the shell's idiom]; [item 2];
               [item 3]; [item 4]; [item 5]
               — the idiom must carry content, e.g. imperatives on a to-do list, quantities on an
               ingredient line, where [the quantity is itself informative]
  Real examples: none at this prompt (searched: §4.13, §7). Nearest, all COMMUNITY and self-reported,
               lengths not given: a QuestBridge short answer written as an obituary (Cornell match), and
               Brown's "teach a class" answered as a fake course-catalog entry (Brown ED admit).
  Evaluation:
    Words/chars:   The label costs 1–3 words. The shell's idiom (e.g. "1 cup", "2 tbsp") can cost about
                   2 words per item, 10 words in all. That leaves roughly 35–45 words for the five
                   things. T7 is the live risk: up to 30% of the budget can go to the shell.
    Portal:        Survives only inline. A one-item-per-line layout depends on undocumented line breaks
                   (§6). No pipes, no emoji checkboxes.
    Answers the prompt? Only if all five items are legible as things important to you once the shell is
                   stripped (T9 + T10).
    Evidence:      weak (community reports only at short-answer length; the showcase evidence for
                   §4.13 is 650-word essays)
  Fails when:  The shell becomes the point: hermit-crab essays "without proper care, are at risk of
               devolving into cute pets" (Rebecca Fish Ewan, CRAFT, READ). Or T4: the shell is
               unrecognizable, and Kim Adrian warns "otherwise you'll just baffle your reader" (CRAFT,
               READ). Or T6: the shell was chosen before the five things.
```

## 3. Tried and failed (keep; do not re-propose)

| Pattern | Verdict | Why (source or reasoning) |
|---|---|---|
| Five abstract values ("family, honesty, education…") | REJECTED for this prompt | The obvious word is the failure: CEG, *"DON'T use Top 50 adjectives"* (PRACTITIONER, READ-WF). Nearest §8 entry: "My Favorite Things", the list assumed interesting (Bauld via Moody, SECONDHAND) |
| A verse or list-poem whose value is its line breaks | REJECTED for this prompt | T10: lineation is "RISKY everywhere" (§4.21, §6), and stripped of line breaks it collapses back into a list. Yale's John places poems, if anywhere, in *"some of the shorter pieces"*, but that is Yale's view (OFFICIAL, 2021), not Stanford's |
| One item per line, numbered, or items separated by "\|" | REJECTED for this prompt | The pipe *"causes portions of your responses to disappear"* (Common App, OFFICIAL, July 2026). Single line breaks are undocumented (§6). Numerals may count as words (counting method undocumented) |
| Emoji as items or bullets | REJECTED for this prompt | Emoji are garbled in the Common App character set (§6) |
| Snarky or deflecting answer | REJECTED for this prompt | Georgia Tech: *"If you are tempted to not spend time on the answer or to get a little snarky in your response, don't."* (OFFICIAL, 2019) |
| Five items that restate the activities list | REJECTED for this prompt | Corroborated theme 5, "Do not restate the résumé" (Penn, UC, Dartmouth, Princeton; `university_guidance.md` Part 2). Penn: *"We don't need you to summarize the rest of your application in your statement or short answers."* (OFFICIAL). Stanford reads each piece as part of *"an integrated and comprehensive whole"* |
| An item count other than five, or a self-referential "fifth thing" | REJECTED for this prompt | Reasoning only (T9): the literal answer is five things. No source addresses this |

## 4. The plain-prose test (for whichever option the writer picks)

Before committing to a form, the writer answers (test numbers from `creative_forms.md` §2):
1. **What does the form say that plain prose can't?** If nothing, it is costume (cliché taxonomy #21).
   (T0 is this skill's own test, not a quoted source.) *Here the list is mandated, so ask this only of
   any frame added on top of the list (the micro-shell, the riddle closer).*
2. **Is the form true to the writer?** (T1: a recipe essay from someone who cooks; a list from a
   list-maker.) **Does it echo the subject?** (T3)
3. **Does one sentence still answer the prompt literally?** Point to it. (T9) *Here: are there exactly
   five things, each important to you?*
4. **Does it survive the portal and the limit?** (T7, T10; §6 and the arithmetic above.) *Paste it with
   all line breaks and styling removed. Is it still five legible things in 50 words or fewer?*
5. **Is there still a why?** The 50/50 what-vs-why rule applies inside any form.
   **[NOT APPLIED: this rule is referenced by the template but defined in no skill file. See the
   friction log.]**

---

# MENU 2

```
FORMS MENU — Personal statement, prompt 7 ("topic of your choice") · no school named · 650 words

PROMPT (verbatim):   "Share an essay on any topic of your choice. It can be one you've already written,
                     one that responds to a different prompt, or one of your own design."
                     USER-SUPPLIED; not verifiable. No skill file caches the Common App prompt text
                     (essay_type_rubrics.md #1 records only that "#7 is 'any topic'"), so no staleness
                     check could run. The prompt does not require a form; any form is CHOSEN, so the §3
                     risk ladder applies in full.
LIMIT:               650 words, approx — verify current cycle (portal_specs.md Profile A lists 650, but
                     that row is not marked VERIFIED, and unverified rows must carry this tag).
                     Counted how: "Words; counting method undocumented" (creative_forms.md §6).
PORTAL:              Common App (the personal statement is "read by every school on the list",
                     portal_specs.md)
FORMATTING SURVIVES: Bold/italic/underline: supported ("You can bold, underline, and italicize text, but
                     formatting like linked text will not work", OFFICIAL help center, 2024), but whether
                     every reader sees it is undocumented (colleges receive "data exports and/or PDF
                     generation"). Line breaks, indentation, tabs: not documented; use blank-line breaks
                     between paragraphs or segments. Characters: Windows-1252 (dashes, curly quotes,
                     •, † ‡, ¹²³, ½, Western accents survive; emoji, non-Latin scripts, ⁴ and higher,
                     arrows, ✓ are garbled). Never "|". Strikethrough, color, indentation, tables, and
                     links break everywhere.
SCHOOL APPETITE:     No school named: no published statement retrieved. Following §5 grading rule 4,
                     "Where a school is silent, the form is judged on §2 alone." Calibration tier
                     defaults to T20-selective (school_tiers.md), which sets the height of the bar but says
                     nothing about form. The general record, since this essay goes to every school:
                     "No admissions office in the searched set recommends form-play in the main personal
                     statement" (creative_forms.md §1.3, the skill's own tally across 16 named offices).
                     If the list includes these schools, their lines apply (§5): Yale, self-chosen
                     letters "just a little too gimmicky" and poems "rarely seen it work well in a longer
                     essay" (OFFICIAL podcast, 2020/2021); Dartmouth, "you don't have to be gimmicky, you
                     have to represent yourself." (OFFICIAL podcast, c. 2023); Vanderbilt, "gimmicks like
                     having a 'hook' or some odd essay format" (OFFICIAL blog, 2008, dated); Tulane, wary
                     of twists (OFFICIAL director's blog, 2018); Johns Hopkins praises form when the content
                     earns it (the skill's summary): "succeeds due to the strength of its content"
                     (OFFICIAL, 2016–2026).
WHAT THE PROMPT TESTS: Who the writer is. The job is to "reveal a person the rest of the file can't
                     show" (essay_type_rubrics.md #1). Prompt fit is "nearly free (prompts are doors, not
                     fences)". [Rubric weights voice 35 / insight 30 / craft 20 / memorability 15 are the
                     skill's JUDGMENT.]
```

## 1. The conventional target (always first)

A 650-word prose essay in one of the two verified shapes (`craft_frameworks.md` §1.1, CEG, VERIFIED):
**narrative** (Status Quo → Inciting Incident → Raising the Stakes → Moment of Truth → New Status Quo)
or **montage** (*"a series of moments or story events connected by a common thematic thread"*), with CEG's
stated default *"experimenting with montage first"*. "Good" at 650 words means ordinary material handled
with *"extraordinary specificity"* (CEG, §1.4) and a first and last paragraph that each work alone,
because Georgia Tech's Rick Clark knows *"many readers who read the first and last paragraphs and only go
back if those are compelling"* (OFFICIAL, 2018, READ). **With no school named, and the essay going to
every school on the list, this is the right call for most writers.** Of 118 official showcase essays,
13 (11.0%) depart from plain prose at all and 4 (3.4%) are wholly non-prose (§1.1). The skill's net
calibration (S): risk the *content* first. CEG: *"instead of risks with basic format, take some risks in
what you write about and the connections and insights you make"* (PRACTITIONER, READ-WF; re-check before
quoting). If a form risk is wanted anywhere, the skill's sources put it in **one** piece that the others
balance. A UVA admissions dean wrote in 2007: *"if a student wants to do something wacky or funny with one
of them, there are two others to balance that out."* (UVA's "Notes from Peabody" blog: OFFICIAL-ADJACENT,
per `university_guidance.md` trap #1; `creative_forms.md` tags it OFFICIAL, and the two files conflict.
See the friction log.) A consultancy account on Reddit agrees: *"Just don't have both an abstract PS and
abstract supplementals."* (COMMUNITY)

## 2. Options by risk level

### LOW: fresh framing

```
ORGANIZING CONCEIT  ·  risk: LOW  ·  catalog: creative_forms.md §4.1
  Move:        One image or system you actually live with organizes an ordinary prose essay.
  Why it can work here: It is the common way showcase essays stand out. At least 12 of JHU's 57
               conventional showcase essays use one: trees, salt, entropy, Oreos, crochet, Spotify
               playlists (§1.1). The prose shape is unchanged, so T0, T7 and T10 pass by default. T3 (the
               image echoes the subject) decides it.
  Skeleton:    ¶1: [the image/system], met through one specific instance, not a definition
               ¶2–4: [three moments], each read through [one facet of the image], each ending on what it
                     shows about you
               ¶5: [where the image stops fitting, or what it can't hold] → [who you are now]
               (drop the image as soon as it stops earning its place; cliché #11 salvage: "Metaphor
               as seasoning… never as structure")
  Real examples: JHU "My Spotify Playlist" (Class of 2027): "reflects on special memories through the
               creative lens of Spotify playlists" (OFFICIAL, READ-WF; re-check before quoting).
  Evaluation:
    Words/chars:   No scaffolding. Setting up the image costs about 40–80 words, which leaves about
                   570–610 for the moments and the reflection.
    Portal:        Safe everywhere.
    Answers the prompt? Yes (prompt 7 accepts any topic). The sentence that carries the answer is the one
                   that says who you are. Put it where a first-and-last-paragraph reader will find it.
    Evidence:      strong (official commentary; the most common showcase move)
  Fails when:  "the conceit outruns its accuracy and the person disappears behind it" (§4.1; cliché #11,
               "Extended-metaphor overreach").
```

```
HUMOR AS THE CARRYING VOICE  ·  risk: LOW (conditional)  ·  catalog: creative_forms.md §4.3
  Move:        A conventional narrative or montage, told in the writer's real comic register.
  Why it can work here: JHU's commentaries credit what the humor reveals: "Most importantly, it gave us
               insight into his personality" (OFFICIAL, READ-WF). T1 decides it entirely.
  Skeleton:    ¶1: [a true situation that was funny as it happened, told straight]
               body: [narrative or montage beats; the humor comes from how you see things, not from
                     inserted punchlines]
               [at least one beat where the reader sees what the humor protects or reveals about you]
               close: [landing in the same voice]
  Real examples: JHU "Intercom Enthusiast", "On Potatoes", "A Study in Ambidexterity", "Growing
               Strawberries in a High School Locker" (OFFICIAL, READ-WF; years not given in the catalog).
  Evaluation:
    Words/chars:   No scaffolding. The cost is jokes that do no characterizing work (T7, informally).
    Portal:        Safe.
    Answers the prompt? Yes.
    Evidence:      strong, "but only for writers who are funny" (§4.3)
  Fails when:  The writer is not funny (Sherri Geller on Dartmouth's podcast: "if they're not funny, then
               maybe a college essay isn't the right time to try out."). Also fails with bathroom humor
               (Yale's Mark: "it shouldn't be in your essay") or outrageousness mistaken for risk (Parke
               Muth: "being outrageous is different than taking a risk").
```

```
RIDDLE OR REPETITION OPENER  ·  risk: LOW–MEDIUM  ·  catalog: creative_forms.md §4.4
  Move:        Open on a short run of seemingly unrelated concrete things, or a phrase you hear on
               repeat, then spend the essay connecting them.
  Why it can work here: Connecticut College counselors, on a riddle opener: "We were curious to find out
               how all of those seemingly unrelated things were connected!"; on Nancy Owusu '28's
               repetition of her own name as household commands, the device helps "the reader see exactly
               what she hears" (OFFICIAL, READ). Tests: T4, T5, and the Georgia Tech reader (the opener must
               reward reading on its own).
  Skeleton:    ¶1: [3–6 concrete, seemingly unrelated items] or [a phrase you actually hear, repeated],
                   written inline
               ¶2–4: [each item or repetition opened into a scene], one per paragraph
               close: [what the connection says about you, in plain words]
  Real examples: Connecticut College: Nancy Owusu '28; an anonymous riddle opener with one object per
               woman in the family (OFFICIAL, READ; years as given).
  Evaluation:
    Words/chars:   The opener costs 20–60 words, which leaves about 590–630.
    Portal:        Safe if the opener is inline. A one-per-line opener depends on undocumented line breaks.
    Answers the prompt? Yes.
    Evidence:      moderate (official showcase with counselor comment)
  Fails when:  "the device is the whole idea" (§4.4).
```

### MEDIUM: structural device

```
STAMPED SEGMENTS  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.6
  Move:        Prose vignettes cut by a recurring marker: an age, a clock time, a running count.
  Why it can work here: "the marker carries the arc without a sentence of explanation" (§4.6). Tests:
               T3 (the marker must belong to the subject), T5, T8.
  Skeleton:    [stamp 1: an age / a time / a count] → [scene, ~100–180 words]
               [stamp 2–4: the same kind of stamp, advancing] → [a scene showing change along one
                     thread, not a milestone]
               [final stamp that breaks the pattern: future tense, a count abandoned] → [what the arc
                     means now]
  Real examples: Hamilton, Claire Lazar '26: "I'm 6." / "I'm 9." … "I'll be 18.", across an Irish-dance
               life, ending in a future-tense scene of passing it on. Hamilton, Zane Glauber '12: a
               clock-stamped day with a jazz-drumming thread. JHU "In Pursuit of the Sublime": "Goal:
               40,000.", then "Status: N" word counts, ending "Not counting anymore". JHU commentary: "The
               unique format of her essay suited the content" (all OFFICIAL showcases, READ / READ-WF).
  Evaluation:
    Words/chars:   3–5 stamps at 2–4 words each cost 6–20 words, which leaves about 630–644 for
                   content: about 125 words per segment with five segments, or 210 with three.
    Portal:        Safe with blank-line breaks. Write the stamp as its own sentence ("I'm 9."). Don't let
                   bold or italics carry it, because whether readers see styling is undocumented.
    Answers the prompt? Yes. The final segment carries the who-you-are-now sentence, which is also where
                   a first-and-last-paragraph reader looks.
    Evidence:      strong (official commentary on JHU "Sublime"); catalog grade moderate–strong
  Fails when:  The segments are résumé milestones (T8: Jill Talbot on autobiographies titled by "years,
               locations, grades in school" that read as "an application essay", CRAFT, READ). Or the gaps
               don't connect (T5: Charles Green, "the need for some signal of coherence"; Montserrat
               Carty, segments used "as a way to avoid the work of connecting various threads").
```

```
HYBRID INSERT  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.9
  Move:        One non-prose artifact (an ingredient list, a stanza, an equation) dropped into prose,
               and the prose then does something with it.
  Why it can work here: In the showcases the insert is evidence or a setup, not decoration. JHU's
               "Fried Rice" recipe is "set up to be rejected"; JHU's slam-poem stanza "is itself the
               evidence of collaboration" (§4.9). Tests: T0, T1 (CEG on a 24-line equation: "a very
               effective strategy given the interests and narrative voice of this particular student",
               PRACTITIONER, READ-WF), T10.
  Skeleton:    [one artifact you actually have or made: a list, a stanza, an equation, a message],
                   about 30–100 words, placed [at the opening | at the turn]
               [the next sentence does something to it: rejects it, completes it, or reveals it as
                   evidence]
               rest: [narrative or montage that the artifact has framed]
  Real examples: JHU "Fried Rice in One (Not So) Easy Step": a full ingredient list, then "I bet you
               didn't read those numbers. I'll let you in on a secret – I didn't either."; commentary
               "Her essay is clever and well written, but more importantly…". JHU "The Voice of Many":
               opens with a co-written slam-poem stanza. CEG's prompt-6 example: a 24-line equation
               mid-essay. (OFFICIAL / PRACTITIONER, READ-WF; years not given in the catalog.)
  Evaluation:
    Words/chars:   The insert costs 30–100 words, which leaves about 550–620 for prose. How the Common
                   App counts equation symbols or list numerals is undocumented.
    Portal:        "lists and lineation are RISKY" (§4.9, §6). Type numerals by hand, use blank lines, and
                   run the plain-text test and the portal preview.
    Answers the prompt? Yes.
    Evidence:      strong for "Fried Rice" (commentary credits content over the insert), but "Several JHU
                   commentaries never mention the insert at all"
  Fails when:  "the insert is decoration" (§4.9).
```

```
REFRAIN  ·  risk: MEDIUM  ·  catalog: creative_forms.md §4.8
  Move:        Prose cut by one short line that returns 3–4 times, shifted in meaning each time.
  Why it can work here: It keeps a letter-like or dialogic device at refrain size. §4.8 (S) notes that
               this is "how it avoids Yale's objection" to whole-essay letters. Tests: T3, T7.
  Skeleton:    body: [narrative or montage]
               refrain: [one line you actually say, hear, or write], placed at [3–4 turning points]
               each return: [the same words, read differently because of what came before]
               close: [a final return, changed]
  Real examples: Hamilton, Heqing "Amy" Zhang (Class of 2018): "Hello, future? I'm ready for my happily
               ever after. Love, Amy." / "Hello, Amy? Sucks, doesn't it? Love, the future." (OFFICIAL
               showcase, READ)
  Evaluation:
    Words/chars:   A refrain of 8–20 words returning 3–4 times costs 24–80 words, which leaves about
                   570–626.
    Portal:        Safe.
    Answers the prompt? Yes.
    Evidence:      moderate (official showcase; no commentary quoted in the catalog)
  Fails when:  The catalog gives no failure note for §4.8. By the §2 tests: the refrain never changes
               meaning (T0/T3, so it is decoration), or the refrain grows into a whole-essay letter (§8's
               failed pattern).
```

*Also in the catalog at this level, not selected (the template caps each level at 1–3): §4.7 braided
essay (craft evidence only; no showcase essay found), §4.10 delayed reveal (practitioner only; exposed to
the first-and-last-paragraph reader), §4.12 reverse chronology (weak; no example found).*

### HIGH: format break or sideways reading

> Evidence note (§3): the HIGH tier is "Thin: 4 of 118 showcase essays; the rest is craft literature and
> anecdote." §3 offers HIGH "only when T1–T4 look passable". T1 cannot be judged without a writer, so each
> block below marks it as the writer's call.

```
BORROWED-DOCUMENT FORM ("HERMIT CRAB")  ·  risk: HIGH  ·  catalog: creative_forms.md §4.13
  Move:        The essay takes the shape of a real document (recipe, test, game, field guide, to-do
               list, mock scientific paper) whose logic mirrors the subject.
  Why it can work here: The borrowed form gives "an enormous amount of contextual information right off
               the bat" (Kim Adrian, CRAFT, READ). JHU "20 Questions": the narrowing mechanic "mirrors the
               writer's iterative learning". Gates: T3 ("A well chosen form will amplify or echo the
               central theme or subject of the essay.", Adrian), T4, T6, T7. T1: writer's call.
  Skeleton:    shell: [a document form that already belongs to your material], chosen AFTER the
                   material (T6)
               units: [4–8 steps / questions / entries], each carrying a scene or a reflection, not just
                   the shell's label
               turn: [the point where the shell's logic bends under your material]
               close: [one unit that says in plain words what the form has been showing]
  Real examples: JHU "20 Questions" ("Is it bigger than a breadbox?" … "Are you thinking of me?");
               commentary: "the essay's creative style succeeds due to the strength of its content." JHU
               "And the Secret Ingredient is…": "Step 1: Get the ingredients" to "Step 6: Enjoy!"; "The
               commentary praises the metaphor, not the step format." JHU "Korean Sticky Notes" (Class of
               2028): Korean words with glosses as section heads, "Hal-in: Discount." (all OFFICIAL,
               READ-WF; re-check before quoting). Literary model at applicant age: Gwendolyn Wallace,
               "Math 1619", written at 18, in The Shell Game (2018) (CRAFT, READ). Community (self-reported):
               a scientific-method personal statement reported with MIT/Harvard/Yale/Princeton admits "from
               an exceptionally strong file"; one written "like an experiment/study" (Penn Nursing ED), which
               its poster called "way too tryhard".
  Evaluation:
    Words/chars:   Unit labels ("Step 3:") cost 8–48 words, 1–7% of 650. Unit text that carries no
                   content costs far more: 20 bare questions at about 6 words each is about 120 words, 18%
                   of the budget. That leaves about 530–640 for content, depending on how much of each
                   unit does real work.
    Portal:        Depends on the shell. Recipe and test shells need their lists to survive (§4.13), so
                   start each unit as a paragraph ("Step 3: …") with blank lines between. Never rely on
                   indentation or single line breaks. Run T10.
    Answers the prompt? Yes (any topic). At least one plain sentence must say what the shell has been
                   about, and it has to sit in the first or last paragraph.
    Evidence:      strong for the three JHU essays (commentary credits content); the overall base rate is
                   thin (3 of 64 JHU essays); community reports are mixed
  Fails when:  T4 (Adrian: "Make your form easily recognizable—otherwise you'll just baffle your reader."),
               T6 (Jessica Wright: "Don't write the essay and then manipulate it into an unusual form for
               the sake of gimmick."), T7. Also when it stays a pet: "without proper care, are at risk of
               devolving into cute pets" (Ewan). The best ones "teeter on the edge of gimmicky but then
               transcend it" (McCabe) (CRAFT, READ).
```

```
NON-HUMAN OR OBJECT NARRATOR  ·  risk: HIGH  ·  catalog: creative_forms.md §4.14
  Move:        Something that was really present for the story (a thing you built or used) narrates
               you.
  Why it can work here: It lets the essay show a change in the writer "without self-praise" (§4.14, on
               JHU's "Pebble"). JHU: "The author chose a style that feels appropriate to them." (T1,
               OFFICIAL, READ-WF). T1: writer's call.
  Skeleton:    narrator: [an object or tool that was actually there], speaking in [a voice consistent
                   with what it is]
               body: [2–4 moments it witnessed]
               the point: [what it notices about you that you wouldn't say yourself: a fault, a
                   change]
               close: [its last observation, which makes you, not it, legible]
  Real examples: JHU "Beep bop beep bop. I'm Pebble. Nice to meet you!" (Class of 2026): narrated by a
               Lego robot the applicant built. Commentary: "This style will not work for everyone, but in
               this essay, we get some insight into the playful nature of the applicant." (OFFICIAL,
               READ-WF; re-check before quoting)
  Evaluation:
    Words/chars:   The narrator's introduction and verbal tics cost 20–60 words. The larger cost is
                   indirection: every sentence about the narrator is a sentence not about you (T7).
    Portal:        Safe (it is prose).
    Answers the prompt? Yes, provided the close makes the writer legible.
    Evidence:      strong commentary, but a single showcase example; "This style will not work for
                   everyone"
  Fails when:  The narrator becomes the subject (the "cute pets" risk, §4.13). If the narrator is only a
               disguise for a third-person self-reveal, it turns into §8's "that little girl was me"
               pattern (Yale's Mark: "it doesn't quite work because I always know that it's you").
```

```
SHORT GLOSSARY (3–5 ENTRIES)  ·  risk: HIGH  ·  catalog: creative_forms.md §4.18 (compare §4.13)
  Move:        Three to five headwords from a vocabulary you actually live in (a language, a trade, a
               family, a field) head the sections, and the definitions accumulate into an arc.
  Why it can work here: §4.18: the alphabet's or entry-order's "arbitrary certainty" supplies coherence
               to disjunctive material (Charles Green on Dinty W. Moore, CRAFT, READ). "A partial alphabet
               or a 3–5-entry glossary is feasible" (S). Tests: T3, T4, T5. T1: writer's call.
  Skeleton:    entry 1: "[Headword]: [short gloss]." at the start of a paragraph → [~100–180-word
                   scene showing what the word means in your life]
               entries 2–4: [same pattern; each definition shifts or complicates the last]
               final entry: [re-defines an earlier headword, or defines a word of your own]
  Real examples: JHU "Korean Sticky Notes" (Class of 2028), five Korean words with glosses as section
               heads (OFFICIAL, READ-WF). Dinty W. Moore, "Son of Mr. Green Jeans: An Essay on Fatherhood,
               Alphabetically Arranged" (Harper's, 2004) (CRAFT).
  Evaluation:
    Words/chars:   3–5 headwords with glosses at 3–8 words each cost 9–40 words, which leaves about
                   610–641 for content, about 120–200 per entry. (A full A–Z would give about 25 words
                   per letter; see §3.)
    Portal:        Safe if each headword opens a paragraph inline. Bold headwords may not reach every
                   reader. A non-Latin script is garbled on the Common App, so romanize (§6).
    Answers the prompt? Yes.
    Evidence:      moderate (one official showcase, with no commentary quoted in the catalog; craft
                   literature)
  Fails when:  The structure is carrying dull material. By Moore's own account (SECONDHAND), his draft
               began "horribly dull" and alphabetizing alone did not fix it. Or the headwords are
               exotic decoration with no scene behind them (T0, T6).
```

*Also in the catalog at this level, not selected: §4.16 second person (weak; Vanderbilt named a variant a
gimmick), §4.17 dialogue/screenplay/text thread (see §3 below), §4.19 footnoted essay (marginal at 650),
§4.20 an essay of questions (one self-report, at the one school that invites play).*

## 3. Tried and failed (keep; do not re-propose)

| Pattern | Verdict | Why (source or reasoning) |
|---|---|---|
| Self-chosen letter to your future self or roommate | REJECTED for this prompt | Yale's Hannah: *"it's just a little too gimmicky, I think."* Yale's Mark: *"a huge amount of content in that essay has been devoted to propping up the gimmick"* (OFFICIAL, 2020). §4.15: "the strongest *negative* official evidence in this file" |
| A poem as the whole personal statement | REJECTED for this prompt | Yale Ep. 17 (2021): *"Downvote."*; *"choosing to write in poem format should not be your ticket to standing out."* (OFFICIAL). §4.21 scale: "650 as a whole poem: no" |
| Third-person opening with a "that little girl was me" twist | REJECTED for this prompt | Yale's Mark: *"it doesn't quite work because I always know that it's you"* (OFFICIAL, 2020) |
| Second-person conversation with God | REJECTED for this prompt | Vanderbilt admissions blog, named as an "odd essay format" gimmick (OFFICIAL, 2008, dated) |
| "Light switch" twist (starts one way, flips) | REJECTED for this prompt | Tulane director: *"can sometimes trap you and come across as inauthentic"* (OFFICIAL, 2018) |
| Segmented autobiography by grade or year | REJECTED for this prompt | Talbot: reads as *"an application essay"*; *"The Admissions Essay is bravado. The Permission Essay is brave."* (CRAFT, Brevity 2013) |
| Full A–Z abecedarian at 650 words | REJECTED for this prompt | About 25 words a letter, too thin (S) |
| Extended metaphor carried as the whole structure | REJECTED for this prompt | `cliche_taxonomy.md` #11: "The metaphor outruns its accuracy by ¶2 and the person disappears behind it" |
| Wacky fonts, colors, concrete/stepped layout, tables | REJECTED for this prompt | CEG: *"Things like a wacky font or text color could easily feel gimmicky to a reader."* (PRACTITIONER); the portal cannot carry them (§4.22, §6) |
| Bathroom humor; swearing to seem edgy | REJECTED for this prompt | Yale's Mark: *"it shouldn't be in your essay"* (OFFICIAL, 2020). A UVA admissions dean: *"rarely thoughtful and almost never clever"* (2007; OFFICIAL-ADJACENT per `university_guidance.md`, see friction log) |
| "My Favorite Things" list | REJECTED for this prompt | *"the assumption that the list itself is interesting. It almost never is."* (Moody's gloss on Bauld, SECONDHAND) |
| Screenplay or text-thread form | REJECTED for this prompt (reasoning, not a §8 entry) | §4.17: 650 "marginal"; no application or literary example was read. The only "Yale really liked" claim is an unverifiable COMMERCIAL one (§9). Centered names and indents are lost, and emoji break the character set (§6). Dialogue *"can take up a good chunk of your word count without explicitly saying anything about who you are."* (CEG) |

## 4. The plain-prose test (for whichever option the writer picks)

Before committing to a form, the writer answers (test numbers from `creative_forms.md` §2):
1. **What does the form say that plain prose can't?** If nothing, it is costume (cliché taxonomy #21).
   (T0 is this skill's own test, not a quoted source.)
2. **Is the form true to the writer?** (T1: a recipe essay from someone who cooks; a list from a
   list-maker.) **Does it echo the subject?** (T3)
3. **Does one sentence still answer the prompt literally?** Point to it. (T9) *For prompt 7 there is no
   literal question to miss. Substitute the §7 pre-mortem (COMMUNITY heuristic): how would a reader finish
   "we really need to accept this applicant because they are ___"? Point to the sentence that fills the
   blank, and make sure it is in the first or last paragraph.*
4. **Does it survive the portal and the limit?** (T7, T10; §6 and the arithmetic above.) *Strip bold,
   italics, indentation and single line breaks, and turn any non-Windows-1252 character into "?". Then
   check the Common App preview.*
5. **Is there still a why?** The 50/50 what-vs-why rule applies inside any form.
   **[NOT APPLIED: this rule is referenced by the template but defined in no skill file.]**

---

# Friction log

Each entry: **where** (file + section) → **what happened** → **judgment call made in this run**.

### A. Contradictions between skill files

1. **UVA "Dean J" is tagged two ways.** `creative_forms.md` §1.6 ("OFFICIAL admission blog"), §5 table
   ("OFFICIAL blog · 2007") and §8 ("UVA Dean J, 2007 (OFFICIAL)") tag the blog OFFICIAL.
   `university_guidance.md` "The attribution rule", known instance #1, says the same blog ("Notes from
   Peabody") is a personal Blogger site, self-identified as unofficial: tag `OFFICIAL-ADJACENT`, cite as
   "a UVA admissions dean writes…", **never "UVA says…"**. SKILL.md Checkpoint 9 makes this
   load-bearing. → Used OFFICIAL-ADJACENT and the dean phrasing. **Fix `creative_forms.md`.**
2. **The no-school fallback differs.** `templates/forms_menu_template.md` header says "no published
   statement retrieved; tier default per school_tiers.md". `creative_forms.md` §5 grading rule 4 says
   "Where a school is silent, the form is judged on §2 alone." `school_tiers.md` has no form-appetite
   content for any tier, so "tier default" gives nothing to apply. → Followed §5 rule 4 and noted the
   T20 default only as bar height.
3. **Checkpoint 9 scope vs. the template's sourcing rule.** SKILL.md Checkpoint 9 lets a school's position
   be quoted only from OFFICIAL/OFFICIAL-ADJACENT entries in `university_guidance.md`, `ai_policy.md`, or
   **`creative_forms.md` §5**. The template requires sourced examples from anywhere in `creative_forms.md`,
   and the JHU/Hamilton/Conn commentaries (school voices) live in §1 and §4, not §5. Read literally,
   quoting JHU's "Pebble" commentary breaks Checkpoint 9. → Quoted them, with tag and access grade. The
   checkpoint should say "creative_forms.md (entries tagged OFFICIAL/OFFICIAL-ADJACENT)".
4. **An undefined hybrid tag.** Penn's "page 217" / dinner-guest lines are tagged "OFFICIAL quoted in
   press" (`creative_forms.md` §2 T9, §4.2, §8). That tag is not in the §0 tag list, and Checkpoint 9
   allows only OFFICIAL/OFFICIAL-ADJACENT. → Used it as an example with the original wording ("Penn
   officer quoted in CSM, 2000"), not as Penn's position.
5. **Two titles for what may be one JHU essay.** `creative_forms.md` §4.13 has "And the Secret Ingredient
   is…". `university_guidance.md` Johns Hopkins entry has "The Secret Ingredient is Connection (baking)".
   They may be one essay or two; offline, this can't be checked. → Used the catalog title.
6. **Stanford reading-culture note vs. "conventional first".** `school_tiers.md` reading-culture notes:
   for Stanford-style prompts "a safe, formal answer fails the prompt even if well-written" (JUDGMENT).
   The forms template: the conventional target is shown first and may be "the right call". The two are
   reconcilable (conventional ≠ formal), but the skill never says so, and a run could read school_tiers as
   pushing Stanford answers up the ladder. → Wrote the conventional target as specific rather than formal,
   and labelled the tier note JUDGMENT.

### B. Instructions missing for this input shape (no draft, no profile, mandated form)

7. **How the ladder applies to a mandated form.** `creative_forms.md` §3 says a prompt-mandated form "is
   not a risk at all" and "The risk ladder applies only to forms the applicant *chooses*". SKILL.md
   anti-pattern 21 agrees. But the template's §2 requires LOW/MEDIUM/HIGH options, and the forms trigger
   list includes list-type questions. Nothing says what LOW/MEDIUM/HIGH mean when the form is the
   assignment. → Redefined the ladder, for Menu 1 only, as distance from a plain well-chosen list, and
   stated that at the top of §2. **Biggest gap in the mode.**
8. **Contradictory risk label for list spines.** `creative_forms.md` §4.11 labels list spines "MEDIUM
   (native in list prompts)". For a list prompt that is a contradiction. → Labelled it "MEDIUM (execution
   risk only)".
9. **No catalog coverage for the Stanford "five things" question.** No §4 entry, §7 report, or §8 failure
   addresses it. The nearest are CEG on USC's three words (§4.5), Columbia's format-locked list (§4.11),
   and QuestBridge/Brown community micro-shells (§4.13). `university_guidance.md` has no Stanford
   formatting instruction for the list. → Every Menu 1 block says "none for this Stanford prompt
   (searched: …)". Menu 1 is thinner on evidence than Menu 2 for this reason.
10. **The craft reader has no forms-mode section.** SKILL.md's mode table assigns `craft_reader` "(form
    fit, §2 tests)". But `agents/craft_reader_agent.md` is written entirely for a draft: a required VOICE
    SAMPLE, ¶ anchors, a 1–6 rating, `reader_report_template.md`. T1 (fit to this writer) cannot run with
    no draft and no profile. → Folded the craft work into "Why it can work here" and "Fails when", and
    marked T1 as the writer's call in every block.
11. **The institutional reader's output is also draft-bound.** `institutional_reader_agent.md` §4 mentions
    forms mode in one sentence, but its output sections (marginal-value ledger, seat argument, red flags
    with quoted lines, rating) presuppose an essay. → Its work went into SCHOOL APPETITE, "Answers the
    prompt?", and the §3 tables.
12. **Checkpoints 1 and 2 are unaddressed in forms mode.** The Phase-0 "present the card for correction"
    pause and the Checkpoint-2 independence rule are never mentioned for forms mode, and the template has
    no slot for reader reports. It is unclear whether the readers are separate passes or one merged
    voice. → Merged them, and did not pause (dry run; no user to confirm).
13. **HIGH gating can't be evaluated with no writer.** `creative_forms.md` §3 offers HIGH "only when T1–T4
    look passable", and a general menu cannot judge T1. The template does not say whether to withhold
    HIGH options or show them flagged. → Showed them with "T1: writer's call" and the §3 thin-evidence
    note.
14. **No selection rule for the "1–3 patterns per level" cap.** At 650 words the catalog has six
    MEDIUM and about ten HIGH candidates. → Chose by evidence strength and listed the unselected ones in
    one line per level.
15. **T9 is ill-defined for an any-topic prompt.** The template's "Answers the prompt?" and plain-prose
    question 3 ("which sentence must carry the literal answer") assume a question that prompt 7 does not
    ask. → Substituted `essay_type_rubrics.md` #1's job ("reveal a person") and the §7 pre-mortem
    (a COMMUNITY heuristic), labelled as such.
16. **No rule on whose appetite governs a personal statement.** It goes to "every school on the list". For AI,
    `ai_policy.md` §1/§3 uses the strictest regime, but for form appetite nothing says whether to honor
    the least form-tolerant school. → Stated §1.3's "no office recommends form-play in the main personal
    statement" and listed the §5 lines to watch "if the list includes" those schools. No strictest rule
    was imposed.
17. **Certification and ceiling are left off the forms card.** The template's Rules mention
    certification-bound prompts and L0, but the forms-mode card (`context_analyst_agent.md` Forms mode)
    has no certification line. → Checked `ai_policy.md` §4: Stanford is SILENT and the Common App
    affirmation/Fraud Policy is the baseline, so neither prompt is certification-bound and no banner was
    armed. This was not recorded on the card because the card has no slot for it.

### C. Template and format gaps

18. **The template requires URLs the catalog doesn't carry.** Template Rules: "Every 'real example' traces
    to a catalog entry with a URL and tag." `creative_forms.md` catalog entries have tags but **no URLs**.
    Its header says the URLs are in `research/creative-forms-2026-09/`, a folder forms mode never points
    to. → Cited catalog section + tag + access grade. Did not open `research/`.
19. **Access grades aren't in the template.** `creative_forms.md` §0 says READ-WF quotes (all of JHU and
    CEG) should be "re-check[ed] before quoting to a user". A forms menu quotes them to a user, yet the
    template has no access-grade field and no re-check step, and this run cannot fetch. → Added the
    access grade and "re-check before quoting" by hand.
20. **The card and the template header disagree.** `context_analyst_agent.md` Forms mode says the card
    notes "whether the prompt itself requires a form", and task 2b wants a verified date. The template
    header has a slot for neither, and none for a word **minimum** (Stanford's 3). → Put all three
    inside the PROMPT and LIMIT lines to keep the template's field set.
21. **The "50/50 what-vs-why rule" is undefined.** `templates/forms_menu_template.md` §4 item 5 cites it.
    A search of every file under `agents/`, `references/` and `templates/`, plus `SKILL.md`, found it
    only in the template itself. → Not applied, and flagged in both menus.
22. **Two evidence scales that don't map.** The template grades evidence strong (official commentary) /
    moderate (published example, no commentary) / weak (community only) / none. The catalog uses "craft
    only", "practitioner", "moderate–strong", "strong, but only for writers who are funny", and so on.
    Practitioner and craft evidence has no slot on the template scale. → Used the template scale and
    added the catalog wording.
23. **Years are missing.** The template asks for a year per example, but the catalog gives none for
    several JHU essays ("20 Questions", "Fried Rice", "The Voice of Many", "In Pursuit of the Sublime",
    "And the Secret Ingredient is…", the humor essays). → Wrote "years not given in catalog".
24. **§4.8 (Refrain) has no "Fails when" line**, which the template requires. → Derived one from the
    §2 tests and labelled it that way.
25. **SKILL SYNTHESIS has no marker in the template.** Many scale lines, such as "50: micro-shells only"
    and "650: 3–5 segments", are marked *(S)* in the catalog, and the template gives no way to carry that
    mark into a menu. → Kept `(S)` inline.

### D. Portal and source gaps

26. **Prompt 7 isn't cached.** No skill file holds the Common App prompt text, so the user's wording
    cannot be verified and `source_refresh.md` has nothing to check. The 650 limit appears only in
    `portal_specs.md` Profile A, which is **not** marked VERIFIED, so it had to carry "approx — verify
    current cycle". → Did both, stated.
27. **Supplement fields aren't covered in §6.** `creative_forms.md` §6 documents Common App styling
    support for "the Common App" generally. Whether a member school's short-answer box (Stanford's
    50-word field) carries bold/italic or line breaks is not stated. → Treated as UNKNOWN.
28. **Word counting is undocumented.** §6 gives the Common App counting method as undocumented, so
    whether "1.", "&", "½", or an equation's symbols count as words is unknown. → Gave all arithmetic as
    ranges.
29. **"One of your own design" has no reading.** Prompt 7 contains that phrase, and no skill file says
    whether it invites form-play. → Read it as freedom of topic, not a form invitation, because nothing
    supports the stronger reading. The menu does not raise it.
30. **Minor.** The Context Analyst's Phase-0 tasks 4–5 (Pool Context Card, season/desk persona) have no
    role in forms mode, and forms mode doesn't say to skip them. → Skipped.

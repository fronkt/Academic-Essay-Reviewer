# AI-Tell Checklist — Application-Essay Edition

Used by `authenticity_reader_agent` (detection) and `line_editor_agent` Gate 2 (mirror scan on generated prose). Built on two sources:

- the `avoid-ai-writing` skill's 21 pattern categories, re-weighted for what admissions readers actually flag in personal essays. For a line-by-line audit with its 43-entry replacement table, run `avoid-ai-writing` on the draft separately.
- [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing), revision 1376018375 (2026-09-21), an advice page kept by WikiProject AI Cleanup. It is a community field guide written for *informational* prose, built from real flagged edits and citing corpus studies (Russell et al., ACL 2025; Kobak et al., *Sci. Adv.* 2025; Juzek & Ward, 2025; Reinhart et al., *PNAS* 2025; Geng & Trotta, 2024–25). Items tagged **[WP]** come from that page; how they map onto essays is this skill's judgment. Study findings are relayed as the page reports them and were not re-verified here.

**Framing rule:** a reader's suspicion does not require proof of AI use. A voiceless, uniformly polished essay loses EVEN IF the applicant wrote every word — the finding is "reads generated," and the fix is the same either way. Never accuse; describe.

## §0. How to use this list: a watchlist, not a delete list

1. **The signs are symptoms, not the defect.** [WP] *"Please do not merely treat these signs as the problems to be fixed; that could just make detection harder."* Swapping *pivotal* for *important* leaves the sentence exactly as empty. A hit means: go look at what the sentence is failing to say.
2. **The defect is regression to the mean.** [WP] A model drifts toward the phrasing that fits the most cases, so specific, unusual facts get replaced by generic, positive ones. The subject becomes "simultaneously less specific and more exaggerated." The page's example: "inventor of the first train-coupling device" becomes "a revolutionary titan of industry." In an essay: *"I rewired the servo at 2 a.m. and the arm stopped twitching"* becomes *"I tackled complex technical challenges that transformed our team."* The repair is upstream: put the specific fact back. A sentence that gets its fact back usually sheds its flagged words without being asked.
3. **One hit is noise; clusters are signal.** [WP] Flagged words co-occur: "where there is one, there are likely others." One or two in 650 words can be coincidence. That is what the escalation ladder is for.
4. **Read the vocabulary literally.** [WP] A word being overused does not mean its synonyms are. Do not extend the list by analogy.
5. **Descriptive, not prescriptive.** [WP] Nothing here is a style rule. A flagged construction the writer uses once, on purpose, in their own voice, stays.

## Escalation ladder

| Level | Definition | Severity |
|-------|-----------|----------|
| Isolated tell | 1–2 hits from one category | MINOR |
| Pattern | Repeated hits from one category, or hits from 3+ categories | MAJOR |
| Cluster | Pattern + absence-of-humanity markers (§C) together | **CRITICAL** (verdict-capping) |

## A. Vocabulary tells (cite the word + line)

- **Essay-observed flag list** (from `avoid-ai-writing`): delve, tapestry, testament (to), foster, myriad, plethora, navigate (a challenge), landscape, journey (as structure), embark, pivotal, profound, invaluable, honed, instilled, resonate, multifaceted, unwavering, ever-evolving, "a world where"
- **Corpus-attested words, by model era** [WP]. The overused set shifts as models change, so the *absence* of the 2023 words proves nothing:
  - 2023 to mid-2024 (GPT-4): additionally (sentence-initial), boasts, bolstered, crucial, delve, emphasizing, enduring, garner, intricate/intricacies, interplay, key (adj.), landscape, meticulous, pivotal, underscore, tapestry, testament, valuable, vibrant
  - mid-2024 to mid-2025 (GPT-4o): align with, bolstered, crucial, emphasizing, enhance, enduring, fostering, highlighting, pivotal, showcasing, underscore, vibrant
  - mid-2025 on (GPT-5): emphasizing, enhance, highlighting, showcasing. The structural tells in §B have outlasted the vocabulary.
- **Copula avoidance** [WP]: *serves as / stands as / marks / represents / functions as* where the writer means *is*; *boasts / features / offers / maintains* where they mean *has*. ("The lab serves as my second home" vs. "I basically live in the lab.")
- **Stiff substitutes** [WP]: *utilized, attempted, relocated, authored, passed away* where a person would write *used, tried, moved, wrote, died*.
- **Vague connection** [WP]: *associated with / in connection with / connected to* instead of saying what the relationship was. The essay cousin is *involved with*. ("Involved with the robotics team" — as what?)
- **Register mismatch** is a specific-word problem, not a formality problem (see §F). SAT vocabulary in a reflective passage counts only when it is these words, or a register the writer uses nowhere else in the draft.
- **Synonym cycling** (the same referent renamed each paragraph to dodge repetition). [WP] now files this as a *historical* indicator from older models, and notes that some non-native writers are taught to do it. Weak on its own.

## B. Rhythm & structure tells

- **Uniform cadence**: every sentence 15–25 words, no fragments, no run-ons. No breath.
- **Rule of three** [WP]: "X, Y, and Z" triads in description, reflection, and conclusion alike, used to make a thin point look thorough.
- **Negative parallelism** [WP]: "not just X, but Y" · "it's not X, it's Y" · "not X, not Y, just Z" · "Y rather than X". It corrects a misreading no reader had. Once is rhetoric; once a paragraph is a tic. Essay form: *"Robotics wasn't just a club. It was where I found out who I am."*
- **Trailing -ing analysis** [WP]: a fact followed by a participle clause telling the reader what it means: "…, highlighting my commitment to…", "…, reflecting a deeper passion for…", "…, fostering a sense of…". The fact was the essay; the tail is filler. Cut it, or replace it with the next concrete thing that happened.
- **The "Despite" formula** [WP]: "Despite these challenges, I…", or a challenge paragraph that ends in generic uplift. Mentioning a challenge is not the tell; the fixed challenge-then-triumph shape is.
- **Balanced paragraphs** of near-identical length with clean topic-sentence discipline (the five-paragraph theme in disguise).
- **Transition scaffolding**: *Moreover / Furthermore / Additionally / Ultimately* opening successive paragraphs. [WP] lists transition words **in isolation** as an ineffective indicator. Only a few (sentence-initial *Additionally* chief among them) are documented as overused. Flag the stack, not the word.
- **Summary closers** [WP, historical]: "In conclusion," "Overall," "Ultimately, this experience taught me…", restating the point back at the reader.
- **Em dashes**: see the note below.

**Note on em dashes.** [WP] Models use them more than non-professional writers of the same genre, often with spaces around them ( — ) and in a pat, "punched-up" way where a person would use a comma, colon, or parentheses. The page says the sign "is most useful when taken in combination with other indicators, not by itself," and in September 2026 flagged it as a candidate for its *historical* list because newer ChatGPT models were tuned to suppress em dashes. It also relays a July 2026 analysis reported in *The Economist*: **of contemporary models, only Claude used em dashes more than professional writers.** Two consequences:
1. **The writer's own em dashes are voice, not a tell.** Never strip or flag them on that basis.
2. **In prose this skill generates, check em-dash density first**, because the generator is the model most prone to it. Gate 1 already forbids adding punctuation the writer does not use.

## C. Absence-of-humanity markers (the heavy ones)

- **No concrete sensory detail**: events summarized at an altitude where nothing can be seen, heard, or smelled
- **Transferable reflection**: every insight could be pasted into another applicant's essay unchanged. The "who is this kid?" test returns empty.
- **Hollow profundity closers**: the final paragraph zooms out to humanity, the future, or "the next chapter" and says nothing checkable
- **Zero risk**: no humor attempted, no odd opinion held, no detail that could only embarrass this one writer
- **Error-free but voiceless**: mechanically perfect prose with no idiosyncrasy. Polish without fingerprints.
- **Significance inflation** [WP: "undue emphasis on significance, legacy, and broader trends"]: small true events given world-historical weight. Words to watch: *stands as, a testament/reminder, pivotal/key moment, marks a shift, key turning point, indelible mark, deeply rooted, setting the stage for, shaping, reflects broader*. ("That moment changed everything.")

## D. Application-essay-specific tells

- The essay answers the prompt's THEME but never touches the writer's actual week, room, or town. Biography-free.
- **Reflection register jumps**: narrative in a plausible teen voice, then insight paragraphs suddenly in a consultant/adult voice (see cliché taxonomy Arc #19). This fires only when the new register is the §A/§C one. Mixed registers on their own are not a tell (§F).
- Generic conclusions that restate the prompt's language back at it
- "As I [verb] into the future" constructions
- **Style shift across the file** [WP: "pronounced shift in writing style"]: one essay, or one paragraph, reads unlike the writer's other pieces in the same application (short answers, activity descriptions, other supplements). A drafted-then-revised essay can show the seam between the two hands. In `portfolio` and `whole-app` modes, compare across pieces.

## E. Why-us, activity, and award text

- **Brochure language** [WP: "promotional and advertisement-like language"]: *vibrant, rich (tradition/history), renowned, nestled, in the heart of, boasts, commitment to, diverse array, groundbreaking, showcasing, exemplifies*. The school described in its own viewbook's voice. The fix is something a viewbook would not say: a course number, a named lab and what it is working on, a student group's actual event.
- **Canned emphasis on recognition** [WP]: *featured in, profiled in, cited in, covered by*, "maintains an active social media presence": listing who noticed instead of what happened. In activity and honors slots, state the thing and the number.
- **Vague attributions** [WP]: *experts argue, observers have cited, some critics argue, several sources*, or "such as" in front of a list that is actually complete.

## F. Ineffective indicators: do NOT log a hit on these alone [WP]

- **Perfect grammar**, clean mechanics
- **Mixed registers**: casual next to clinical, technical next to emotional. The page: this "may also indicate youth, a preference for mixed registers, playfulness, or neurodivergence," or someone from a technical field. It is how many strong 17-year-old STEM writers sound.
- **Formal, academic, or "fancy" prose in general**. Only the specific words in §A correlate.
- **"Bland" prose**. Bland is a craft finding for the Craft Reader, not an authenticity finding.
- **Transition words in isolation** (see §B)
- **Your own confidence.** [WP] relays a 2025 study (Russell et al.) in which frequent LLM users spotted AI text about 90% of the time while light users did only slightly better than chance, plus other 2025 studies putting untrained readers near chance. Detector tools have non-trivial error rates. Describe what the prose does to a reader; do not rule on how it was made.
- **Convergence.** [WP, citing 2024–25 studies of spoken and academic English] People are picking up LLM phrasing, so a flagged word may simply be the writer's own.

## G. Signs of human writing: protect them in edits, aim for them in generation

[WP] lists constructions found empirically *more* often in human text than in AI text:

- Plain *is / has / there is* sentences
- Plain verbs: *wrote, moved, used, tried, died*
- Committed claims: *the only, the first, one of the best*, when true
- Hedges and intensifiers: *very, perhaps, tends to*
- The occasional wordy construction: *in order to, the fact that, all of the*

**What this means for the line editor:** standard tightening advice (cut every *very*, every *in order to*, every *there is*) pushes a draft *toward* the machine register. L1/L2 edits leave a writer's natural hedges and plain constructions alone unless they cause a real problem (word count, ambiguity). A draft sanded to zero roughness has lost its fingerprints (§C).

The essay-specific markers point the same way. The statistically *unlikely* detail is what shows a person was there:

- A proper noun, a number, a time, a brand, a room: something checkable
- A detail that could only embarrass or amuse this one writer
- An opinion a reasonable reader could disagree with
- A reflection that fails the transfer test (§C): it could not be pasted into another applicant's essay
- An ending that stays on the ground (an action, an object, a line of dialogue) instead of zooming out to the future
- A sentence left plain where a flourish was available

## Reader instructions

1. Scan by category; log each hit with quoted line + ¶ location.
2. Before logging, check §F. Drop any hit that rests only on an ineffective indicator.
3. Classify per the escalation ladder; only clusters justify CRITICAL.
4. In the report, describe the reader-experience consequence ("by ¶4 the voice has no fingerprints; a tired reader files this with the other 40") rather than speculating about tools.
5. In "What would disarm me," point at the specific paragraphs where putting back the writer's real diction and detail would retire the finding. Prescribe the missing fact, never a synonym (§0.1).

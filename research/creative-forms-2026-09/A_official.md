# Strand A — Official and published sources on creative / risk-taking essay FORM

Compiled 2026-09-23. Scope: university-published example essays (with admissions commentary where it exists), base rates of unconventional form inside those showcases, and official statements welcoming or warning against creative formats.

## Provenance method (read this first)

- **Direct text (exact):** pages fetched with `curl` and stripped to text locally, then grepped/read. Quotes from these are character-exact. Sources: Yale podcast transcripts, UChicago essay page (Gatsby page-data JSON) and UChicago News, Connecticut College, Hamilton, MIT, Georgia Tech, UC (web page + two official PDFs), Columbia, Stanford, Tulane (Blogger feed JSON), UVA Dean J (Blogger feed JSON), Vanderbilt, Dartmouth, Emory, Tufts.
- **WebFetch extraction:** Johns Hopkins (`apply.jhu.edu`) returns a Cloudflare block to `curl`. So every JHU page was read through WebFetch, which runs the page through a summarizing model. I asked for the commentary verbatim each time. Where I fetched a page twice (20 Questions, Pebble, In Pursuit of the Sublime, Fried Rice), the two extractions agreed word for word. Treat the JHU quotes as **READ (WebFetch, verbatim requested)**, one notch below the curl-exact sources. A final re-check against the live page before shipping would be prudent.
- Tags: OFFICIAL = an admissions office or officer speaking in role. OFFICIAL-ADJACENT = university-affiliated but not admissions (news office, student blogger). PRACTITIONER = a counselor or consultant. PUBLISHED-EDITORIAL = selected by editors.
- Essay excerpts are capped at about 25 words. No whole essays are reproduced.

---

## Part 1 — Unconventional-FORM essays in official showcases

Categories used below and in the tallies:
- **A = whole-essay non-prose form**: the entire essay is recast as another genre, such as recipe steps, a Q&A game, a glossary, or a non-human narrator.
- **B = segmented or structural device inside prose**: timestamps, age-stamps, a counter, a refrain, headed sections.
- **C = hybrid insert**: a poem, ingredient list or stat list dropped into otherwise conventional prose.

### Q&A game structure ("20 Questions") — Johns Hopkins "Essays That Worked", posted 2017-12-15 [A]
- What it is / how the form enacts the content: The essay mimics the electronic 20Q game. Quoted yes/no questions ("Is it bigger than a breadbox?", "Does it strive to learn?", "Is it driven?", "Does it apply what it learns?", "Does it attempt to better itself?", "Does it think deeply?", "Are you thinking of me?") each open a prose answer. The game's guess-by-narrowing mechanic mirrors the writer's claimed philosophy of iterative learning ("practice and perseverance"). The last line ties back to the device: "And much like 20Q, I will continue to learn throughout my life…" Writer: Ben[jamin].
- Source: https://apply.jhu.edu/hopkins-insider/20-questions/ — READ (WebFetch, verbatim requested, fetched twice, consistent) — OFFICIAL — JHU Undergraduate Admissions, commentary attributed to the admissions committee (no individual named)
- Commentary (verbatim): "We were impressed by the unique format Ben chose to describe himself and the lessons learned through his interest in computer science. However, the essay's creative style succeeds due to the strength of its content. Ben simulates electronic 20 questions to hook the reader's attention while effectively bridging his academic interests and future aspirations." — JHU admissions committee
- Outcome stated by source: Presented as an "Essay That Worked". The fetched page does not state admission status in so many words.
- Cautions/failure modes stated: Yes, implicitly. The form "succeeds due to the strength of its content". Format alone is not credited.

### Numbered recipe steps as section heads — JHU, "And the Secret Ingredient is…", posted 2018-12-15 [A]
- What it is / how the form enacts the content: Six headings, "Step 1: Get the ingredients" through "Step 6: Enjoy!". The steps follow a novice making empanadas from a YouTube tutorial, and each step carries a prose reflection on collaboration. The recipe's sequence stands in for the process of synthesizing other people's input. Writer: Mathias.
- Source: https://apply.jhu.edu/hopkins-insider/and-the-secret-ingredient-is/ — READ (WebFetch) — OFFICIAL — JHU admissions (unattributed)
- Commentary (verbatim): "Through the metaphor of cooking empanadas as a novice, his essay effectively conveys the message that collaboration 'demands an open mind'…" and "This tells us that, as a student, Mathias values the contributions of his peers and strives to bring people and ideas together to accomplish obstacles." — JHU admissions
- Outcome stated by source: "Essay That Worked". The status wording is the same as the entry above.
- Cautions/failure modes stated: None. Note that the commentary praises the *metaphor*, not the step format.

### Ingredient-list opener, then prose — JHU, "Fried Rice in One (Not So) Easy Step", posted 2020-12-15 [C]
- What it is / how the form enacts the content: The essay opens with a full fried-rice ingredient list with quantities. The prose then begins by puncturing it: "I bet you didn't read those numbers. I'll let you in on a secret – I didn't either." The recipe form is set up to be rejected. Family cooking runs on intuition, not measurement, and that tension (the writer loves precision baking) is the subject. The recipe is not returned to. Writer: Jess.
- Source: https://apply.jhu.edu/hopkins-insider/fried-rice-in-one-not-so-easy-step/ — READ (WebFetch, fetched twice, consistent) — OFFICIAL — JHU admissions committee
- Commentary (verbatim): "What we learn about Jess from her essay is a willingness to experiment, to take risks and find failure, and to learn from the past… Her essay is clever and well written, but more importantly it shows us her willingness to try different things…" — JHU admissions committee
- Outcome stated by source: "Essay That Worked".
- Cautions/failure modes stated: The "clever… but more importantly" construction puts craft below what it reveals.

### Non-human first-person narrator (the applicant's Lego robot) — JHU, "Beep bop beep bop. I'm Pebble. Nice to meet you!", tagged Essays That Worked 2026, posted 2022-12-19 [A]
- What it is / how the form enacts the content: The whole essay is narrated by "Pebble", a robot the applicant built in fifth-grade robotics. The applicant is shown only from outside, which lets the essay stage his arc from arrogance to humility without self-praise. Opening: "I'm Stone's sidekick, friend, and mentor." Closing: "I wonder what's next? Can't wait to find out!" Writer: Stone M.
- Source: https://apply.jhu.edu/hopkins-insider/beep-bop-beep-bop-im-pebble-nice-to-meet-you/ — READ (WebFetch; first extraction elided text, second gave it in full) — OFFICIAL — JHU admissions committee
- Commentary (verbatim): "The author chose a style that feels appropriate to them. This style will not work for everyone, but in this essay, we get some insight into the playful nature of the applicant. The content tells a story of growth. We see the author move from a place of arrogance to one of humility." — JHU admissions committee
- Outcome stated by source: Presented under the "Essays That Worked 2026" tag, meaning the Class of 2026.
- Cautions/failure modes stated: **Explicit: "This style will not work for everyone."** The form is justified by fit with the applicant ("feels appropriate to them"), not by novelty.

### Glossary / vocabulary-word section heads — JHU, "Korean Sticky Notes", Class of 2028, posted 2024-08-08 [A]
- What it is / how the form enacts the content: The frame is the Korean-word sticky notes on the writer's bedroom door. Five standalone headings, each a Korean word with its English gloss: "*Hal-in*: Discount.", then Jeonlyag (Strategy), Eon-eo (Language), Daehwa (Conversation) and Tamgu (Exploration). Each section is a prose vignette, for example grocery-store bargaining with her mother at H Mart. The glossary form enacts learning a heritage language word by word. Writer: Nancy P.
- Source: https://apply.jhu.edu/hopkins-insider/korean-sticky-notes/ — READ (WebFetch; heading structure confirmed in a second targeted fetch) — OFFICIAL — JHU admissions committee
- Commentary (verbatim): "Nancy's essay details the responsibilities she had at a young age and her resulting spirit of exploration. She shares memories of supporting her mother through the aisles of H Mart, and we learn about the strategic thinking skills she builds." — JHU admissions committee
- Outcome stated by source: Listed as Class of 2028.
- Cautions/failure modes stated: None. The commentary does not mention the form at all.

### Running word-count "Status" counter that segments the essay — JHU, "In Pursuit of the Sublime", posted 2016-12-15 [B]
- What it is / how the form enacts the content: The essay opens "Goal: 40,000." "Status: N" lines recur, tracking the word count of a 40,000-word novel the writer is drafting (40,000 → 5,000 → … → 0 → "Not counting anymore"). They cut into vignettes, so the numbers carry the arc from writing for validation to writing for herself. Dropping the count is the resolution. Writer: Kaylee.
- Source: https://apply.jhu.edu/hopkins-insider/in-pursuit-of-the-sublime/ — READ (WebFetch, fetched twice, consistent) — OFFICIAL — JHU admissions committee
- Commentary (verbatim): "We were impressed by Kaylee's ability to creatively relay important information about herself. The unique format of her essay suited the content and also showcased her passion for writing. What the essay did particularly well, though, was effectively explore experiences (both small and large) that shaped her growth as a person and writer." — JHU admissions committee
- Outcome stated by source: "Essay That Worked".
- Cautions/failure modes stated: The approval is conditional on fit ("suited the content"), and the "though" moves the credit to the reflection.

### Collaborative slam-poem stanza as opener — JHU, "The Voice of Many", posted 2018-12-15 [C]
- What it is / how the form enacts the content: The essay opens with one roughly 12-line stanza of a slam poem the writer wrote with a friend, starting "It's a hot and humid day in Swat Valley, Pakistan". Conventional narrative follows, about that collaboration becoming an Equality Club. Co-writing the poem is itself the evidence of collaboration. Writer: Reshmi.
- Source: https://apply.jhu.edu/hopkins-insider/the-voice-of-many/ — READ (WebFetch) — OFFICIAL — JHU admissions committee
- Commentary (verbatim): "Reshmi's essay highlights how combining forces with others can help you achieve your goals… This essay clearly shows us how the writer intends to collaborate with her peers to inspire change, both in and outside of the classroom." — JHU admissions committee
- Outcome stated by source: "Essay That Worked".
- Cautions/failure modes stated: None. The commentary is silent on the poem.

### Epistolary refrain + fragmented clauses — Hamilton College, Heqing "Amy" Zhang, Class of 2018 collection [B]
- What it is / how the form enacts the content: Prose about a first novel rejected at acquisitions, a classmate's death, and the novel later selling. It is punctuated by one-line letters to and from "the future": "Hello, future? I'm ready for my happily ever after. Love, Amy." Then the reply: "Hello, Amy? Sucks, doesn't it? Love, the future." It closes with "Hello, future? I'm not afraid. Love, Amy." Fragment strings ("Phone call from my agent. Sweaty palms and dizziness…") and a repeated "okay, okay, okay" carry the emotional pacing. The letter device appears only as a refrain. It is not a whole-essay letter.
- Source: https://www.hamilton.edu/admission/apply/college-essays-that-worked/2014-essays-that-worked (page titled "Essays that Worked - Class of 2018") — READ (curl, exact) — OFFICIAL (Hamilton Admission publishing the essays; "reprinted with their permission")
- Commentary (verbatim): none. Hamilton publishes no per-essay commentary.
- Outcome stated by source: "a sampling of the terrific college essays written by Hamilton students in the Class of 2018".
- Cautions/failure modes stated: none.

### Age-stamped vignettes ending in future tense — Hamilton, Claire Lazar '26 (Class of 2026 collection; published in the Fall 2022 Hamilton magazine) [B]
- What it is / how the form enacts the content: Paragraphs open "I'm 6." / "I'm 9." / "I'm 12." / "I'm 15." across an Irish-dance life. The last shifts to "I'll be 18." and a future-tense scene in which she adjusts a little girl's bun as her own once was. The timeline form turns a résumé of competitions into a passing-down.
- Source: https://www.hamilton.edu/admission/apply/college-essays-that-worked — READ (curl, exact) — OFFICIAL (Hamilton Admission)
- Commentary (verbatim): none.
- Outcome stated by source: "written by members of the latest class of incoming students". The page footer says the essays "were published in the Fall 2022 Hamilton magazine".
- Cautions/failure modes stated: none.

### Clock-stamped single-day structure — Hamilton, Zane Glauber, "The Rhythm of My Days, Measure by Measure" (Class of 2012 collection) [B]
- What it is / how the form enacts the content: The essay is segmented by clock times ("It's six o'clock.", "It's now five o'clock.", "The clock strikes ten.") across a school day, with jazz-drumming imagery threaded through. A day-in-the-life structure makes the "measure by measure" rhythm literal.
- Source: https://www.hamilton.edu/admission/apply/college-essays-that-worked/2008-essays-that-worked (titled "Essays that Worked - Class of 2012") — READ (curl) — OFFICIAL (Hamilton Admission)
- Commentary: none. Outcome: presented as Class of 2012 students' essays. Cautions: none.

### Headed "lessons" list — Hamilton, Alexander Wear, "Life from Seven Feet Up" (Class of 2018 collection) [B, borderline]
- What it is / how the form enacts the content: The body is a set of lesson headings, each followed by a prose paragraph: "I learned how to be comfortable in my own skin." / "I learned how to be kind." / "I learned humility." / "I developed a sense of lightheartedness." A plain enumerated structure for a height-defined identity.
- Source: Hamilton Class of 2018 page (URL above) — READ (curl) — OFFICIAL
- Commentary: none. Outcome: Class of 2018 collection. Cautions: none.

### Own poem appended after the prose — Hamilton, Sorina Seeley, "There is Something About Africa" (Class of 2012 collection) [C]
- What it is / how the form enacts the content: It opens with a rapid Zulu-greeting drill in dialogue lines ("You say, 'Sawubona.'" / "Sawubona"), follows with prose about a first visit to her father's South African home, and ends with an eight-line free-verse poem dated "Jan 2002" ("In the distance a hot wind / Sways the branches of a lone acacia tree…"). The dated poem works as an artifact of the trip.
- Source: Hamilton Class of 2012 page (URL above) — READ (curl) — OFFICIAL
- Commentary: none. Outcome: Class of 2012 collection. Cautions: none.

### Stat-list opener — Hamilton, Aubrey Wallen '26 [C, minor]
- What it is / how the form enacts the content: The opening line is a three-item numeric list, "75,000 flipped pages. 11,520 packed boxes. 6 school maps." It is then unpacked in prose about moving often and reading fantasy.
- Source: https://www.hamilton.edu/admission/apply/college-essays-that-worked — READ (curl) — OFFICIAL. Commentary: none.

---

## Part 2 — Framing-level risks (sideways reading, humor, meta, reversal) in official showcases

### Humor as the carrying voice — JHU "Intercom Enthusiast" (Isaac, posted 2016-12-15), "On Potatoes" (Madison, posted 2020-01-01), "A Study in Ambidexterity" (Justin, 2017-12-15), "Growing Strawberries in a High School Locker" (Seena, 2016-12-15)
- What it is: conventional prose whose main register is comic. The subjects are reading the morning announcements; potatoes as the one food to eat forever; ambidexterity; growing strawberries in a school locker.
- Sources (all READ via WebFetch, OFFICIAL, JHU admissions committee):
  - https://apply.jhu.edu/hopkins-insider/intercom-enthusiast/ — "Isaac's essay was light-hearted, comical, and fun to read. Most importantly, it gave us insight into his personality and hinted at the type of presence he's likely to have on our campus."
  - https://apply.jhu.edu/hopkins-insider/on-potatoes/ — "Madison's fun writing style left the admissions committee entertained, but more importantly gave us insight into her outlook and personality."
  - https://apply.jhu.edu/hopkins-insider/a-study-in-ambidexterity/ — "He also shows a sense of humor, revealing his character in addition to his academic goals."
  - https://apply.jhu.edu/hopkins-insider/growing-strawberries-in-a-high-school-locker/ — "His account of successfully growing strawberries in his locker showcased his ingenuity, sense of humor, and, most crucially, enthusiasm for collaborative work."
- **Pattern across all JHU commentary that mentions form, style or humor (8 essays: the four above plus 20 Questions, Pebble, Sublime and Fried Rice).** Every one pairs the praise of style with a turn that ranks content or insight higher: "However… succeeds due to the strength of its content"; "will not work for everyone, but…"; "…though, was effectively explore experiences"; "clever… but more importantly"; "Most importantly"; "but more importantly"; "revealing his character"; "most crucially". This is a consistent institutional framing: form and humor are credited as windows, never as ends.

### Repetition as structure — Connecticut College, Nancy Owusu '28
- What it is: the writer's name is repeated as a barrage of household commands ("Nancy, do the laundry," "Nancy, can you wash the bowls,"…) and totted up in a mock calculation (about 17,680 times a year). The page itself has the reader hear the name as she does.
- Source: https://www.conncoll.edu/admission/apply/essays-that-worked/nancy-owusu-28/ — READ (curl, exact) — OFFICIAL ("Every essay we receive is read by our admission counselors. Here's what they said…")
- Commentary (verbatim): "She uses repetition of her name throughout the essay to help the reader see exactly what she hears: her name, over and over and over. Rather than using a lot of words to spell out her dissatisfaction… she gets to the point in an amusing but heartfelt way" — Conn admission counselors
- Outcome stated: from "students who enrolled at Conn".
- Cautions: none.

### Riddle / list-question opener — Connecticut College, anonymous ("Standing up for your beliefs")
- What it is: the opener is "What do you get when you combine a hypodermic needle, international code, clay, an early mainframe computer, and the national budget? In a sense, you get me." Each object stands for a woman in the writer's family.
- Source: https://www.conncoll.edu/admission/apply/essays-that-worked/anonymous/ — READ (curl) — OFFICIAL
- Commentary (verbatim): "The first remark really drew us in: We were curious to find out how all of those seemingly unrelated things were connected! This set-up was also a fascinating way to share how the women in the student's family provided the drive and values…" — Conn admission counselors
- Outcome stated: from students "who enrolled at Conn".

### Meta-essay (writing about writing the essay) — Hamilton, Caroline O'Shea (Class of 2007) and Mitchell Greene (Class of 2022)
- What it is: O'Shea opens "Writing a college essay is intimidating business… So, I asked for help," reports her family's topic suggestions, and then turns to "who I am" as unsettled. Greene opens "It all comes down to the essay" and parallels his anonymous sperm donor's application essay with his own college essay.
- Sources: https://www.hamilton.edu/admission/apply/college-essays-that-worked/2003-essays-that-worked (titled Class of 2007) and https://www.hamilton.edu/admission/apply/college-essays-that-worked/2022-essays-that-worked — READ (curl) — OFFICIAL. No commentary.
- Note: Greene's meta frame is earned by content, since the donor file literally contained an essay. O'Shea's is the generic version of the move.

### Ironic reversal title — Hamilton, Riley Smith '12, "Why My Friends Didn't Visit Last Summer"
- What it is: a self-deprecating catalogue of the reasons friends "scoffed" at rural Rhinelander, Wisconsin (the barn, the chickens, the uncles). It reverses at the end: "I just feel sorry for everyone who scoffed at a visit to Rhinelander."
- Source: Hamilton Class of 2012 page — READ (curl) — OFFICIAL. No commentary.

### "An entire essay of questions" — UChicago applicant (applied 2008), reported in UChicago News, 2012-07-11
- What it is: a UChicago fourth-year student said of his own application: "I answered the question with an entire essay of questions." No text or prompt is given.
- Source: https://news.uchicago.edu/story/uncommon-approach-yields-creative-college-essays — READ (curl) — OFFICIAL-ADJACENT (UChicago News office article). The student's quote is COMMUNITY.
- Outcome stated: yes. He is "a fourth-year in economics", so enrolled.
- The same article quotes an admissions officer (Grace Chapin, "senior admissions counselor"): "We want the students to write about things that don't show up in a workshop on writing college essays." It also reproduces the opening of Laura Castelnuovo's answer to "two types of people". She reads the prompt sideways, dividing humanity into those who love and those who hate tomatoes: "For centuries, one thing has divided the human population like no other: the tomato."

### Pop-culture punchline ending — Emory, "Strong Personal Statements: Use rhetoric to engage your reader" (2021-09-17)
- What it is: the essay opens with a Homer epigraph ("How prone to doubt, how cautious are the wise!"), argues for action over caution, and ends on a pun: "As the wiser Homer has taught America… one must simply 'D'oh.'" That is a Simpsons reversal of the epic-poet epigraph.
- Source: https://blog.emoryadmission.com/2021/09/strong-personal-statements-use-rhetoric-to-engage-your-reader/ — READ (curl) — OFFICIAL (Emory Office of Undergraduate Admission blog; "The staff responsible for this student's file had this to say")
- Commentary (verbatim): "Lastly, a willingness to take risks is evident throughout the narrative and exciting to read about." This refers to the content. The pun is not commented on.
- Outcome stated: "written by students now enrolled at Emory University".

### Organizing conceit ≠ unconventional form (for calibration) — JHU "My Spotify Playlist" (Alyssa C., Class of 2027, 2023-08-25)
- A conventional-prose essay organized around three playlists. It is included because it *sounds* formal but is not: there are no track-list headings. Commentary: "Alyssa's essay reflects on special memories through the creative lens of Spotify playlists." — https://apply.jhu.edu/hopkins-insider/my-spotify-playlist/ — READ (WebFetch) — OFFICIAL. Many JHU "conventional" essays are conceit-built in this way (see tallies).

---

## Base-rate tallies

Classification: A = whole-essay non-prose form; B = segmented/structural device within prose; C = hybrid insert; Conv = conventional paragraph prose (it may still use an extended metaphor or conceit).

| Collection | Years covered | N | A | B | C | Conv | A+B+C share |
|---|---|---|---|---|---|---|---|
| **JHU Hopkins Insider "Essays That Worked" archive**, all 8 listing pages (https://apply.jhu.edu/hopkins-insider/application-section/essays-that-worked/ pp. 1–8) | posted 2016-12 → 2026-08 (about Classes of 2020–2030) | **64** | 4 (20 Questions; Secret Ingredient; Pebble; Korean Sticky Notes) | 1 (Sublime) | 2 (Fried Rice; Voice of Many) | 57 | **7/64 = 10.9%** (A alone 6.3%) |
| **Hamilton "Essays that Worked"**, 5 collections | Classes of 2007, 2012, 2018, 2022, 2026 | **38** (8+8+7+7+8) | 0 | 4 (Glauber clock; Zhang letter-refrain; Wear headed lessons; Lazar age-stamps) | 2 (Seeley poem; Wallen stat-list) | 32 | **6/38 = 15.8%** (A alone 0%) |
| **Connecticut College "Essays that Worked"** (current page) | Classes of '25 and '28, plus 1 anonymous | **9** | 0 | 0 | 0 | 9 | **0%** (1 uses heavy repetition, 1 a riddle opener) |
| **Emory "Strong Personal Statements"** (2021 five-part series + 2025-10 post) | 2020–21 and 2024–25 cycles | **7** | 0 | 0 | 0 | 7 | **0%** |
| **Pooled official showcases** | | **118** | **4 (3.4%)** | 5 | 4 | 105 | **13/118 = 11.0%**; A+B = 9/118 = 7.6% |

Notes on the tallies:
- JHU classification of the 57 "conventional" essays relies on WebFetch structural descriptions. I read all 64 pages individually; none of the 57 was described as having headings, lists, dialogue-script or letter form. The fetch summaries described at least 12 of the 57 as built on an extended metaphor or organizing conceit: trees, salt, entropy, Oreos, a hummus wrap, polyphony, crochet, tortillas, dance, Spotify playlists, packing, ambidexterity. **Conceit is common and form-risk is rare.**
- Hamilton's A = 0 means none of its 38 essays abandons prose wholesale. All six of its divergences are devices layered on prose.
- **Commentary on form, when a school gives commentary at all:** of JHU's 7 form-divergent essays, the commentary names the form in 3 (20 Questions, Sublime, Pebble), calls the writing "clever" in 1 (Fried Rice), and ignores the form in 3 (Secret Ingredient, Korean Sticky Notes, Voice of Many). Hamilton publishes no commentary. Conn's commentary names a device (repetition) once.
- Siena University (https://www.siena.edu/news/story/see-three-college-application-essays-that-worked/, 2016-06-21) had 3 essays. WebFetch summary only, so it is excluded from the pooled count: 0 clearly unconventional, 1 described as "poetic/philosophical prose".
- Collections I could not count: NYT money/work/class essays (blocked), Yale (none published), UChicago (none published), Harvard Crimson book (not legitimately readable). See "Searched, not found".

---

## Official statements on creative formats

### Welcoming (or permitting)

- **UChicago, official essay page, 2026–27 prompts** — https://collegeadmissions.uchicago.edu/apply/essay/ (read via the site's page-data JSON; curl exact) — OFFICIAL (Office of College Admissions):
  - "They can be approached with utter seriousness, complete fancy, or something in between."
  - Option 7 (choose a past prompt or write your own): "Be original, creative, thought provoking. Draw on your best qualities as a writer, thinker, visionary, social critic, sage, citizen of the world, or future citizen of the University of Chicago; take a little risk, and have fun!"
- **UChicago News, 2021-08-20** — https://news.uchicago.edu/story/unique-uchicago-essay-questions-spark-students-creativity — READ (curl) — OFFICIAL-ADJACENT article quoting officials:
  - Peter Wilson (AVP, director of undergraduate admissions): "It also signals to prospective students that we are an institution that values and celebrates novel ways of thinking and solving problems."
  - Grace Chapin James (former chair of the essay committee): "When we give people these creative questions, the goal is to open up their minds and see if they have a level of creativity or flexibility and exploration that will lend itself well to being in a UChicago classroom."
  - Dean John W. Boyer is *reported*, not quoted, as saying the idea is "to invite prospective students to be creative in a serious but intellectually playful way". That is the news writer's paraphrase, so do not present it as a direct quote.
- **UChicago magazine, Feb 2005** ("Question Authority", Amber Lee Mason) — https://magazine.uchicago.edu/0502/chicagojournal/report.shtml — READ (WebFetch) — OFFICIAL-ADJACENT. It reports then-Dean Ted O'Neill's rationale. Extracted lines include "A great candidate can make even the worst questions good questions." Speaker attribution within the article was not verified character-exact, so treat it as SNIPPET-grade.
- **UVA, Dean J (Senior Associate Dean of Admission), "On taking risks", 2007-01-26** — https://uvaapplication.blogspot.com/2007/01/on-taking-risks.html — READ (Blogger feed, exact) — OFFICIAL (the UVA admission blog):
  - "I love risk takers. I'm impressed by a kid who's willing to go against the grain in their application. During information sessions, I talk about taking risks, especially when it comes to essays. My thinking is that there are three essays on the UVa application and if a student wants to do something wacky or funny with one of them, there are two others to balance that out."
  - With a warning: "Risks are good, but use your judgement and stay away from being offensive." The case in point is swear-word essays: "This kind of essay is rarely thoughtful and almost never clever."
  - (Dated 2007. This is the only official source found that states a **portfolio logic** for form-risk: take it in one piece, balanced by the others.)
- **Yale, "Inside the Yale Admissions Office" Ep. 6 "Essays: The Little Stuff", 2020-07-31** — https://admissions.yale.edu/posts/2020-07-31-episode-6-essays-the-little-stuff — READ (curl, exact) — OFFICIAL (Yale admissions officers Hannah, Mark and Reed; the podcast carries the disclaimer "the views expressed here in this podcast are ours and they do not necessarily represent those of Yale University"):
  - Hannah on the 35-word Short Takes: "I do think that these short takes can be an opportunity to be a little bit more spontaneous with your answers… they can sometimes give us some– a little bit more spontaneity or personality than a full-sized essay can."
  - Reed on a committee case: the applicant's short takes "were just so lively and so different from every other piece of writing that he'd produced." No outcome is stated.
- **Yale Ep. 4 "Essays: What Works", 2020-06-15** — https://admissions.yale.edu/posts/2020-06-15-episode-4-essays-what-works — READ (curl) — OFFICIAL:
  - Hannah: "So if you are someone who's funny and light, then the voice that comes through in your essay should be funny and light. If you're more serious and solemn, then you might be writing a more serious and solemn essay. And that's OK."
- **JHU commentary**, quoted in full in Part 1: "We were impressed by the unique format…"; "The unique format of her essay suited the content…"; "The author chose a style that feels appropriate to them."
- **Tufts, Inside Admissions blog** — OFFICIAL:
  - Sean Ashburn (admissions officer), "5 Essay Writing Tips to Get You Through December" (Nov 30; year not shown on page) — https://admissions.tufts.edu/blogs/inside-admissions/post/5-essay-writing-tips-to-get-you-through-december/ — READ (curl): "Editing to catch typos and incorrect spellings is essential, but I encourage you not to let the editing phase sanitize the creative expression that should make your essays yours."
  - "Adventures of a First-Time Admissions Officer: Reading Season" (Nov 16; year not shown; byline "Tufts Admissions") — https://admissions.tufts.edu/blogs/inside-admissions/post/adventures-of-a-first-time-admissions-officer-reading-season/ — READ (curl): "Some authors' voices sing across the page, some are straightforward and deeply thoughtful, others possess deadpan humor or loud, clamoring wit… Over the past couple of weeks, I have laughed aloud while reading".
- **Stanford, "Application and Essays" (updated 2026-07-21)** — https://admission.stanford.edu/apply/first-year/apply.html — READ (curl) — OFFICIAL. The prompts themselves *require* forms: "There is a 3-word minimum and a 50-word maximum for each question"; "List five things that are important to you."; "Write a note to your future roommate…". Framing: "there are no right or wrong answers and you should allow your genuine voice to come through."
  - **Tension to flag:** Stanford's prompt mandates a letter to a roommate, yet Yale officers (below) single out the *self-chosen* letter-to-roommate essay as "too gimmicky". The skill should treat prompt-mandated form and self-imposed form differently.
- **Tulane, Jeff Schiffman (Director of Admission), "Apps 101: Ten Tips for an Epic College Essay"** (URL dated 2018-07; feed shows republication 2021-07-01) — https://tuadmissionjeff.blogspot.com/2018/07/ten-tips-for-epic-college-essay.html — READ (Blogger feed, exact) — OFFICIAL (the director's admission blog). He praises a process-structured essay: "I read a great essay this year where an applicant walked me thorough the steps of meditation and how your body responds to it. Loved it." (The typo "thorough" is in the original.)

### Warning (or steering toward plain)

- **Yale Ep. 5 "Essays: What Doesn't Work", 2020-07-10** — https://admissions.yale.edu/posts/2020-07-10-episode-5-essays-what-doesnt-work — READ (curl, exact) — OFFICIAL (Yale admissions officers Hannah and Mark; podcast disclaimer as above). This is the single strongest official warning found on self-imposed form.
  - Letter form. Hannah: "The letter to self or the letter to the future roommate– again, I get it as a prompt. And it can be helpful as a little creative writing exercise, I think. But it's just a little too gimmicky, I think."
  - Mark: "you tend to get wrapped up in the gimmick… I often find myself thinking that a huge amount of content in that essay has been devoted to propping up the gimmick of the letter. It has a salutation. And it has these little turns of phrase in the style of a letter. Yeah. It just often doesn't use the space very well."
  - Third-person twist. Mark: "This is the essay that's written in the third person, or it usually starts in the third person and there's usually a twist about two or three paragraphs in where you turn to, and you say, 'that little girl was me.'… it doesn't quite work because I always know that it's you."
  - Humor floor. Mark: "Bathroom humor, anything related to anything happening in the bathroom, it shouldn't be in your essay."
  - **Critical caveat (Hannah, same episode):** "these are not universal things. And they're never going to be the reason alone that you would be denied from Yale. We have admitted students every year who have made every single one of the choices that I think we'll be talking about."
- **Vanderbilt admissions blog, "The College Admissions Essay Part II: Beyond gimmicks and hooks", 2008-09-12, posted by "Thom"** (author slug thomgolden; he writes as an application reader, but his title is not given in the post) — https://admissions.vanderbilt.edu/vandybloggers/2008/09/the-college-admissions-essay-part-ii-beyond-gimmicks-and-hooks/ — READ (curl) — OFFICIAL (officer on the official admissions blog; capacity inferred from the post):
  - "It goes beyond the OCD (see yesterday's post) gimmicks like having a 'hook' or some odd essay format (like a second person account of a conversation between the applicant and God – a topic listed as 'can't miss' in one of those guidebooks at the mega-bookstore). Clear message, well thought out voice, and solid writing and editing."
- **Dartmouth, "Admissions Beat" S4E5 "Let Your Life Speak Through Your College Essay"** (the 50th episode; references early-September New York Times AI stories, c. fall 2023) — https://admissions.dartmouth.edu/admissions-beat-s4e5-transcript — READ (curl) — OFFICIAL (Lee Coffin, Dean of Admissions and Financial Aid):
  - Coffin: "The way you put a spotlight on something, you don't have to be gimmicky, you have to represent yourself."
  - Guest counselor Sherri Geller (PRACTITIONER: school counselor, past President of New England ACAC) on humor: "If they're funny, their essay can be funny, although I always tell them that if they're not funny, then maybe a college essay isn't the right time to try out."
- **University of California, official PIQ page** — https://admission.universityofcalifornia.edu/how-to-apply/applying-as-a-freshman/personal-insight-questions.html — READ (curl) — OFFICIAL:
  - "Making a list of accomplishments, activities, awards or work will lessen the impact of your words."
  - "Use 'I' statements… Use 'I' and 'my' statements in your responses." This implicitly cuts against second-person and non-human-narrator forms.
  - "save them in plain text (ASCII)… make sure no odd characters or line breaks have appeared." This is a technical ceiling on typographic forms.
- **UC official PIQ worksheet PDF** (filename `new-uc-piq-worksheet-2022_freshman.pdf`) — https://admission.universityofcalifornia.edu/_assets/files/how-to-apply/new-uc-piq-worksheet-2022_freshman.pdf — READ (downloaded, text-extracted) — OFFICIAL:
  - "Edit for content (facts about yourself) as the UC admissions reader is not looking at style or structure in your response."
  - (Strongest official "keep it straightforward" statement found. Note that the worksheet itself uses list-style brainstorming exercises such as "List three words…". Those are prewriting prompts, not a response format.)
- **Columbia, "Columbia-Specific Application Questions" (updated 2026-07-28)** — https://undergrad.admissions.columbia.edu/apply/process/columbia-questions — READ (curl) — OFFICIAL. The list question is format-locked: "Your response should be a list of items separated by commas or semicolons. Items do not have to be numbered or in any specific order. It is not necessary to italicize or underline titles of books or other publications. No author names, subtitles or explanatory remarks are needed." (There is no room for creative framing inside the list itself. Any "creativity" has to live in the selection.)
- **MIT, official "Essays, activities & academics" page (2026–27 questions)** — https://mitadmissions.org/apply/firstyear/essays-activities-academics/ — READ (curl) — OFFICIAL:
  - "Remember that this is not a writing test. Be honest, be open, be authentic—this is your opportunity to connect with us."
  - "if you're thinking too much—spending a lot of time stressing or strategizing about what makes you 'look best,' as opposed to the answers that are honest and easy—you're doing it wrong."
- **MIT, Chris Peterson (then admissions staff), "How To Write A College Essay", 2012-07-30** — https://mitadmissions.org/blogs/entry/how-to-write-a-college-essay/ — READ (curl) — OFFICIAL:
  - "It was a real thing, which happened to a real person, told simply. There is nothing better than that."
  - He also attacks essay-anthology books: "The single greatest scourge of college application essays is the advice dispensed by books with names like '50 Winning College Essays from Ivy League Students.'" (Relevant to how the skill treats anthology-sourced "examples".)
- **Georgia Tech, Rick Clark (Director of Undergraduate Admission), "College Admission Essays: I've Heard that One Before…", 2018-09-28** — https://sites.gatech.edu/admission-blog/2018/09/28/college-admission-essays-ive-heard-that-one-before-2/ — READ (curl) — OFFICIAL:
  - "there is no completely unique topic."
  - The reading-behavior constraint that matters for form: "your voice has to be evident. And like the list of extra-curricular activities, it needs to be clear in the first sentence or two. I know many readers who read the first and last paragraphs and only go back if those are compelling." (A form that withholds its point until the middle is exposed to exactly this reader.)
- **Georgia Tech, Katie Mattli (Senior Assistant Director), "Will saying I'm a blueberry get me into college? Supplemental Essays 101", 2019-07-12** — https://sites.gatech.edu/admission-blog/2019/07/12/will-saying-im-a-blueberry-get-me-into-college-supplemental-essays-101 — READ (curl) — OFFICIAL:
  - On quirky prompts: "If you are tempted to not spend time on the answer or to get a little snarky in your response, don't." And: "the answer itself does not really matter. At the end of the paragraph, they will know you better".
- **Tulane, Jeff Schiffman** (same post as above) — OFFICIAL:
  - He prescribes a plain three-part shape: "A great format of your essay: Part one; hint at whatever theme… Part two: tell a great story that illustrates that theme. Part three: circle back to the theme… Done."
  - He warns about the twist structure: "the light switch essay (where things start one way and then totally change in a different way) can sometimes trap you and come across as inauthentic."
  - "Sometimes, the simplest topics are the best ones."
- **Hamilton, "Essays that Worked – Tips for a Good College Essay"** — https://www.hamilton.edu/admission/apply/college-essays-that-worked/tips-for-a-good-college-essay — READ (curl) — OFFICIAL ("The Hamilton Admission Team"):
  - "resist the urge to be too casual or to over-share."
  - "Poignant moments in time, with a little bit of reflection, often make great essays."
  - "(And resist the urge to use the thesaurus!)"
- **Connecticut College "Essays that Worked" intro** — https://www.conncoll.edu/admission/apply/essays-that-worked/ — READ (curl) — OFFICIAL:
  - "We don't expect to be on the edge of our seats as we read essays. We just want you to be yourself in your content and style so we can learn more about you and see a sample of your writing skills. That's it."
- **Yale, official "Essays" page** — https://admissions.yale.edu/essays — READ (WebFetch) — OFFICIAL:
  - "We have read wonderful essays on common topics and weak essays on highly unusual ones." This concerns topic novelty, not form, but it is the same principle.
- **Yale Ep. 4** (Mark): "This is not the place to show off how big your vocabulary is or to try to construct the most complex sentences with lots of semicolons and dependent clauses".

### Synthesis of the official record (for the skill's calibration)
1. **The only official voices that invite play are prompt-bound.** They are UChicago's extended essay, Yale's Short Takes and Stanford's short questions. **Personal-statement-level form-play is never actively recommended** by any office I found. It is praised after the fact (JHU) or tolerated with conditions (UVA 2007: one wacky piece balanced by the others).
2. **Warnings name specific forms:** the letter to self or roommate (Yale), the third-person twist (Yale), the second-person conversation with God (Vanderbilt), the "light-switch" twist (Tulane), and generic gimmickry (Dartmouth, Vanderbilt). UC says its readers are "not looking at style or structure". Columbia locks its list format.
3. **Even the praise is conditional.** In every JHU commentary that mentions form, style or humor, the credit goes to fit or content: "succeeds due to the strength of its content"; "suited the content"; "feels appropriate to them"; "will not work for everyone".
4. **Base rate:** about 1 in 9 showcase essays deviates in form at all (13/118), and about 1 in 30 abandons prose wholesale (4/118).

---

## Searched, not found

- **Yale published example essays with commentary.** `https://admissions.yale.edu/essays-worth-reading` returns 404. The official `/essays` page links no sample essays. Two site-restricted searches (the "essays worth reading" commentary query and "sample essays / why we liked") found no official collection. The podcast transcripts were used instead.
- **UChicago officially published example responses with commentary.** None found on collegeadmissions.uchicago.edu (essay page JSON), news.uchicago.edu (2012 and 2021 stories), mag.uchicago.edu ("Sixteen questions", Fall 2016) or magazine.uchicago.edu (2005). There is only one quoted opening line (the tomato essay) and one self-report (the "entire essay of questions"). The "Uncommon Blog" URLs from search (`/uncommon-blog/uncommon-approach-our-uncommon-prompts`, `/uncommon-blog/essay-writing-advice-why-x-university-essays`) render client-side and returned no body text via curl, page-data JSON or WebFetch.
- **Tufts "Essays We Loved" series.** A search summary mentioned such a series, but a site search for the phrase and the Inside Admissions "writing supplement" category (4 posts) did not surface it. Unverified; not used.
- **Carleton, Bowdoin, Colby, Vassar, Wellesley, Smith.** One combined site-restricted search for "essays we love / essays that worked / favorite essays" (carleton/bowdoin/colby/vassar) returned no official collection. I ran no separate query for Wellesley or Smith beyond the general "essays that worked site:edu" search, which surfaced only JHU, Connecticut College, Hamilton and Siena. Treat Wellesley and Smith as **not checked**, not as confirmed absent.
- **NYT college essays on money, work and class (PUBLISHED-EDITORIAL).** nytimes.com is blocked for both WebSearch ("domains are not accessible to our user agent") and WebFetch. The UW-Madison clipsheet page is only a link and summary. College Essay Advisors has a secondhand 2017 summary (PRACTITIONER; its form claims were unverified by me). **No base rate is possible.** This is a real gap.
- **Harvard Crimson, "50 Successful Harvard Application Essays".** The content is not legitimately readable online. Search surfaced only apparent pirate copies (Scribd, SlideShare), which were not opened. The Crimson's online "10 Successful Harvard Essays" (2021, 2024, 2025) is **sponsored advertising content** (Crimson Business "along with HS2 Academy", with Ivy Institute ad copy on the page: https://business.thecrimson.com/10-successful-harvard-essays-2025). It is not editorial, so I did not count or use it.
- **MIT officer statements specifically on poems, lists or gimmick formats.** None found. The MIT blog post titled "Poems" (2008) is by student blogger Lulu L. '09 and contains no advice. Other MIT posts read were by student bloggers: Elizabeth Choe '13 (2017), Lydia K. '14 (2012), Yuliya K. '18 (2015) and Victor D. '27 (2025, OFFICIAL-ADJACENT/COMMUNITY). Victor D. wrote of his own admitted MIT essay: "how absurd/unusual of a topic can i choose that will still be meaningful and make me memorable to the admissions officers… (probably very little of it lol)." — https://mitadmissions.org/blogs/entry/my-mit-admissions-essays/ — READ (curl).
- **Common App official statement on formatting (bold, italics, line breaks).** Not found. Only practitioner pages, which contradict one another.
- **"A UC director said bullet points are OK."** This appeared only in a search-engine summary of practitioner pages. It is SNIPPET-grade and unattributed, so I did not use it. The UC official documents say the opposite in spirit ("lessen the impact"; "not looking at style or structure").
- **Stanford official statement on creative formats** beyond the prompt text: none found on the essays page (`/apply/freshman/essays.html` yielded no usable text) or on `/apply/first-year/apply.html`.
- **Georgia Tech official "Personal Essays" page** (https://admission.gatech.edu/first-year/personal-essays): read, nothing on form.
- **JHU officer-authored essay-advice posts** ("Application Tips: Personal Statement", 2023-08-25, by "Tara"; "Advice For Crafting Your Supplemental Essay", 2026-08-03, by "Shannon"): read via WebFetch, nothing on form.
- **Harvard College student blogs** ("The Personal Essay", 2016-11-11; "My Very Unofficial Tips…", 2016-04-22): read, nothing on form. These are student bloggers (OFFICIAL-ADJACENT), not officers.
- **This American Life "A Prank Admissions Essay To Rick Clark"** is a prank email from an admissions professional, not an applicant essay. Irrelevant.

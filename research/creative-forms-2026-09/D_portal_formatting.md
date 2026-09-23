# D — Portal formatting behavior (2026–27 cycle)

Strand D of the creative-forms reference for `college-essay-board`. Compiled 2026-09-23. This file covers what each portal does to formatting. It does not repeat limits and structure, which `references/portal_specs.md` already holds.

## How to read this file

- **Tags.** OFFICIAL = portal operator or university in its role. PRACTITIONER = a named counselor or consultant writing publicly. COMMERCIAL = a test-prep or consulting company's content marketing. COMMUNITY = forums and Q&A.
- **READ vs SNIPPET.** READ means I opened the page and the quote comes from it. SNIPPET means the claim appeared only in a search-engine summary. Treat SNIPPETs as leads, not evidence.
- **Three kinds of READ.** Pages marked **READ (DOM)** were rendered in Chrome and the text was taken from the page itself, so the quotes are exact. Common App's help centers run on Salesforce and show nothing to a plain fetch, so every Common App help article here is READ (DOM). **READ (pdf)** means the text was extracted with `pdftotext`, so it is also exact. **READ (fetch)** means the quote came back through WebFetch's summarizer. It is very likely verbatim, but a small risk of paraphrase remains. Re-verify a READ (fetch) quote before printing it.
- **Dates.** Common App help articles show a "last modified" date and no cycle label. Every article cited was live on 2026-09-23.
- **INFERENCE** marks a conclusion I drew by combining official statements. No source states it directly.

---

## 1. Per-portal summary table

| Portal / box | Line breaks | Bold / italic / underline | Indentation / bullets | Special characters | Limit unit & counting | Key sources |
|---|---|---|---|---|---|---|
| **Common App** — personal essay + "long answer" college questions + Writing Supplement | **Not documented officially.** The official check is the preview: "how your essay will look to colleges." COMMERCIAL: the app adds a blank line between paragraphs automatically, so a typed blank line becomes a double space. | **Supported (OFFICIAL):** bold, underline, italic. **Links do not work (OFFICIAL).** Nothing else is listed, so strikethrough, superscript, font, size and color should be assumed lost (INFERENCE). | **No official statement.** COMMERCIAL: "does not allow tabbing." A "•" character passes the character filter (INFERENCE). Word auto-list formatting is at risk on paste (OFFICIAL: formatting loss on paste). | **OFFICIAL:** stored as MySQL latin1. Characters outside it become "unreadable." MySQL latin1 = Windows cp1252 (OFFICIAL, MySQL docs). So em/en dashes, curly quotes, …, •, † ‡ § ¶ °, ¹²³, ½ and Western-European accents **survive**. Emoji, non-Latin scripts, arrows, ✓ ☐ ★, ≠ and superscripts ⁴ and above **do not** (INFERENCE). **Pipe "\|" is banned (OFFICIAL):** it makes parts of responses disappear. | **Words.** "The system will prompt you if you exceed" the limit (OFFICIAL). How words are counted: **not found officially**. COMMERCIAL claims conflict on hyphens. | C1–C14 below |
| **UC** — Personal Insight Questions (4 × 350 words); Additional comments | OFFICIAL: after pasting, proofread so that "no odd characters or line breaks have appeared." Line structure is not guaranteed. PRACTITIONER: use block paragraphs, no indentation, a blank line between paragraphs. | OFFICIAL: save "in plain text (ASCII)." PRACTITIONER: Ctrl+B/I/U work while typing, but "such formatting is not saved." | OFFICIAL: plain text (ASCII) only, so "•" is a risk. PRACTITIONER: no indentation. | OFFICIAL: ASCII. PRACTITIONER: the app warns about characters it will not accept and converts curly apostrophes and long dashes to ASCII. | **Words**, 350 per PIQ (OFFICIAL). Additional comments: **550 characters** (OFFICIAL counselor deck 2026–27). Counting method: **not found officially**. | U1–U5 |
| **MIT** — MIT's own portal: 4 × ~100–200 words, 4 × 40–50 words, additional-info box | **Not found officially** for the current portal. | **Not found officially** for the current portal. The only official guidance comes from 2011–2013 blogs about the *previous* MyMIT portal, which MIT replaced in 2020. | Not found officially. | 2011 MIT blog (old portal): "Be particularly careful of characters like apostrophes, em dashes, and quotation marks." | **Words, hard-enforced:** "Your information will not be saved if the responses are too long" (OFFICIAL FAQ, undated). 2011/2013 blogs (old portal): the limit was really a character count; contractions and hyphenated words counted as two or more words. | M1–M6 |
| **Coalition on Scoir** | Not found officially. | Not found officially. | Not found officially. | Not found officially. | **Words:** "minimum of 250 words but 500-650 is typically a good target" (OFFICIAL, Scoir). **Preview exists:** "Download a PDF to see what colleges will see" (OFFICIAL). | S1–S2 |
| **ApplyTexas** (redesigned 2024) | Not found officially for applicants. | **Depends on each receiving college (OFFICIAL, THECB):** colleges choose "rich text formatted essay data" or "a plain text version." The applicant cannot know which. | Same as the previous cell. | Not found officially. | **UT Austin short answers are limited by LINES:** "no more than 40 lines, or about 250-300 words" (OFFICIAL). The legacy "120 eighty-character lines" rule is SNIPPET/COMMERCIAL only and dates from before the redesign. | T1–T3 |
| **QuestBridge** (NCM application) | Not found officially. AskQB warns that pasted text may be "cut off at the end," which points to a hard limit. QuestBridge's essay guide: "It's easiest to read essays with a line break between each paragraph!" | Not found officially. | Not found officially. | Not found officially. | Not verified officially in this strand. The 800- and 500-word figures are SNIPPET/COMMERCIAL only. | Q1–Q3 |

**School-specific portals:**
- **Stanford** uses the Common App. **Caltech** uses the Common App or QuestBridge. Neither has its own essay portal.
- **Georgetown** offers its own Georgetown Application alongside the Common App. How its essay boxes handle formatting was not found officially.
- **UChicago** takes the Common App or Coalition and adds a self-upload channel for creative work. Details in G1–G6.

---

## 2. Evidence by portal

### Common App (OFFICIAL unless tagged)

| # | Source (URL · access · tag · date) | Verbatim quote(s), each ≤25 words |
|---|---|---|
| C1 | "Why won't my essay copy and paste correctly?" — https://appsupport.commonapp.org/applicantsupport/s/article/Why-won-t-my-essay-copy-and-paste-correctly · READ (DOM) · OFFICIAL · last modified Jul 31, 2024 | "some types of text formatting options are not possible when completing long answer questions." / "You can bold, underline, and italicize text, but formatting like linked text will not work." / "The preview button is a great way to see how your essay will look to colleges." / "If your essay has formatting errors, you can try to first paste your essay into a notes app." |
| C2 | "What character types does Common App allow?" — https://appsupport.commonapp.org/applicantsupport/s/article/What-character-types-does-Common-App-allow · READ (DOM) · OFFICIAL · Jul 25, 2023 | "our data only allows the mysql's latin1 character set." / "Characters outside of the latin1 character set are translated to an unreadable format when saved to the database." |
| C3 | "Pipe character (\|)" — https://appsupport.commonapp.org/applicantsupport/s/article/Pipe-character · READ (DOM) · OFFICIAL · **Jul 16, 2026** | "Avoid using the pipe character ( \| ) because it causes portions of your responses to disappear when your application data is submitted." |
| C4 | "What is the min/max word count for the essays on the Questions page or Writing Supplement?" — https://appsupport.commonapp.org/applicantsupport/s/article/What-is-the-min-max-word-count-for-the-essays-on-the-Questions-page-or-Writing-Supplement · READ (DOM) · OFFICIAL · date not captured | "Each school has different requirements/word counts for their essay questions" / "The system will prompt you if you exceed or do not meet the word limit for any given essay question." |
| C5 | "Why isn't my Writing Supplement showing in the PDF preview…?" — https://appsupport.commonapp.org/applicantsupport/s/article/Why-isn-t-my-Writing-Supplement-showing-in-the-PDF-preview-of-my-Common-App · READ (DOM) · OFFICIAL · date not captured | "the Common App and Writing Supplement are reviewed and submitted separately." / "Once the Common App has been submitted you will be able to review and submit the Writing Supplement." |
| C6 | "Why are some responses missing from the PDF preview…?" — https://appsupport.commonapp.org/applicantsupport/s/article/Why-are-some-responses-missing-from-the-PDF-preview-of-my-application · READ (DOM) · OFFICIAL · date not captured | "Colleges can choose to hide (or 'suppress') certain Common App answers on their PDF of your application." (The listed examples are test info, date of birth, gender, race and SSN. Essays are not among them.) |
| C7 | Member site: "Copy and Paste Formatting Issues" — https://membersupport.commonapp.org/membersupport/s/article/copy-and-paste-formatting-issues-viqlyqrk · READ (DOM) · OFFICIAL · Aug 8, 2023 | "You may experience some loss of formatting if you copy and paste text into the writing supplement text box." |
| C8 | Member site: "Scheduled delivery service (SDS) overview" — https://membersupport.commonapp.org/membersupport/s/article/Scheduled-delivery-service-SDS-overview · READ (DOM) · OFFICIAL · Feb 20, 2026 | Colleges receive "automated delivery of applicant and recommender records through data exports and/or PDF generation." |
| C9 | Member site: "Transfer SDS" — https://membersupport.commonapp.org/membersupport/s/article/Transfer-SDS · READ (DOM) · OFFICIAL · Aug 27, 2024 (transfer data feed) | "Common App will handle escaping of the special characters with answers." The same page describes tab- or comma-delimited .txt exports. |
| C10 | Member site: "Control Center application configuration — question configuration" — https://membersupport.commonapp.org/membersupport/s/article/Control-Center-application-configuration-question-configuration · READ (DOM) · OFFICIAL · Dec 19, 2025 | "Question type - Radio buttons, Dropdown, Checkboxes, Multiselect dropdown, Short answer, Long answer, Date, Month, Phone, Email, File upload" |
| C11 | Common App "Application dictionary" PDF (toolkit) — https://www.commonapp.org/static/6ac5a0fbb2c8b4b7721999e09d38defc/Resource_FYTR_AppDictionary_ENG_2025.06.24_0_0.pdf · READ (pdf) · OFFICIAL · 2025-06-24 | Portfolio: "A supplemental form used to showcase your special talents in 1 or more subjects." / "The Writing Supplement can only be submitted once your application to that college has been submitted." |
| C12 | "What are the 2026-27 Common App essay prompts?" — https://appsupport.commonapp.org/applicantsupport/s/article/What-are-the-2026-27-Common-App-essay-prompts · READ (DOM) · OFFICIAL · Mar 11, 2026 | Prompt 7: "It can be one you've already written, one that responds to a different prompt, or one of your own design." |
| C13 | Slate (Technolutions) knowledge base, "The Common Application Materials" — https://knowledge.technolutions.net/docs/the-common-application-materials · READ (DOM) · OFFICIAL for Slate, the reader-side CRM vendor, not Common App · 2026-03-27 | "PDFs will import automatically once the associated application record has been created via the CommonApp Source Sormat [sic] data import." |
| C14 | MySQL 8.4 Reference Manual, "West European Character Sets" — https://dev.mysql.com/doc/refman/8.4/en/charset-we-sets.html · READ (fetch) · OFFICIAL for MySQL, not Common App | "MySQL's latin1 is the same as the Windows cp1252 character set." |
| C-p1 | College Transitions, "How to (Quickly) Format Your Common App Essay" (Kelsea Conlin) — https://www.collegetransitions.com/blog/common-app-essay-format/ · READ (fetch) · COMMERCIAL · Aug 14, 2026 | "The Common App form does not allow tabbing" / "The application automatically places a space between each paragraph. If you already have a space, it will become a double space." / "any words written in those languages will be displayed as question marks." |
| C-p2 | Patch.com counselor post, "Paragraphs Now Permitted!" (Stacey Brook) — https://patch.com/new-york/mineola/important-update-to-the-common-application-essay-format-paragraphs-now-permitted_26c5dfca · READ (fetch) · PRACTITIONER · **Sep 9, 2013** (historical) | In 2013 the new Common App at first seemed to allow only one paragraph break. Common App then said that was never intended, and blank-line paragraphs worked. Historical context only. |
| C-p3 | wordlimit.ai, "Common App Word Count Rules" — https://wordlimit.ai/common-app-word-count-rules · **SNIPPET** · COMMERCIAL | Snippet claim: Common App counts words by splitting on spaces, so a spaced em dash counts as a word. Other snippets in the same search disagreed about hyphens. **Unverified. Do not rely on it.** |

**Character-set inference, as a reusable rule.** C2 plus C14 imply that the Common App keeps any character in Windows-1252 and garbles the rest. I checked membership with Python's `cp1252` codec.

- **Survives:** — – " " ' ' … • † ‡ § ¶ ° × ½ ¹ ² ³ ™ € and Western-European letters such as é ñ ü ç.
- **Garbled:** ⁴ and higher superscripts, → ✓ ☐ ★ ♪ ≠ ∑, all emoji, CJK (中), Cyrillic (Ж), Greek (α), and Central-European letters such as ł ş ő.

This is an INFERENCE. Common App never lists the characters, and the C2 article dates from 2023. The pipe "|" is a plain ASCII character, so it passes the character set but is banned separately (C3). One plausible reason is that delimited data exports treat it as a separator (C9 shows those exports exist), but that is also INFERENCE.

**What readers see (Common App).** Common App tells applicants the preview shows "how your essay will look to colleges" (C1). But colleges receive "data exports and/or PDF generation" (C8), and Slate imports the Common App PDFs as reader materials (C13). No official source says whether every reader sees the PDF, or whether some see exported text where bold and italic may be gone. **Not found officially.** So bold, italic and underline are safe in the PDF but not guaranteed across every college's reading setup (INFERENCE).

### UC (OFFICIAL unless tagged)

| # | Source | Verbatim quote(s) |
|---|---|---|
| U1 | UC first-year PIQ page — https://admission.universityofcalifornia.edu/how-to-apply/applying-as-a-first-year/personal-insight-questions.html · READ (DOM; the tip sits in a collapsed accordion) · OFFICIAL · page undated | "Once you are satisfied with your answers, save them in plain text (ASCII) and paste them into the space provided in the application." / "Proofread once more to make sure no odd characters or line breaks have appeared." / "Each response is limited to a maximum of 350 words." |
| U2 | "Presenting yourself on the first-year UC application 2026–27" (counselor deck) — https://admission.universityofcalifornia.edu/counselors/_files/documents/presenting-yourself-on-the-uc-application-first-year.pdf · READ (pdf) · OFFICIAL · 2026–27 | "Focus on the content, not the style, of your writing" / "Work on your PIQ responses in a separate document to check for spelling and grammatical errors." / "Once ready, copy and paste them into the UC application." / Additional comments: "there is a 550-character limit." / "Do not write a 5th PIQ response here!" |
| U3 | "Personal Insight Questions Guide for First-Year Applicants" — https://admission.universityofcalifornia.edu/_blocks/how-to-apply/first-year-applicants/new-ada-fy-piq.pdf · READ (pdf) · OFFICIAL · PDF metadata says modified Apr 16, 2026 | "Edit for content (facts about yourself) as the UC admissions reader is not looking at style or structure in your response." / "UC does not review unsolicited supplemental information (transcripts, letters of recommendation or resumes)." / "We do not have a definition of creativity, nor do we need you to limit your own idea of creativity." (tip on PIQ 3) |
| U4 | Ask Ms. Sun, "UC Application How-To Guide, Part III: PIQ Tricks" (Wei-Li Sun) — https://askmssun.com/uc-app-piq-tricks/ · READ (fetch) · PRACTITIONER · Oct 2, 2025 | Ctrl+B/I/U work while typing, but "such formatting is not saved" / "The application will also give a warning for special characters that are not accepted" / it "will automatically convert some special characters, such as curly apostrophes (') and long dashes (—), to plain text (ASCII text)" / "Set up your Personal Insight Questions in block paragraph format (single space, no indentation, double space between paragraphs)" |
| U5 | Older UC transfer user guide — https://admission.universityofcalifornia.edu/_assets/files/how-to-apply/application-guide-transfer-applicants.pdf · READ (pdf) · OFFICIAL · **2019** (stale) | Has no formatting guidance. Listed only so no one cites it again. |

### MIT

| # | Source | Verbatim quote(s) |
|---|---|---|
| M1 | MIT FAQ "Is it ok to go over the essay word count?" — https://mitadmissions.org/help/faq/essays-word-count/ · READ (fetch) · OFFICIAL · undated | "We require applicants to follow the word limits provided on the application. Your information will not be saved if the responses are too long." |
| M2 | MIT essays page ("For the 2026–2027 application") — https://mitadmissions.org/apply/firstyear/essays-activities-academics/ · READ (fetch) · OFFICIAL · 2026–27 | Short responses: "There is only space for 40 to 50 words each". The page gives **no** formatting guidance. |
| M3 | "Early Action Updates" (Matt McGann '00) — https://mitadmissions.org/blogs/entry/ea-updates-2011/ · READ (fetch) · OFFICIAL blog · **Oct 25, 2011 — about the old MyMIT portal** | "If you copy and paste from a program like Microsoft Word into the application, you may lose some formatting." / "Be particularly careful of characters like apostrophes, em dashes, and quotation marks." / "My understanding is that MyMIT is counting words like won't and first-class as two words each, and father-in-law would be three." |
| M4 | "Early Action Updates 2013" (Chris Peterson SM '13) — https://mitadmissions.org/blogs/entry/early-action-updates-2013/ · READ (fetch) · OFFICIAL blog · **Oct 17, 2013 — old portal** | "well technically, a character count limit with an estimated average character per word" / "You may find that MyMIT and your text editor disagree sometimes on how many words there are" … "trust MyMIT." |
| M5 | "The First-Year Application for the MIT Class of 2025 is now live" (Chris Peterson) — https://mitadmissions.org/blogs/entry/the-first-year-application-for-the-mit-class-of-2025-is-now-live/ · READ (fetch) · OFFICIAL blog · Aug 13, 2020 | MIT "completely overhauled the technical backend and applicant interface". **So M3 and M4 describe a portal that no longer exists.** The same post, about the optional extenuating-circumstances questions only: "Think technical communication, not creative writing." |
| M6 | MIT FAQ "May I include supplementary materials…?" — https://mitadmissions.org/help/faq/may-i-include-supplementary-materials-with-my-application/ · READ (fetch) · OFFICIAL · undated | "Creative portfolios in SlideRoom are available for researchers, performing artists, visual artists, and makers to submit supplemental materials." |

### Coalition on Scoir

| # | Source | Verbatim quote(s) |
|---|---|---|
| S1 | Scoir Help Center, "For Students: How to Apply Coalition with Scoir" — https://help.scoir.com/article/qqnplr6x2u-for-students-how-to-apply-with-scoir · READ (DOM) · OFFICIAL · "Updated 5 months ago" (≈ Apr 2026) | "An essay (minimum of 250 words but 500-650 is typically a good target)" / "Download a PDF to see what colleges will see (and share with others to review)" |
| S2 | Coalition essay prompts — https://www.coalitionforcollegeaccess.org/essays · READ (fetch) · OFFICIAL · no cycle label | "Share an essay of about 500-650 words" |

A search of Scoir's help center for "essay formatting" returned no formatting article.

### ApplyTexas

| # | Source | Verbatim quote(s) |
|---|---|---|
| T1 | THECB (which runs ApplyTexas), "ApplyTexas Questions Running List" — https://reportcenter.highered.texas.gov/training-materials/applytexas-questions/ · READ (pdf) · OFFICIAL · **last updated 4/29/24**, a pre-launch Q&A for colleges | "Institutions will have the option of receiving rich text formatted essay data for their applicants." / "the option to receive a plain text version of essay data will continue to be available for institutions as needed." / "Yes, you can configure plain text essays instead of rich text." / Planned then: "allow students to upload a document to be converted into Rich Text (and saved as both Rich and Plain text)" |
| T2 | UT Austin, "Essays & Short Answers" — https://admissions.utexas.edu/apply/application-materials/essays-and-short-answers/ · READ (DOM) · OFFICIAL · page undated (current cycle) | "Answers are limited to no more than 40 lines, or about 250-300 words per prompt, typically the length of one paragraph." / "Please keep your essay between 500-650 words (typically two to three paragraphs)." / "The Common App personal essay will complete the UT Austin essay requirement." |
| T3 | Legacy rule "no longer than 120 eighty-character lines of text (including spaces and blank lines)" — InGenius Prep / Bright Horizons College Coach (search results) · **SNIPPET** · COMMERCIAL · from before the redesign | Not confirmed for 2026–27. Mentioned only because a line-based limit charges for blank lines. |

### QuestBridge

| # | Source | Verbatim quote(s) |
|---|---|---|
| Q1 | AskQB, "Completing the Application: Quick Start Guide" — https://questbridge.zendesk.com/hc/en-us/articles/360025077033 · READ (Zendesk API JSON) · OFFICIAL · updated 2026-09-21 | "Always write, edit, and save your writing responses, including short answers and essays, in a document outside of the application" / "ensure that you have copied each response correctly and that it is not cut off at the end." |
| Q2 | AskQB, "I'm ready to submit my application — any final tips?" — https://questbridge.zendesk.com/hc/en-us/articles/218778647 · READ (API) · OFFICIAL · updated 2026-09-18 | "ensuring all of your writing responses are copied/pasted correctly." |
| Q3 | QuestBridge, "Writing College Essays: Detailed FAQs" — https://www.questbridge.org/resources/writing-college-essays-detailed-faqs · READ (fetch) · OFFICIAL · undated | "It's easiest to read essays with a line break between each paragraph!" |

### School-specific portals and upload channels

| # | Source | Verbatim quote(s) |
|---|---|---|
| G1 | Georgetown, "Application Requirements and Forms" — https://uadmissions.georgetown.edu/apply/first-year-applicants/application-requirements-and-forms/ · READ (DOM) · OFFICIAL · © 2026 | "Students can apply to Georgetown using either the Georgetown Application or the Common Application." / Essay 1: "Please submit a brief personal or creative essay which you feel best describes you" (650 words). How the Georgetown Application's boxes handle formatting: **not found**. |
| G2 | Stanford, "Application and Essays" — https://admission.stanford.edu/apply/first-year/apply.html · READ (fetch) · OFFICIAL · updated Jul 21, 2026 | "please do so online by submitting the Common Application" / "There is a 3-word minimum and a 50-word maximum for each question." / "There is a 100-word minimum and a 250-word maximum for each essay." |
| G3 | Stanford Arts Portfolio — https://admission.stanford.edu/apply/first-year/arts.html · READ (fetch) · OFFICIAL · 2026–27 deadlines Oct 20 (REA) / Dec 10 (RD) | "Students who wish to highlight their extraordinary talent in the fine or performing arts may submit an Optional Arts Portfolio". Materials are uploaded through the Stanford Portal. The summarizer reported the disciplines as Art Practice, Dance, Music and TAPS, with **creative writing not listed**. Verify before relying on that. |
| G4 | Caltech first-year applicants — https://www.admissions.caltech.edu/apply/first-year-applicants · READ (fetch) · OFFICIAL · Fall 2027 | "Common App or QuestBridge Application. Caltech does not have a preference between any of our 2 applications." A supplemental-materials "Portfolio" page exists. I did not read it. |
| G5 | UChicago, "Optional Application Materials" — https://collegeadmissions.uchicago.edu/apply/application/optional-materials/ · READ (DOM) · OFFICIAL · undated | "Students may submit supplemental material representing a significant talent, passion, or achievement by self-upload through their UChicago Account." / "These materials include, but are not limited to, creative writing projects" |
| G6 | UChicago's help topic inside the Common App help center, "Are there word limits?" — https://appsupport.commonapp.org/s/article/are-there-word-limits-kudeoeos · READ (DOM) · OFFICIAL (UChicago content) · **Jun 28, 2023** | "There are no strict word limits on the UChicago Supplement essays." / extended essay: "we suggest that you aim for around 650 words." Check this against the current UChicago page. |
| G7 | UChicago guidance to submit "the best paragraph or page of a creatively written work" · **SNIPPET** (search summary; probably the UChicago FAQ) · OFFICIAL if confirmed | Unverified wording. Do not quote it without opening the page. |

---

## 3. Implications for creative forms

Two principles hold across all six portals.

1. **The only formatting any portal officially supports is Common App's bold, italic and underline.** No portal officially documents that it preserves single line breaks, indentation, alignment, tabs, strikethrough, superscript or tables. A form that depends on any of those is betting on something undocumented.
2. **Plain characters travel; styling may not.** CAPS, spacing words out, colons, numerals, dashes and quotation marks survive everywhere the character set allows. Bold and italic survive only on the Common App, and even there only if the college reads the PDF (C8, C13).

Ratings: **SAFE** = supported officially or by a clear inference. **RISKY** = undocumented or depends on the college's setup, so verify in the preview. **BREAKS** = official or inferred loss. **n/a** = the form does not fit the box.

| Form | Common App | UC PIQ | MIT | Coalition/Scoir | ApplyTexas | QuestBridge | Survival recipe |
|---|---|---|---|---|---|---|---|
| **List / numbered list** (one item per line) | RISKY. Single line breaks are undocumented. Typed "1." and "•" survive the character filter; Word auto-numbering may be lost on paste (C1, C7). | RISKY. Plain ASCII only, so use "1." or "-" and never "•". Line breaks may shift (U1). | RISKY at 100–200 words. **n/a at 40–50 words.** | RISKY; check the PDF preview. | **UT short answers: every item costs a line** out of 40 (T2). | RISKY | Type the numerals yourself, not Word lists. Put several items on one line if line breaks collapse. Check the preview. |
| **Poem with line breaks / enjambment** | RISKY. Single-line breaks are undocumented; the preview is the only check. | RISKY-to-BREAKS. UC tells you to proofread for moved line breaks (U1) and says readers ignore "style or structure" (U3). | RISKY | RISKY | RISKY-to-BREAKS. A line-based limit charges for every short line (T2). | RISKY | Use stanza breaks (blank lines), not single line breaks. If the lineation carries the meaning, use slash notation ("line / line"). **Never use pipes on Common App (C3).** |
| **Stepped or concrete poetry, centered or indented text** | BREAKS. No official indentation support, and COMMERCIAL sources say no tabbing (C-p1). | BREAKS (ASCII; no indentation, per U4). | BREAKS (assume) | BREAKS (assume) | BREAKS (assume) | BREAKS (assume) | Do not use in essay boxes. Use an upload channel (UChicago G5, MIT SlideRoom M6). |
| **Screenplay / dialogue script** | RISKY. Centered speaker names and indents are lost; CAPS and "NAME:" survive. | Same: RISKY, ASCII only. | RISKY | RISKY | RISKY. Many short lines use up the line budget. | RISKY | Flush-left "NAME: line." Put stage directions in parentheses or italics (Common App only). No pipes or tab stops. |
| **Footnotes / annotations** | SAFE-ish. Superscript formatting is not supported (C1). The characters ¹ ² ³ * † ‡ survive (INFERENCE C2+C14); **⁴ and higher are garbled**. | Use [1] or * only; ¹ † are not ASCII. | RISKY; word counts include the notes. | RISKY | RISKY | RISKY | Use bracketed numerals [1] [2], or * † ‡. The notes count toward the word limit. |
| **Text-message thread** | **BREAKS if it uses emoji** (outside latin1, C2). Left/right bubble alignment is impossible. Timestamps and names survive. | BREAKS with emoji (ASCII). | RISKY | RISKY | RISKY | RISKY | Render as "Mom (9:14 PM): …" lines. Describe emoji in words or use ASCII emoticons like ":)". No pipes. |
| **Acrostic carried by bolded first letters** | RISKY. Bold is supported (C1), but the reader may see exported text (C8, INFERENCE). | **BREAKS.** Bold is not saved (U4, PRACTITIONER); ASCII only (U1). | RISKY (not documented) | RISKY | **Depends on each college's rich or plain text setting (T1)**, which the applicant cannot see. | RISKY | Let the letters carry the acrostic without styling, using line-initial capitals. Or say it outright. The form must work with the styling removed. |
| **Recipe** (ingredients plus numbered steps) | RISKY (same as lists). ½ ¼ ¾ and ° survive; **⅓ ⅔ do not** (INFERENCE, cp1252). | Use "1/2 cup" and "degrees" (ASCII). | n/a at 40–50 words; RISKY at 100–200. | RISKY | Uses up lines (T2). | RISKY | Run the ingredient list inline in one sentence. Keep numbered steps as short paragraphs. |
| **Letter form** ("Dear…", "Sincerely") | SAFE. It is prose, and only the salutation line needs a break. | SAFE (ASCII) | SAFE | SAFE | SAFE | SAFE | The lowest-risk creative form; it survives even if line breaks collapse. |
| **Bilingual / code-switching** | Accented Latin letters are SAFE (é ñ ü ç). **Non-Latin scripts BREAK** (C2; COMMERCIAL C-p1 says they show as "?"). ł ş ő also break (INFERENCE). | ASCII advice puts even accents at risk (U1). | RISKY | RISKY | RISKY | RISKY | Romanize the non-Latin words (pinyin, transliteration). College Transitions suggests "phonetic pronunciations" (C-p1). |
| **Italics for titles, inner voice or foreign words** | SAFE in the preview (C1). | BREAKS (U4) | Unknown | Unknown | Depends on the college (T1) | Unknown | Use quotation marks. Do not let meaning depend on italics outside the Common App. |
| **Strikethrough / crossed-out words** | BREAKS. Not on the supported list (C1, INFERENCE). | BREAKS | Assume BREAKS | Assume BREAKS | Depends on the college (T1) | Assume BREAKS | Use words instead of styling: write "I almost wrote X" rather than striking X through. Markdown-style ~~X~~ shows up as literal tildes. |
| **Hyperlinks / multimedia** | BREAKS: "linked text will not work" (C1). | BREAKS | Use SlideRoom (M6). | — | — | — | Use an upload or portfolio channel. |
| **Table / two-column / pipe-separated layout** | BREAKS. The pipe is banned (C3) and there is no table support. | BREAKS | BREAKS | BREAKS | BREAKS | BREAKS | Never use in essay boxes. |

**Limit-unit traps that decide whether a form fits:**
- **Common App, UC, Coalition and QuestBridge limit words. UT Austin's short answers limit lines (T2).** Under a line limit, poems, scripts, lists and text threads are expensive, because every blank line and short line costs as much as a full one.
- **MIT hard-rejects over-limit text (M1).** Its 40–50-word boxes cannot hold a list or poem with any structure. Keep creative forms to the 100–200-word essays.
- **UC's Additional Comments limit is 550 characters, not words (U2).**
- **Word counting differs across portals and from Word or Google Docs.** No portal documents its counting method. The only official data point is MIT's old portal, where contractions and hyphenated words counted as 2–3 words (M3). Tokens common in creative forms ("—", "1.", "NAME:", timestamps) may count as words. The rule: **trust the portal's own counter** (M4's advice) and leave slack.

**Permission is not the same as survival.** Several institutions explicitly invite unconventional pieces: Common App prompt 7, "one of your own design" (C12); Georgetown, "a brief personal or creative essay" (G1); UChicago's creative-writing uploads (G5). That permission says nothing about formatting. UC's guide says readers are "not looking at style or structure" (U3), so a form whose value lives in its layout is working against UC's stated reading stance.

**Upload channels are a different road.** Work whose meaning depends on layout, such as concrete poetry, a real screenplay format or a zine, belongs in an upload channel, not an essay box:
- UChicago's self-upload through the UChicago Account (G5)
- MIT's SlideRoom creative portfolios (M6)
- Stanford's Arts Portfolio, fine and performing arts only (G3)
- Common App member "File upload" and Portfolio questions, where a college sets them up (C10, C11)
- Caltech's Portfolio page (G4; not read)

The limits:
- **UC does not review unsolicited supplemental material (U3).**
- ApplyTexas had no general document upload beyond the essay as of 2024 (T1).
- Uploads are optional and reviewed at the college's discretion. They supplement the essay; they do not replace it.

**Board rule to adopt.** Before praising a creative form, the board should run the **"plain-text test."** Remove all bold, italics, indentation and single line breaks, and turn every non-cp1252 character into "?" on the Common App or every non-ASCII character on UC. The essay must still work. If it does not, the form is a portal risk, and the applicant should check the PDF preview (Common App C1; Scoir S1) before submitting.

---

## 4. Not found officially (with searches run)

| Question | Searches / places checked |
|---|---|
| Common App: are **single line breaks** (within a paragraph) preserved? Are blank-line paragraphs preserved or auto-inserted? | Common App applicant help-center searches ("essay formatting", "paragraph", "preview essay", "italics", "special characters", "question marks", "emoji", "foreign language characters", "known issues"); member help-center searches ("rich text", "essay formatting", "bold", "essay PDF", "special characters"); commonapp.org essay-prompts page, 2026–27 prompt blog, first-year guide, first-year toolkit, and its Essays and App Dictionary PDFs. Only COMMERCIAL claims were found (C-p1). |
| Common App: **indentation and tab** behavior | Same as above. COMMERCIAL only (C-p1). |
| Common App: **how words are counted** (hyphens, dashes, numerals) | Help-center articles C4, "Word Count", "Is there a specific word count for the essay?" (Jul 28, 2026: no counting method given). Only a COMMERCIAL SNIPPET (C-p3), with conflicting claims. |
| Common App: whether **readers see the PDF or exported text**, and whether bold and italic survive in data exports | Member articles C8, C9 and C10; Slate KB C13. Both channels exist, but rendering is not documented. |
| Common App: whether formatting applies to **"Short answer"** member questions (C1 names only "long answer questions") | Member question-configuration article C10. |
| UC: **bold/italic handling, the special-character warning, and auto-conversion** | UC PIQ page, the 2026–27 counselor deck, the PIQ guide PDF, the "Filling out the application" page, the 2019 transfer user guide, and a site search of universityofcalifornia.edu for "special characters". Found only PRACTITIONER U4. |
| UC: **word-count method** | Same UC sources. None found. |
| MIT (current portal since 2020): **formatting, line breaks, characters, counting method** | mitadmissions.org FAQ index and FAQ-topic "application" listing; essays page; site searches for "italics", "formatting", "line breaks" and "word count". Only 2011–2013 old-portal blogs (M3, M4). |
| Coalition/Scoir: **any formatting behavior** | Scoir Help Center search "essay formatting"; the Scoir how-to-apply article; Coalition essays page and FAQ. |
| ApplyTexas: **applicant-facing formatting guidance** for the redesigned app, and **which colleges choose rich vs plain text** | THECB running list (T1, college-facing, 2024); UT Austin essays page; searches for ApplyTexas "plain text", "special characters" and "eighty-character lines" (legacy, COMMERCIAL only). |
| QuestBridge: **formatting, character set, essay limits** | AskQB Zendesk API searches ("formatting", "special characters", "word count", "copy and paste", "essay", "cut off", "character limit", "preview application", "writing section", "bold italics"); the Match Requirements Guide; the Detailed Essay FAQs. The limits (800/500 words) appeared only in COMMERCIAL snippets and were not verified. |
| Georgetown Application: **how essay boxes handle formatting**, and whether essays are typed or uploaded | Georgetown requirements page (G1); site search of georgetown.edu. |

**Caveats.**
- Several Common App articles are old (2023–2024) but still live. C3, the pipe warning, is dated 2026 and is the freshest.
- The cp1252 survival list is an inference from two official statements. The applicant's PDF preview is the only ground truth.
- No portal was tested hands-on. That would take a logged-in applicant account, which is out of scope.

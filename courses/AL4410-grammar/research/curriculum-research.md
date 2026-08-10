# AL4410 Curriculum Research — Design Rationale

**Research date:** 2026-08-09

## Executive conclusion

The strongest independent-study approximation of DIU AL4410 is a **data-analysis and grammar-description course**, not a formal syntax survey and not an Arabic grammar course.

DIU publicly defines AL4410 around:

- analyzing/describing basic morphological and syntactic issues;
- numerous practical exercises;
- a large variety of languages;
- word classes;
- allomorphy;
- inflectional and derivational morphology;
- phrases, clauses, and sentences.

The curriculum therefore uses:

1. **Bickford** as the primary field-analysis/grammar-sketch spine;
2. **Thomas Payne, _Exploring Language Structure_** as the major secondary problem-solving text;
3. **Leipzig Glossing Rules** as the presentation baseline;
4. **Lieber** selectively for modern morphology depth;
5. **WALS and Grambank** only after human analysis for typological comparison;
6. **MIT 24.900** for additional introductory morphology/syntax practice;
7. **MIT 24.902** only as theory-heavy stretch work;
8. **Egyptian Arabic scholarship after independent analysis**;
9. **FLEx/CAMeL Tools** as auditable analysis aids after manual skill is established;
10. a cumulative **grammar sketch** rather than disconnected homework.

---

# 1. DIU scope and boundary

DIU currently lists AL4410 as a 4-credit undergraduate course offered Spring/Summer/Fall. Its public description emphasizes practical exercises and basic descriptive analysis across many natural languages.

That wording matters. It points toward **transferable analytical skill** rather than mastery of one formal syntactic framework.

DIU separately offers AL5313 Advanced Grammatical Analysis. Its public description says that course incorporates syntactic typology and formal syntax using a simplified Lexical Functional Grammar framework.

DIU also offers AL5312 Discourse Analysis, covering sentence structure in discourse, macrosegmentation, information structure, participant reference, salience, transitivity, and paragraph analysis.

**Boundary decision:** AL4410 should build descriptive morphological/syntactic competence, but should not attempt to recreate AL5313 formal grammar or AL5312 discourse analysis.

---

# 2. Why Bickford remains the primary text

SIL International's current 2022 casebound issue of J. Albert Bickford's _Morphology and Syntax: Tools for Analyzing the World's Languages_ is unusually aligned with DIU AL4410.

Its table of contents covers:

- morphemes and hypotheses;
- introductory morphology;
- constituent structure, syntactic categories, grammatical relations;
- phrase structure and lexicon;
- noun phrase structure;
- verbal valence and obliques;
- inflection and derivation;
- suppletion/morphophonemics;
- nonlinear affixation;
- variable constituent order;
- questions and commands;
- case/agreement;
- clitics and word division;
- passive/voice;
- embedded and relative clauses;
- linguistic writing;
- grammar-sketch preparation.

Albert Bickford's DIU faculty profile also documents decades of teaching introductory morphology/syntax analysis in SIL/DIU contexts, reinforcing the text's relevance to the instructional tradition this independent study is approximating.

**Decision:** Bickford is the course spine.

---

# 3. Why Thomas Payne is the major secondary text

Thomas Payne's _Exploring Language Structure: A Student's Guide_ is specifically designed to teach beginning students how to analyze morphology and syntax step by step. Cambridge states that it includes almost 100 practical exercises based on diverse world-language data.

Its ten chapters map cleanly onto the course:

- morphology/syntax foundations;
- morphological processes;
- morphophonemics;
- word classes;
- subclasses;
- constituent structure;
- typology;
- grammatical relations;
- voice/valence;
- multi-clause constructions.

Payne also maintains an official page of additional exercises organized by chapter.

**Decision:** use Payne heavily for alternative explanations and cross-linguistic problems instead of buying several separate introductory syntax/morphology textbooks.

---

# 4. Why Lieber is selective rather than core

Rochelle Lieber's _Introducing Morphology_, 3rd ed. (2021), is a current undergraduate morphology text with hands-on analysis, cross-linguistic data, inflection, derivation, morphological typology, and interfaces with syntax/phonology.

It is excellent for updating terminology and deepening morphology, but AL4410 must divide time between morphology and syntax.

**Decision:** assign selected chapters only, particularly inflection, typology, and the morphology-syntax/phonology interfaces. Do not let morphology consume the entire 4-credit study.

---

# 5. Why WALS and Grambank are comparison tools, not answer keys

WALS provides descriptive typological chapters/maps on phenomena such as:

- locus of marking;
- case systems;
- word order;
- adposition/noun phrase order;
- relative-clause order;
- inflectional synthesis.

Grambank covers 2,467 language varieties and 195 grammatical features across 215 families plus isolates.

These resources are valuable for challenging assumptions and selecting breadth targets, but a database code is not an analysis.

**Decision:** require an **analysis-first typology rule**:

1. solve/analyze the primary data;
2. freeze the description;
3. inspect WALS/Grambank;
4. compare the language to broader patterns;
5. revise only when evidence, not database authority, justifies revision.

---

# 6. Glossing and linguistic writing

The Leipzig Glossing Rules provide a widely used baseline convention for interlinear morpheme-by-morpheme glosses. They deliberately permit flexibility and do not replace language-specific explanation.

AL4410 needs consistent examples because the final grammar sketch must make its evidence auditable.

**Decision:** introduce Leipzig conventions in Week 1 and revisit them in Weeks 7 and 16. Require a project-specific abbreviation list and explicit documentation of any deviations.

---

# 7. MIT material: useful, but carefully bounded

## MIT 24.900 Introduction to Linguistics

The 2022 course has undergraduate morphology and syntax lectures/problem sets. One syntax assignment explicitly asks students to gather and present data from the language they are studying, including interlinear presentation.

This is highly compatible with the Egyptian Arabic consultant component.

## MIT 24.902 Syntax

The public course includes eight problem sets and extensive lecture material, but it is a dedicated syntax course whose aim includes theoretical discoveries and formal syntactic phenomena.

**Decision:** 24.900 can supply core supplemental practice; 24.902 is optional stretch material only. AL4410 is not a generative syntax course.

---

# 8. Egyptian Arabic reference strategy

## Core reference

Abdel-Massih, Abdel-Malek & Badawi, _A Reference Grammar of Egyptian Arabic_ (Georgetown University Press reprint, 2009; original 1979).

The grammar covers phonology, morphology, and syntax and is aimed at intermediate/advanced students. Because it is alphabetically organized by grammatical term rather than as a linear course, it works best as a **post-analysis reference**.

## Formal/advanced comparison

Aoun, Benmamoun & Choueiri, _The Syntax of Arabic_, covers clause structure, subjects, agreement, negation, wh-interrogation, restrictive relatives, clitic-left dislocation/focus, and the left periphery. Cambridge describes it as valuable for graduate students and syntactic theorists.

**Decision:** use only selected chapters after descriptive analyses are frozen; formal derivations are not required for AL4410 mastery.

## Stage-specific sources

- Benmamoun on Egyptian Arabic tense morphology → after Week 4 TAM paradigms.
- Soltan on Cairene sentential negation → after Week 13 negation analysis.
- Aoun/Benmamoun/Choueiri on agreement, wh-questions, relatives → after matching analyses.

---

# 9. Nonlinear morphology and computational comparison

Egyptian Arabic makes AL4410 unusually strong for nonconcatenative morphology, but the learner must avoid treating traditional root-pattern labels as self-validating.

CAMeL Tools currently ships an Egyptian Arabic morphology database (`calima-egy-r13`) and morphological analyzer/tokenizer support.

**Decision:** manual paradigm analysis comes first. CAMeL Tools is then used as an external analysis system to audit:

- segmentation;
- roots/stems;
- POS/features;
- ambiguity;
- tokenization;
- disagreement with speaker/corpus evidence.

This converts software use into a research exercise rather than an answer lookup.

---

# 10. FLEx as an optional field-linguistics tool

SIL FieldWorks Language Explorer supports:

- lexical entries;
- interlinear text;
- morpheme segmentation/glossing;
- grammatical categories;
- suggested analyses based on prior work;
- morphological parsing;
- concordance;
- grammar-sketch generation.

SIL explicitly distinguishes approved human analyses from parser-predicted analyses.

**Decision:** introduce FLEx only after the learner can segment/gloss manually. It should reinforce reproducible corpus analysis, not hide the analytical process.

---

# 11. AI research findings relevant to AL4410

Recent ACL research reinforces a useful experimental direction: automatic interlinear glossing can reduce documentation workload, but performance depends heavily on structured examples/corpora and may still create trust/interpretability problems.

In 2026 work on Mapudungun, structured annotated corpus retrieval outperformed less targeted resource configurations. A 2026 field-linguistics paper on Jungar Tuvan found gains from retrieval-augmented prompting and hybrid neural/LLM workflows, while also noting that dictionary resources could sometimes hurt performance.

**Decision:** the AL4410 AI benchmark should measure not merely accuracy but:

- segmentation alignment;
- gloss alignment;
- morphology/feature correctness;
- ambiguity preservation;
- evidence traceability;
- correction effort;
- hallucinated categories or analyses.

This has direct relevance to the long-term AI-assisted Bible-translation research thread.

---

# 12. Problem-set design

The course needs four practice layers:

1. **free review** — _Essentials of Linguistics_;
2. **core field-analysis practice** — Bickford + Payne;
3. **typological/stretch analysis** — selected MIT/WALS-informed problems;
4. **quarantined assessment datasets** — unseen, closed-AI.

At least half of graded formal datasets remain non-Arabic.

The breadth requirement should include structurally different systems, not merely many language names.

---

# 13. What the course intentionally does not try to master

AL4410 does **not** require mastery of:

- Lexical Functional Grammar;
- Minimalist/generative syntax;
- X-bar/merge/movement theory beyond basic literacy where useful;
- deep syntactic typology;
- discourse information structure;
- full reference-grammar writing;
- advanced corpus annotation engineering;
- computational morphology model development.

These are future-study directions.

---

# 14. Resource acquisition priority

## Tier 1 — essential
1. J. Albert Bickford, _Morphology and Syntax: Tools for Analyzing the World's Languages_.
2. Thomas E. Payne, _Exploring Language Structure: A Student's Guide_.

## Tier 2 — strongly useful
3. _A Reference Grammar of Egyptian Arabic_ — for post-analysis comparison throughout the longitudinal project.

## Tier 3 — optional modern deepening
4. Rochelle Lieber, _Introducing Morphology_, 3rd ed.

## Tier 4 — free
5. Leipzig Glossing Rules.
6. _Essentials of Linguistics_ morphology/syntax chapters.
7. Payne's official additional exercises.
8. MIT OCW 24.900 materials.
9. WALS Online / Grambank.
10. SIL FieldWorks.
11. CAMeL Tools.

## Tier 5 — advanced/post-analysis reference
12. Aoun, Benmamoun & Choueiri, _The Syntax of Arabic_.
13. selected advanced journal chapters/articles as needed.

Do not buy a stack of theoretical syntax textbooks for this prerequisite.

---

# 15. Final design principle

AL4410 should force this recurring sequence:

`data → segmentation → paradigm/structure → diagnostics → hypothesis → counterexamples → elicitation → interlinear evidence → cross-linguistic comparison → published comparison → revision`

If the learner can recite Arabic paradigms or draw English syntax trees but cannot perform that sequence on unfamiliar data, the study has failed.

# Project — AI and Automated Grammar-Analysis Benchmark

## Research question

How reliably can current AI and structured language-analysis systems infer or assist with basic morphology and syntax from finite, low-resource-style datasets, and how much human correction/evidence checking do they require?

This project distinguishes **general LLM reasoning** from **language-specific structured analyzers** and from **automatic interlinear glossing**.

## Dataset mix

Use 8–12 datasets spanning:
- morpheme segmentation/allomorphy;
- inflection;
- derivation;
- nonlinear morphology;
- word classes;
- constituency;
- grammatical relations/valence;
- clause structure;
- complex sentences.

At least half must be non-Arabic and should represent different typological profiles.

## Systems to compare

### A. Human baseline
Independent closed analysis.

### B. General AI/LLM
One or more current models given only the evidence available to the human analysis.

### C. Egyptian Arabic structured morphology tool
For Egyptian Arabic morphology, use CAMeL Tools with its Egyptian Arabic morphology resources where appropriate.

This system is not directly comparable to an LLM on arbitrary languages, so report it as a **specialist comparator**.

### D. Optional automatic interlinear glossing system/workflow
If a legitimately accessible research implementation exists when the study is run, evaluate a dedicated glossing/segmentation workflow separately.

## Core procedure

1. Human analysis without AI/analyzer/reference lookup.
2. Freeze response and confidence ratings.
3. Grade against authoritative source/key where available.
4. Preserve exact input evidence.
5. Run AI/system analysis.
6. Preserve raw output.
7. Score using task-specific metrics.
8. Test a second condition requiring the AI to point to supporting tokens/examples.
9. Where relevant, provide a small structured corpus/few-shot example set and compare performance.
10. Record actual human correction time, not merely accuracy.

## Morphology metrics

Track separately:
- boundary precision/recall or exact segmentation match where feasible;
- lexical gloss correctness;
- grammatical gloss/feature correctness;
- allomorph grouping;
- lemma/root/stem analysis where relevant;
- inflection vs. derivation classification;
- ambiguity preserved vs. collapsed;
- alignment between segments and glosses;
- correction effort.

## Syntax/descriptive metrics

Score:
- category diagnosis;
- constituency claims;
- grammatical relations vs. semantic roles;
- argument/valence structure;
- order generalizations;
- construction identification;
- counterexample handling;
- evidence citation;
- competing-analysis awareness;
- unsupported certainty.

## Failure taxonomy

Track:
- invented morphemes or meanings;
- segmentation forced by familiar-language assumptions;
- category labels without diagnostics;
- confusion of semantic role and grammatical relation;
- ignored counterexamples;
- overconfident claims from sparse data;
- inability to preserve ambiguity;
- failure to align glosses to segments;
- errors caused by orthography;
- correct pattern detection with incorrect explanation;
- importing a known grammar rather than analyzing supplied evidence;
- silently normalizing speaker data;
- unsupported claims about cultural/naturalness judgments.

## Egyptian Arabic specialist comparison

For selected original paradigms/constructions compare:

1. student's manual analysis;
2. CAMeL Tools analysis/tokenization where applicable;
3. LLM analysis;
4. published description after freeze;
5. follow-up consultant evidence.

Useful questions:
- Does CAMeL segmentation match the grammatical word/morpheme distinctions needed for the course?
- Which feature labels are annotation conventions rather than independently established grammatical facts?
- Does the LLM reproduce standard Arabic knowledge rather than the supplied Egyptian data?
- Which system exposes ambiguity best?

## Research-context readings — only after experimental design is frozen

Recent field-linguistics/NLP work should inform interpretation without contaminating the experiment design.

Recommended context:
- 2026 AmericasNLP work on LLM/RAG interlinear glossing for Mapudungun, which reports strong benefits from small structured annotated corpora and weaker results from some resource combinations;
- 2026 FieldMatters work on a hybrid neural/LLM glossing pipeline for Jungar Tuvan, including evidence that retrieval augmentation can help while dictionaries can sometimes hurt performance;
- 2025 SIGMORPHON work on word-by-word LLM prompting for low-resource interlinear glossing.

Do not assume findings from one language/model transfer automatically.

## Final report

Target: 4,000–6,000 words plus scoring/correction-effort tables.

Required conclusions:
- which tasks can be accelerated safely;
- which errors are difficult for a novice to detect;
- whether evidence-grounded prompting improves trustworthiness;
- when a structured analyzer outperforms a general model;
- whether automatic suggestions reduce or increase total correction burden;
- where native-speaker/linguist judgment remains indispensable;
- implications for AI-assisted language documentation and Bible translation.

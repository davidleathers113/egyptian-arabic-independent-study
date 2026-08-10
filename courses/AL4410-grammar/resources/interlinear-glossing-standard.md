# AL4410 Interlinear Glossing Standard

## Purpose

Make every grammatical claim inspectable. The final grammar sketch should show enough structured evidence that another linguistically trained reader can understand how an analysis was derived.

## Baseline convention

Use the Leipzig Glossing Rules as the default interlinear convention, with project-specific additions documented explicitly.

Canonical example shape:

```text
(12)  vernacular/or-transliteration line
      morpheme-segmentation line
      morpheme.gloss-3SG-PST line
      ‘free translation’
```

Arabic script may be retained as an additional line when useful, but the analysis must remain readable to someone who can follow the transcription/gloss conventions.

## Required practices

1. Number examples uniquely within a paper/project.
2. Preserve the original recorded/source form in private data.
3. Do not silently regularize the consultant's production to a textbook form.
4. Segment only where an analysis is justified.
5. Align segmentation and gloss boundaries consistently.
6. Use small caps/standard abbreviations for grammatical categories where practical.
7. Provide a project abbreviation list.
8. Distinguish lexical gloss from grammatical category/features.
9. Mark uncertain segmentation/glossing explicitly in working notes.
10. State when a zero morpheme or unexpressed category is an analysis rather than directly observed form.
11. Do not let Arabic spelling determine morpheme boundaries automatically.
12. Do not treat spaces produced by an automatic tokenizer as proof of grammatical wordhood.

## Project-specific conventions

Create a living file for:
- transcription system;
- Arabic script conventions;
- clitic boundary conventions;
- equals sign vs. hyphen policy;
- fused feature/gloss conventions;
- zero markers if used;
- irregular forms;
- uncertain analyses;
- consultant/corpus token identifiers.

Any deviation from Leipzig conventions must be stated, not hidden.

## Evidence tiers

For major grammatical generalizations, identify whether the supporting example is:

- **NAT** — spontaneous/natural speech;
- **ELIC** — elicited production;
- **JUDG** — acceptability/contrast judgment;
- **TEXT** — approved textual/corpus example;
- **REF** — published reference example;
- **GEN** — constructed analytical example checked with consultant;
- **AUTO** — generated/analyzed by software and not yet human-verified.

`AUTO` examples may never serve as sole evidence for a final claim.

## Minimal metadata for examples

Where privacy allows, retain privately:
- token/session ID;
- speaker ID;
- date;
- elicitation/natural context;
- recording timestamps;
- analysis version;
- consultant verification status.

The public repository may contain de-identified references rather than raw private material.

## Revision discipline

Never overwrite a material segmentation/gloss change without preserving the reason in version history or analysis notes.

The goal is not merely tidy examples. It is an auditable path from speech/data to grammatical description.

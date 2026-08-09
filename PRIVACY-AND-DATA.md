# Privacy and Data Policy

This is a **public repository**. The study involves a real native Egyptian Arabic speaker, so the default is to minimize public exposure.

## Never commit by default

- raw or working audio containing the consultant's voice;
- video of the consultant;
- signed or recorded consent artifacts;
- full name, phone, email, address, employer, immigration information, or other identifiers;
- private lesson notes containing personal information;
- unredacted AI transcripts containing private details;
- copyrighted textbook PDFs/scans;
- private assessment answer keys before use.

## Allowed public-safe material

- pseudonymous speaker IDs such as `SPK001`;
- broad dialect/region information when appropriate and consented;
- de-identified acoustic measurements;
- short audio excerpts only when separately approved for public use;
- original analyses and figures;
- elicitation protocols and metadata schemas;
- public-source quotations within normal copyright limits;
- bibliographic citations and links.

## Consent levels

Track consent privately and distinguish:
1. **Private educational analysis** — recording and analysis for the independent study.
2. **Public educational use** — permission to publish selected examples in videos/blogs/repository artifacts.
3. **Research/AI reuse** — permission for future research, model evaluation, dataset publication, or external sharing.

Permission at one level does not imply permission at another.

## Storage model

Recommended private working structure:

```text
Egyptian-Arabic-Fieldwork-PRIVATE/
  consent/
  master-audio/
  working-audio/
  private-metadata/
  private-transcripts/
```

Recommended public repository exports:

```text
data-public/
  metadata-schema/
  deidentified-measurements/
  approved-excerpts/
```

## Master audio

Original master recordings are immutable. Analysis uses copies. Never run noise reduction, normalization, compression, EQ, AI enhancement, or destructive editing against the archival master.

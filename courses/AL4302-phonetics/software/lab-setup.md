# AL4302 Software and Lab Setup

## Required

### Praat
Official site: https://www.fon.hum.uva.nl/praat/

Use for:
- waveform/spectrogram inspection;
- pitch;
- formants;
- duration;
- segmentation and TextGrids;
- acoustic measurements;
- later scripting/automation.

Praat operates locally and its official documentation states that it does not automatically upload analysis data.

### Audacity
Official site: https://www.audacityteam.org/

Use primarily for:
- recording when convenient;
- level checks;
- creating working copies;
- non-destructive preparation/export.

## Optional/later

### ELAN
Official site: https://archive.mpi.nl/tla/elan

Introduce when longer connected-speech recordings need time-aligned multilayer annotation.

## Public repo vs. private lab

The repository may contain:
- Praat scripts;
- public-safe TextGrid templates;
- de-identified measurement CSVs;
- screenshots with no private speech content.

Raw audio and private annotations remain outside Git.

## Suggested Praat tier progression

Early course:
- `utterance`
- `arabic`
- `broad_IPA`
- `notes`

Later as justified:
- `narrow_IPA`
- `word`
- `stress`
- `phonetic_event`

Do not add annotation tiers merely because the software allows them.

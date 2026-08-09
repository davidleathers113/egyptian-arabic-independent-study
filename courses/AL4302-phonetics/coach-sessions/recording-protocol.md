# Recording Protocol

## Canonical master format

- WAV
- linear PCM
- 48,000 Hz sample rate
- 24-bit when supported by the recorder/editor
- mono for the standard single-speaker setup

## Levels

Run a brief level test with representative loud speech. Aim for healthy headroom and avoid clipping; approximately -12 to -6 dBFS peaks is a useful practical target, not a rigid grading criterion.

## Placement

For a dedicated microphone, begin around 6–10 inches from the speaker and slightly off-axis to reduce plosive blasts. Document distance/angle and keep them reasonably consistent for comparable acoustic measurements.

## Environment

Prefer a quiet, furnished room with limited reverberation. Document unavoidable HVAC, traffic, fan, or room noise.

## Master/working split

`*_MASTER.wav` is immutable.  
`*_WORKING.wav` may be trimmed or processed for analysis.

Never normalize, denoise, EQ, compress, enhance with AI, or otherwise alter the master.

## Session naming

`EA-DL-###-YYYYMMDD-descriptor_MASTER.wav`

Associated files inherit the base ID:
- `_WORKING.wav`
- `.TextGrid`
- `_metadata.csv`
- `_notes.md`

## Private storage

Audio is excluded from this public repository by default. See the root privacy policy.

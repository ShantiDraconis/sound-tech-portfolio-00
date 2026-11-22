# QLab + LTC integration demonstration

**Design only — no QLab workspace or live hardware test has been performed here.**

## Inputs and assumptions
QLab version, licensing, audio interface, LTC frame rate, receiving console, wiring and latency are TBD and must be confirmed on authorized equipment. Use original or rights-cleared audio only.

## Build sequence
1. Create an empty workspace and name cue groups PRESHOW, SHOW, POSTSHOW.
2. Populate cues using `examples/qlab_synthetic_cue_sheet.csv`.
3. Set the correct frame rate and define the timecode source; verify the exact QLab-version support before configuring.
4. Route audio through approved outputs; document the interface, without publishing private vessel configuration.
5. Verify timecode reception and cue triggering with a test clock and receiving console.
6. Run repeated starts, stops, cue skips, blackout recovery and manual fallback tests.
7. Log expected versus observed trigger timestamps and compute frame drift.
8. Archive an original workspace, synthetic screenshots and test logs before claiming reproducibility.

## Acceptance matrix
| Test | Pass criterion | Actual |
|---|---|---|
| Manual cue | Correct audio starts/stops | NOT RUN |
| LTC lock | Receiver reports stable lock | NOT RUN |
| Cue alignment | Measured drift within project-specific tolerance | NOT RUN |
| Recovery | Operator can restore show-safe state | NOT RUN |

Never use copyrighted show files or unlicensed tracks in the published demonstrator.

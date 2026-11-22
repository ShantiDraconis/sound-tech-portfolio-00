# QLab and LTC show-control construction — reproducible design

**Evidence classification: AUTHOR-REPORTED EXPERIENCE + ORIGINAL DEMONSTRATION DESIGN. Not independently verified employer documentation.**

## Situation and scope
Reported experience: QLab, show playback, sound-light integration and timecode in cruise entertainment, including cross-department diagnosis of synchronization issues. No independently reviewed QLab workspace file or show license has been provided.

## Method and technical decisions
Build an ORIGINAL demonstrator: (1) create a new QLab workspace; (2) define audio cue groups for preshow, show and postshow; (3) add synthetic audio placeholders licensed for redistribution; (4) define LTC source and receiving show-control endpoint; (5) map cue start times to a documented cue sheet; (6) rehearse start, stop, hold and recovery; (7) document latency and drift tests; (8) validate manual fallback. QLab's exact timecode features and hardware routing must be confirmed against the installed version and authorized equipment.

## Functional architecture (illustrative)
```text
[QLab workspace] --> [Audio output] --> [Sound console] ; [LTC source] --> [Timecode distribution] --> [Lighting controller]
```

## Traceability and verification
Create and attach an original QLab workspace, screenshot of a synthetic cue list, source-attribution manifest, test recordings and run logs. The design here is not proof that a workspace was built or tested.

| Verification item | Expected result | Current status |
|---|---|---|
| Reproducible procedure | Another technician can follow the steps | DOCUMENTED, NOT FIELD-TESTED |
| Source evidence | Authorized records with date and role | PENDING |
| Operational result | Observed recovery, acceptance or show readiness | AUTHOR-REPORTED / PENDING |
| Employer approval | Public redistribution permission | PENDING |

## Leadership and management transfer
The operational lesson is to make failure modes observable, separate evidence from assumptions, prioritize safe show continuity, define responsibility and preserve a clear handover. These are transferable to fleet-level standardization, but **do not establish prior fleet-management authority**.

## Privacy and professional boundaries
No private medical or trauma information, workplace allegations, personnel names, access credentials or confidential show files belong in this public-facing case study.

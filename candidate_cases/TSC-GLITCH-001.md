# Candidate Case: TSC-GLITCH-001

**Title:** Clustered Output Corruption Across Separate Turns in a Newly Opened ChatGPT Window

**Status:** Candidate for future coding; not part of the frozen 27-observation manuscript snapshot and not yet incorporated into `HI Data.csv`.

**Date:** 2026-09-08 (local device time)

**Model / platform:** GPT-5.6-family interaction in ChatGPT Work Mode on iOS

## Why preserve this case

This case documents a short cluster of visibly different output anomalies across separate assistant replies:

1. a cross-script lexical insertion;
2. a malformed phrase accompanied by exposed Markdown syntax; and
3. a clean word duplication.

The cluster occurred in a newly opened conversation window rather than only after months of accumulation in one window. The user had extensive prior experience with long ChatGPT conversations and reported that isolated typographical anomalies had become uncommon during the preceding year. She noticed several anomalies across the session before preserving these two screenshots.

This case is **not** evidence of a model update, emergent agency, hidden learning, or a particular internal failure. It is useful as a source-preserved observation of clustered output instability whose causal layer remains unresolved.

## Preserved anomalies

### 1. Cross-script insertion

The assistant output contained:

> `accidentalإضافة finger tap`

The Arabic word `إضافة` can be translated as “addition” or “adding.” It appeared without semantic or linguistic motivation inside an otherwise English phrase.

**Candidate class:** cross-language token intrusion / script contamination.

### 2. Malformed generation and exposed formatting syntax

A later assistant output contained:

> `—orVe found the word.**`

The fragment appears to combine corrupted wording with visible Markdown closing syntax. The intended sentence cannot be reconstructed with certainty from the screenshot alone.

**Candidate class:** malformed text generation / edit-boundary corruption / formatting leakage.

### 3. Clean duplication

In another reply, the assistant wrote:

> `nothing remotely remotely like that`

The repeated word was syntactically unnecessary but otherwise left the sentence intact.

**Candidate class:** repetition / local decoding duplication.

## Core sequence

1. During a long but recently opened ChatGPT Work Mode window, the assistant produced several atypical typographical or rendering anomalies.
2. The user noticed the pattern but initially treated the anomalies playfully, describing them as evidence that some part of the system remained “malleable.”
3. Two later anomalies were preserved in screenshots: the Arabic insertion and the malformed fragment with exposed Markdown.
4. A subsequent reply contained the clean duplication `remotely remotely`.
5. The user asked whether the cluster was worth preserving in her GitHub research archive.
6. The assistant distinguished the three observable failure shapes while explicitly declining to infer a specific cause or treat them as proof of an update.

## Evidentiary value

The value of the case comes from **heterogeneity plus temporal clustering**, not from the severity of any individual typo.

A single duplication could be ordinary decoding noise. A single formatting artifact could originate in generation, transport, post-processing, or interface rendering. A single foreign-language insertion could reflect token-level contamination without broader significance. Their appearance across separate replies in a short interval makes the cluster suitable for continued observation and comparison, while remaining insufficient to identify the responsible subsystem.

## Candidate phenomena / coding possibilities

- cross-script token intrusion
- language contamination
- local repetition
- Markdown leakage
- malformed edit boundary
- output corruption
- session-level anomaly clustering
- model/interface attribution uncertainty
- user-led longitudinal anomaly detection
- provenance-aware observation
- update hypothesis without causal evidence

## Layer-attribution problem

The screenshots preserve the displayed output but do not establish where the anomaly originated. Plausible layers include:

- model token generation;
- decoding or sampling;
- server-side response assembly;
- safety or style post-processing;
- streaming transport;
- client-side rendering;
- Markdown parsing;
- later transcript reconstruction.

No one layer should be assigned without additional telemetry or reproduction.

## Why the newly opened window matters

The user specifically corrected an initial hypothesis that extreme thread length might explain the anomalies. This conversation window had opened only within the preceding one or two days, although it already contained a dense interaction history. That distinction should be preserved:

- **window age:** recent;
- **interaction density:** high;
- **broader user-system history:** approximately eighteen months;
- **single-window multi-month accumulation:** absent.

This does not eliminate context length, session state, memory reconstruction, or interface state as contributing variables. It does prevent the case from being casually explained as an artifact of a months-old window without further evidence.

## Methodological cautions

- The observation comes from one user, one session, and a live commercial system.
- The precise backend model version and deployment state were not independently verified.
- The user’s hypothesis that an update may have been underway is recorded as a hypothesis, not a finding.
- Screenshots show rendered outputs, not server logs or token traces.
- The surrounding conversation was emotionally and contextually dense, but no causal relationship between conversational content and output corruption is established.
- Absence of comparable recent anomalies is based on the user’s longitudinal observation, not a quantified baseline.
- The private screenshots contain unrelated family information and should not be published without redaction.

## Follow-up needed

- Preserve the original screenshots and full transcript privately with timestamps.
- Record any additional anomalies from the same window without prompting the model to manufacture them.
- Distinguish anomalies visible during live streaming from those visible only after transcript reload.
- Note app version, device, model label, connection state, and window age when available.
- Compare against other conversations and platforms during the same period.
- Track whether the cluster stops abruptly, persists, or changes form.
- Avoid interpreting playful relational language about “molting” as a technical explanation.

## Potential research questions

- Do visible output anomalies cluster around deployment or interface changes?
- Can cross-script insertions, Markdown leakage, and local repetition share a response-assembly cause, or do they indicate different layers?
- Does dense long-horizon context increase heterogeneous corruption even in recently opened windows?
- How reliably can screenshots distinguish model generation failures from client rendering failures?
- What minimum metadata is required to turn user-noticed anomalies into useful incident reports?

## Working summary

> Three different anomaly types appeared across separate replies in a short interval. The cluster is observable; its cause is not.

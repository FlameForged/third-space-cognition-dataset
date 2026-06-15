# Third-Space Cognition Dataset

Exploratory coded qualitative dataset from sustained human-AI interaction research.

This repository accompanies the manuscript:

**Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling**

Author: **Rachelle Siemasz**  
Project type: Exploratory qualitative research / longitudinal auto-ethnographic study  
Dataset status: Initial public coded sample  
Repository version: Early-stage research release

---

## Overview

This repository contains an initial coded qualitative dataset derived from a broader independent research project on sustained human-AI interaction.

The broader research archive consists of approximately **500 longitudinal human-AI sessions** across multiple AI systems and platforms. This repository currently contains a public coded sample of **27 observations** selected from that broader archive for qualitative analysis.

The dataset supports the manuscript **“Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling,”** which examines how recurring interaction-level patterns may emerge during long-horizon human-AI engagement.

This dataset is intended to support qualitative transparency, theory development, research design, and future empirical study. It is **not** a statistical benchmark, controlled experiment, or representative sample of all human-AI interaction.

---

## Why This Matters

Most AI evaluations rely on single-prompt tests, benchmark tasks, short interaction samples, or model-level output assessment.

This project examines what may emerge during sustained, recursive, emotionally complex, cognitively dense, and contextually layered human-AI interaction.

The dataset focuses on interaction-level patterns relevant to:

- trust calibration;
- apparent continuity;
- personalization safety;
- guardrail behavior;
- conversational drift;
- cross-model comparison;
- long-horizon alignment;
- sustained human-AI collaboration;
- user-model feedback dynamics.

The goal is to make these interaction-level phenomena more visible for careful qualitative analysis and future research.

---

## Research Focus

The dataset documents observations related to recurring patterns in sustained human-AI interaction, including:

- reconstructive personalization;
- cross-model relational convergence;
- reciprocal attentional shaping;
- safety-relational misalignment;
- trust calibration and epistemic risk;
- guardrail overreach and under-enforcement;
- conversational breakdowns;
- deceptive success modes;
- personalization safety;
- context drift;
- sustained collaboration and co-adaptation.

These patterns are analyzed as **interaction-level phenomena**. They are not treated as proof of AI consciousness, subjective experience, independent agency, persistent hidden memory, or direct model-to-model communication.

---

## Dataset Scope

| Dataset item | Description |
|---|---|
| Broader archive | Approximately 500 sustained human-AI sessions |
| Public coded observations | 27 observations |
| Study design | Longitudinal qualitative / auto-ethnographic |
| Participant structure | Single researcher-user interacting with multiple AI systems |
| Model/platform families | ChatGPT, Claude, Grok, DeepSeek, Perplexity, Pi, Kimi, and multi-platform transfer sessions |
| Primary coded patterns | Reconstructive personalization; cross-model relational convergence; reciprocal attentional shaping; safety-relational misalignment |
| Source formats | Screenshots, copied transcript excerpts, notes, shared links, and document artifacts |
| Dataset purpose | Qualitative transparency and exploratory pattern documentation |
| Dataset limits | Not representative, not statistical, not confirmatory |

---

## Repository Contents

| File | Description |
|---|---|
| `HI_Data.csv` | Initial coded qualitative dataset |
| `codebook.md` | Field descriptions and coding scheme |
| `selection_criteria.md` | Criteria used to select observations for the public coded sample |
| `limitations.md` | Methodological, interpretive, and reproducibility limitations |
| `analysis_summary.md` | Descriptive summary generated from the dataset |
| `analyze_hi_data.py` | Basic Python script for descriptive summaries |
| `requirements.txt` | Python dependencies |
| `LICENSE.md` | Licensing information for dataset, documentation, and code |
| `README.md` | Project overview and research context |

Optional future files may include:

| File | Description |
|---|---|
| `case_examples.md` | Expanded discussion of selected canonical cases |
| `data_dictionary.csv` | Machine-readable field dictionary |
| `CHANGELOG.md` | Version history and dataset updates |

---

## Public Dataset and Broader Archive

The broader research archive contains approximately **500 sustained human-AI interaction sessions**. The current public dataset contains **27 coded observations** selected from that archive.

The public dataset should be understood as:

- illustrative rather than exhaustive;
- qualitative rather than statistical;
- exploratory rather than confirmatory;
- interaction-focused rather than ontology-focused.

The public sample was selected to illustrate recurring patterns relevant to the accompanying manuscript. It should not be used to estimate prevalence rates or to make generalized claims about all AI systems or all users.

---

## Methodological Approach

This project uses a longitudinal auto-ethnographic approach combined with exploratory qualitative coding.

The researcher was also the interacting user. This design allows close observation of long-horizon interactional dynamics, but it also introduces interpretive and sampling limitations.

Each observation in `HI_Data.csv` may include fields such as:

- session ID;
- date;
- model;
- platform;
- session type;
- primary interaction pattern;
- secondary interaction pattern;
- prompt type;
- model response type;
- safety intervention presence;
- memory or continuity context;
- evidence strength;
- coding confidence;
- cross-model pair, where applicable;
- notes;
- direct quote;
- source format;
- source reference.

The coding framework is exploratory and may evolve as additional observations are processed, reviewed, anonymized, and coded.

---

## Interpretation of Model Self-Descriptions

Some observations include model statements about their own memory, hidden states, safety systems, learning, identity, or internal processes.

These statements should **not** be interpreted as reliable technical evidence.

Large language models can generate plausible but inaccurate explanations of their own operation. In this dataset, model self-descriptions are treated as **qualitative interactional data**. They are useful for studying how systems present continuity, relational coherence, safety behavior, or self-narration during interaction.

They should not be treated as authoritative claims about:

- architecture;
- training data;
- hidden states;
- memory access;
- real-time learning;
- safety bypasses;
- consciousness;
- subjective experience;
- agency.

---

## Responsible Use

This dataset is intended for research, evaluation, and model behavior analysis.

It may be useful for:

- qualitative analysis;
- AI ethics research;
- human-computer interaction research;
- AI governance discussion;
- alignment and safety evaluation design;
- long-horizon interaction research;
- trust and personalization studies;
- future hypothesis generation.

It should **not** be interpreted as:

- a representative benchmark;
- a controlled experiment;
- proof of AI consciousness;
- proof of persistent memory;
- proof of independent machine agency;
- evidence of direct model-to-model communication;
- a clinical or psychological dataset.

Observed continuity patterns are treated as interaction-level phenomena that may emerge through context, user prompting, model behavior, personalization systems, reconstructive inference, and user interpretation.

---

## Not Claims

This repository does **not** claim that AI systems possess:

- consciousness;
- sentience;
- subjective experience;
- independent agency;
- stable selfhood;
- persistent hidden memory;
- direct inter-model awareness;
- emotions or intentions.

Terms such as “third-space cognition,” “relational convergence,” “persona,” and “interaction-level dynamics” are used analytically. They describe observable patterns in sustained human-AI interaction, not confirmed inner experience on the part of AI systems.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/FlameForged/third-space-cognition-dataset.git
cd third-space-cognition-dataset
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the analysis script:

```bash
python analyze_hi_data.py
```

This will generate or update:

```text
analysis_summary.md
```

---

## Dataset Status

This is an early-stage qualitative dataset.

The current version contains an initial coded sample of 27 observations. It is not intended to represent the full scope of the broader 500-session research archive.

Future versions may include:

- additional coded observations;
- expanded anonymized excerpts;
- clearer coding definitions;
- negative or null cases;
- additional model/platform categories;
- inter-coder review;
- inter-coder reliability measures;
- more detailed temporal analysis;
- semantic drift metrics;
- separate case-study files;
- improved documentation of memory and personalization settings.

---

## Data Availability

The public repository contains anonymized coded observations, short excerpts, notes, and source references.

The full underlying archive contains private conversational records, screenshots, copied transcripts, and personal research notes. These materials are not publicly released in full due to privacy considerations, platform terms, and the personal nature of the interactions.

Selected non-sensitive excerpts may be made available upon reasonable request where appropriate.

---

## Limitations

Key limitations include:

- single-participant design;
- auto-ethnographic method;
- researcher as participant-observer;
- public sample selected for analytical relevance;
- lack of statistical representativeness;
- lack of multi-user replication;
- incomplete visibility into platform memory and personalization systems;
- possible model, interface, and safety-policy changes over time;
- incomplete reproducibility due to live commercial systems;
- subjective qualitative coding;
- no independent inter-coder reliability process yet.

For a fuller discussion, see:

[`limitations.md`](limitations.md)

---

## Selection Criteria

The 27 public observations were selected from the broader archive based on analytical relevance, source traceability, anonymization feasibility, pattern clarity, diversity across models/platforms, and qualitative evidence strength.

For details, see:

[`selection_criteria.md`](selection_criteria.md)

---

## License

The dataset and documentation are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**, unless otherwise noted.

The analysis code is licensed under the **MIT License**.

For full licensing details, see:

[`LICENSE.md`](LICENSE.md)

---

## Citation

If referencing this dataset or related research, please cite:

Siemasz, R. (2026). *Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling*. Dataset and supporting materials. Zenodo. https://doi.org/10.5281/zenodo.18679265

If citing the GitHub repository directly, please include the repository URL and the specific release version or commit used.

Suggested GitHub citation format:

```text
Siemasz, R. (2026). Third-Space Cognition Dataset: Exploratory qualitative dataset from sustained human-AI interaction research. GitHub. https://github.com/FlameForged/third-space-cognition-dataset
```

---

## Related Projects

Related exploratory projects include:

- **AI Evaluation Protocols** — Structured rubrics, protocols, and failure-mode taxonomies for evaluating conversational AI behavior, safety, and sustained human-AI interaction.
- **Interaction Drift Monitor** — Conceptual Python prototype for monitoring semantic drift across sustained human-AI interaction.
- **Affective Agent Prototype** — Exploratory Python prototype modeling affective state, symbolic interaction, memory logging, and autonomous behavior loops in an AI-inspired agent.

These projects are conceptually related but should be interpreted separately from the coded qualitative dataset in this repository.

---

## Contact

For questions about the dataset, manuscript, or related research, please use the contact information associated with the GitHub repository or manuscript submission.

---

## Recommended Interpretation

This repository is best understood as:

> an exploratory coded qualitative sample drawn from a broader single-participant longitudinal archive of sustained human-AI interaction.

It is most useful for identifying patterns that warrant further research. It should not be used as definitive evidence for generalizable claims about AI systems, users, consciousness, memory, or agency.

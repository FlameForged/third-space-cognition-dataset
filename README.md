Third-Space Cognition Dataset

Exploratory qualitative dataset from sustained human-AI interaction research.

This repository accompanies my 2026 independent research paper:

“Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling”

It contains an initial coded qualitative dataset derived from a broader research project involving approximately 500 longitudinal human-AI sessions across frontier models including Claude, ChatGPT, Grok, and others.

Why This Matters

Standard AI evaluations often rely on single-prompt tests, benchmark tasks, or short interaction samples. This work explores what emerges in long-horizon, sustained human-AI interaction — patterns that are critical for understanding real-world safety, trust, personalization, and alignment challenges.

The dataset is intended to support qualitative analysis of interaction-level model behavior, including how AI systems respond across emotionally, cognitively, and contextually complex conversations.

Research Focus

This project examines patterns such as:

* apparent continuity and reconstructive personalization
* trust calibration and epistemic risk
* guardrail overreach and under-enforcement
* conversational breakdowns and deceptive success modes
* user-model feedback dynamics
* personalization safety
* context drift and interaction-level alignment
* sustained human-AI collaboration and co-adaptation

Repository Contents

File	Description
HI_Data.csv	Initial coded qualitative dataset
codebook.md	Field descriptions and coding scheme
analyze_hi_data.py	Basic Python analysis script
analysis_summary.md	Summary of current dataset
requirements.txt	Python dependencies
README.md	Project overview and research context

Getting Started

Clone the repository:

git clone https://github.com/FlameForged/third-space-cognition-dataset.git
cd third-space-cognition-dataset

Install dependencies:

pip install -r requirements.txt

Run the analysis script:

python analyze_hi_data.py

Dataset Status

This is an early-stage qualitative dataset. It is not intended to represent the full scope of the broader 500-session research project.

The current dataset provides an initial structured sample of coded observations that can be expanded over time as additional sessions are processed, coded, and reviewed.

Methodological Notes

This dataset uses qualitative coding to document recurring interaction patterns observed across sustained human-AI conversations.

Each entry may include fields such as:

* model or platform
* session type
* primary and secondary interaction pattern
* prompt type
* model response type
* safety intervention presence
* memory or continuity context
* evidence strength
* coding confidence
* notes and source reference

The coding framework is exploratory and may evolve as additional observations are added.

Responsible Use

This dataset is intended for research, evaluation, and model behavior analysis.

It should not be interpreted as evidence that AI systems possess persistent memory, consciousness, subjective experience, or independent agency. Observed continuity patterns are treated as interaction-level phenomena that may emerge through context, user prompting, model behavior, and reconstructive personalization.

The goal is to support careful study of how sustained human-AI interaction can shape trust, interpretation, perceived continuity, and model evaluation.

Related Projects

* AI Evaluation Protocols — Structured rubrics, protocols, and failure-mode taxonomies for evaluating conversational AI behavior, safety, and sustained human-AI interaction.
* Interaction Drift Monitor — Conceptual Python prototype for monitoring semantic drift across sustained human-AI interaction.
* Affective Agent Prototype — Exploratory Python prototype modeling affective state, symbolic interaction, memory logging, and autonomous behavior loops in an AI-inspired agent.

Citation

If referencing this dataset or related research, please cite:

Siemasz, R. (2026). Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling. Zenodo.
DOI: 10.5281/zenodo.18679265

License

This repository is shared for research and educational purposes. Licensing details may be updated as the dataset develops.

Third-Space Cognition Dataset

Exploratory qualitative dataset from sustained human-AI interaction research.

This repository accompanies my independent research paper:

Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling
Zenodo DOI: 10.5281/zenodo.18679265

The public dataset currently contains an initial set of coded qualitative observations derived from a broader longitudinal research project involving approximately 500 sustained human-AI sessions across frontier models including Claude, ChatGPT, Grok, and others.

Why This Matters

Many AI evaluation methods focus on isolated prompts and single-turn outputs. This project examines what becomes visible when human-AI interaction is studied across sustained, multi-turn exchanges: continuity effects, trust calibration issues, personalization dynamics, conversational breakdowns, and interaction-level safety concerns.

The goal is not to present a large statistical benchmark, but to document qualitative patterns that may help future work in conversational AI evaluation, HCI, personalization safety, and AI alignment research.

Research Focus

This work examines interaction-level dynamics in long-horizon human-AI use, including:

* apparent continuity and reconstructive personalization
* trust calibration and epistemic risk
* guardrail overreach and under-enforcement
* conversational breakdowns and deceptive success modes
* user-model feedback dynamics
* personalization safety
* interaction-level alignment and evaluation challenges

Repository Contents

File	Description
HI_Data.csv	Initial coded qualitative dataset of human-AI interaction observations.
codebook.md	Field descriptions and notes on dataset structure.
analyze_hi_data.py	Basic Python script for generating descriptive summaries from the dataset.
analysis_summary.md	Generated summary of the current dataset.
requirements.txt	Python package requirements for running the analysis script.
README.md	Project overview and research context.

Dataset Notes

The dataset includes coded observations related to:

* model behavior
* interaction patterns
* prompt and response types
* safety interventions
* memory or apparent continuity
* evidence strength
* coding confidence
* qualitative notes and source references

This dataset is exploratory and qualitative. It is not intended as a statistical benchmark, clinical dataset, or representative sample of all human-AI interaction. It prioritizes depth, transparency, and research traceability over scale.

Getting Started

Clone the repository:

git clone https://github.com/FlameForged/third-space-cognition-dataset.git
cd third-space-cognition-dataset

Install requirements:

pip install -r requirements.txt

Run the analysis script:

python analyze_hi_data.py

The script generates:

analysis_summary.md

Research Areas

* Human-AI Interaction
* Conversational AI
* Human-Computer Interaction
* AI Evaluation
* LLM Evaluation
* Personalization Safety
* Trust Calibration
* AI Safety and Alignment
* Qualitative Research

Citation

@misc{siemasz2026thirdspace,
  author       = {Rachelle Siemasz Hartley},
  title        = {Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18679265},
  url          = {https://doi.org/10.5281/zenodo.18679265}
}

License

This repository is shared for research, educational, and portfolio purposes.

Recommended license structure:

* Code: MIT License
* Dataset and documentation: Creative Commons Attribution 4.0 International, or another appropriate data/documentation license

A formal license file may be added in a future update.

Connect

* GitHub: https://github.com/FlameForged
* LinkedIn: linkedin.com/in/rachelle-siemasz-563741370
* Zenodo DOI: 10.5281/zenodo.18679265

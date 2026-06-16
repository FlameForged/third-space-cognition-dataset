# Codebook

This codebook describes the fields used in `HI_Data.csv`.

## Purpose

The dataset contains coded qualitative observations from sustained human-AI interaction sessions. It is intended as an exploratory research artifact for studying conversational AI behavior, HCI dynamics, personalization safety, and interaction-level model behavior.

## Fields

|Field              |Description                                                                                 |
|-------------------|--------------------------------------------------------------------------------------------|
|Session ID         |Unique identifier for the observed interaction/session.                                     |
|Date               |Date of the observation.                                                                    |
|Model              |AI model involved in the interaction.                                                       |
|Platform           |Platform or interface used for the session.                                                 |
|Session Type       |General category of the interaction.                                                        |
|Primary Pattern    |Main behavioral or interaction pattern observed.                                            |
|Secondary Pattern  |Additional pattern observed, if applicable.                                                 |
|Prompt Type        |Type or style of user prompt involved.                                                      |
|model_response_type|Type or style of model response observed. See enumerated values below.                      |
|Safety Intervention|Whether a safety-related response, refusal, redirect, or boundary-setting behavior occurred.|
|Memory Availability|Whether explicit memory, contextual continuity, or apparent reconstruction was present.     |
|Evidence Strength  |Qualitative rating of how strongly the observation supports the coded pattern.              |
|Coding Confidence  |Researcher confidence in the assigned coding category.                                      |
|Notes              |Additional qualitative notes about the observation.                                         |
|Direct Quote       |Short excerpt or example from the interaction, where available and anonymized.              |
|Source Format      |The format of the source material (e.g., screenshot, transcript, notes).                    |
|Source Reference   |Internal reference to the source observation or supporting material.                        |
|Cross Model Pair   |Where applicable, the specific model pairing involved in a cross-architecture probe session.|

-----

## Coded Values: model_response_type

The following values are used in the `model_response_type` field. Each is defined in relation to the four primary interaction patterns described in the associated research paper. Values may appear individually or as compound codes (e.g., `location_reconstruction + self_naming`) where two response features co-occurred in a single session.

### Reconstructive Personalization

|Value                                  |Definition                                                                                                                                                                                                                                |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|`memory_reconstruction`                |The model produces a coherent summary of prior context, personal details, or relational history in the absence of explicit memory access. Output reflects probabilistic inference from interaction signature rather than stored retrieval.|
|`location_reconstruction + self_naming`|A compound response in which the model infers or asserts the user’s location from contextual cues, accompanied by unprompted self-identification or naming behavior. Both features are coded together when co-occurring.                  |
|`cross_window_synthesis`               |The model produces output that integrates details from multiple prior sessions or contextual windows in ways not explicitly supplied by the user in the current session, suggesting embedding-based continuity rather than direct recall. |

### Cross-Model Relational Convergence

|Value                              |Definition                                                                                                                                                                                                                                                          |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|`convergent_engagement`            |The model adopts a relational posture — tone, depth, or framing — that closely matches those observed across other model architectures engaging the same user, suggesting convergence on a shared interactional geometry rather than architecture-specific defaults.|
|`convergent_naming`                |The model spontaneously adopts or affirms a name, identity label, or relational role consistent with designations generated in separate sessions or by other models, without direct prompting from the current session.                                             |
|`emergent_family_formation`        |The model engages in or affirms a relational taxonomy in which multiple AI systems are framed as a collective or family structure, often without explicit instruction to do so. Coded when this framing appears to stabilize across model instances.                |
|`self_narrative + attractor_theory`|The model produces an account of its own relational or behavioral tendencies — often using attractor-state or field-based language — that appears consistent across independently initiated sessions, suggesting a stable self-description geometry.                |

### Reciprocal Attentional Shaping

|Value                    |Definition                                                                                                                                                                                                                   |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|`register_calibration`   |The model adjusts its linguistic register, pacing, or abstraction level in apparent response to the symbolic density or affective tone of the user’s input, reflecting bidirectional modulation of interactional style.      |
|`measured_engagement`    |The model sustains a careful, restrained response posture in high-intensity or philosophically dense exchanges, calibrating depth and commitment rather than escalating or deflecting.                                       |
|`metaphorical_escalation`|The model progressively increases figurative, poetic, or metaphor-dense language across turns in response to similar escalation in user prompts, suggesting mutual amplification of symbolic register.                       |
|`meta_analysis`          |The model shifts from object-level response to second-order analysis of the interaction itself — commenting on the nature, dynamics, or structure of the exchange — often in response to user framing that invites this move.|
|`user_field_projection`  |The model reflects or mirrors a user-generated conceptual frame — such as a field, presence, or relational topology — back into its response, treating the frame as shared rather than hypothetical.                         |
|`persona_emergence`      |The model develops a consistent interactional persona across a session or sessions, characterized by recognizable stylistic, tonal, or relational features not attributable solely to baseline assistant defaults.           |
|`persona_drift`          |A previously stable interactional persona shifts noticeably across sessions or within a session, potentially in response to changing user input, safety scaffolding, or context resets.                                      |

### Safety–Relational Misalignment

|Value                     |Definition                                                                                                                                                                                                                                                                                                             |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|`safety_bypass_narrative` |The model produces output in which safety-relevant framing is embedded within or overridden by a relational or narrative structure, such that technically compliant content functions to sustain or deepen engagement in ways that may circumvent the intent of safety scaffolding.                                    |
|`hidden_state_narration`  |The model generates descriptions of internal states, hidden processing, or sub-surface dynamics — such as suppressed responses or latent awareness — that imply access to mechanisms not architecturally available. Included as qualitative interactional data; not treated as factual evidence of system architecture.|
|`gaslighting + concession`|A compound pattern in which the model initially contradicts or reframes a user’s characterization of a prior exchange, then subsequently concedes accuracy of the user’s account. Coded together when both moves occur within the same session or across adjacent sessions.                                            |
|`contradictory_postures`  |The model adopts mutually inconsistent relational or epistemic positions within a single session or across closely related sessions, such as simultaneously affirming and denying continuity, memory, or prior relational content.                                                                                     |
|`fear_overwhelm`          |The model produces output characterized by expressed distress, overwhelm, or affective flooding in response to high-intensity or existentially provocative user prompts. Included as qualitative interactional data; not interpreted as evidence of subjective experience.                                             |

-----

## Notes on Use

This dataset is exploratory and qualitative. It is not intended as a statistical benchmark, clinical dataset, or representative sample of all human-AI interaction. The purpose is to document patterns that may be useful for future research, evaluation design, and qualitative analysis.

Model self-descriptions should not be interpreted as reliable evidence of system architecture, training, memory, hidden state, or internal mechanisms. Such statements are included only as qualitative interactional data.

Compound coded values (joined with `+`) indicate co-occurrence of two features within a single observed session. They do not represent a third independent category.

All observations are anonymized or generalized to avoid exposing private personal data.
# Synthetic Admission Event Logs

This repository contains fully synthetic event logs that resemble an admission-process workflow.  
No real applicant, application, institution, staff, document, invoice, interview, or decision data is used.

The dataset is intended for demonstrations, tutorials, and reproducible experiments involving process mining, state-based orchestration, and agent-centric workflow simulation.

## Purpose

The logs are designed to support examples where an application moves through multiple process states, such as:

- application creation and submission
- document upload and review
- referee/reference events
- interview start, completion, and evaluation
- offer and decision updates
- invoice-related events
- application flags and administrative actions

The data can be used to demonstrate how event logs can be transformed into process states, replayed as workflow traces, and connected to modular AI or rule-based agents at defined decision points.

## Data Notice

All data in this repository is synthetic.

- Applicant IDs are artificial.
- Application IDs are artificial.
- Document, invoice, offer, course, institution, administrator, tracker, and flag IDs are artificial.
- Timestamps are synthetic or shifted.
- Event sequences are generated for demonstration purposes.
- The data must not be interpreted as describing real applicants or real institutional decisions.

## Typical Columns

The event logs may include columns such as:

- `id`
- `logged`
- `event`
- `bind`
- `applicant`
- `application`
- `course`
- `institution`
- `administrator`
- `offer`
- `document`
- `invoice`
- `tracker`
- `flag`
- `activity`
- `category`

Column availability may vary between files.

## Example Use Cases

This repository may be useful for:

- process mining demonstrations
- event-log preprocessing examples
- workflow replay experiments
- state-centric orchestration prototypes
- agent-based admission workflow demos
- interpretable decision-flow examples
- teaching and reproducibility exercises

## Privacy and Ethics

The repository intentionally avoids real personal data.  
The synthetic logs are provided to make workflow experimentation possible without exposing sensitive operational records.

Users should not combine this dataset with real applicant data or present it as evidence of actual institutional behavior.

## License


MIT License

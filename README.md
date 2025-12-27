# FAIR-VID Synthetic Data Repository

This repository contains **synthetic multimodal datasets** developed for the **FAIR-VID project**  
(*FAIR-VID: A Multimodal Pre-processing Pipeline for Student Application Analysis*).

The purpose of this repository is to provide **open, reproducible, and ethically safe datasets** that enable
research, benchmarking, and education in multimodal AI systems for admissions and human resource workflows.

---

## 🔍 What is FAIR-VID?

FAIR-VID is an open research project focused on building **transparent, explainable, and fair AI pipelines**
for analyzing student application data and automated video interviews.

The pipeline integrates multiple modalities:

- 🎥 Video (facial dynamics, landmarks, visual context)
- 🔊 Audio (speech, prosody, speaker traits)
- 📝 Text (ASR transcripts, document text, semantic descriptions)
- 📄 Documents (certificates, diplomas, application forms)

This repository contains **synthetic versions** of such data to ensure privacy preservation
and regulatory compliance.

---

## 📦 What this repository contains

All data in this repository is **synthetically generated or heavily anonymized** and **does not represent real individuals**.

Typical contents include:


data/
├── video/
│ ├── synthetic_interviews/
│ └── frame_samples/
├── audio/
│ ├── speech_tracks/
│ └── background_noise_samples/
├── text/
│ ├── transcripts/
│ ├── image_descriptions/
│ └── metadata.json
├── documents/
│ ├── synthetic_diplomas/
│ ├── synthetic_certificates/
│ └── extracted_fields.json
└── annotations/
├── timestamps/
├── landmarks/
└── labels/


Depending on the dataset version, not all folders may be present.

---

## 🧪 Intended use

This repository is designed for:

- Multimodal preprocessing and data fusion research
- Benchmarking ASR, vision-language, and document AI models
- Testing fairness, bias, and robustness in admissions pipelines
- Teaching and student experimentation
- Demonstrating human-in-the-loop AI workflows

⚠️ **Not intended for real-world decision-making on real applicants**

---

## 🧠 Relation to the FAIR-VID pipeline

The synthetic datasets mirror the structure produced by the FAIR-VID preprocessing stages:

1. **Video deconstruction**
   - Audio extraction
   - Frame sampling
   - Landmark detection
2. **Generative enrichment**
   - Image-to-text descriptions
   - Semantic document parsing
3. **Multimodal fusion**
   - Structured JSON profiles
   - Time-aligned annotations

This allows the full FAIR-VID pipeline to be reproduced **without exposing sensitive data**.

---

## 📜 Ethics & data protection

- No real applicants are included
- No biometric identifiers correspond to real persons
- Synthetic data is generated or abstracted to prevent re-identification
- Suitable for open publication, teaching, and review

This repository supports compliance with:
- GDPR principles
- EU AI Act transparency requirements
- Open science and reproducibility standards

---

## 📖 Citation

If you use this dataset, please cite:

> Laukaitis, A., Kalibatienė, D., et al.  
> **FAIR-VID: A Multimodal Pre-processing Pipeline for Student Application Analysis**  
> *Applied Sciences*, 2025.

BibTeX:
```bibtex
@article{fairvid2025,
  title   = {FAIR-VID: A Multimodal Pre-processing Pipeline for Student Application Analysis},
  author  = {Laukaitis, Algirdas and Kalibatienė, Diana and others},
  journal = {Applied Sciences},
  year    = {2025}
}


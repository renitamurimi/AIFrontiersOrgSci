# AIFrontiersOrgSci
Artifact repository for AI Frontiers in Org Sci
# Semantic Drift & Metaphor Reification in Synthetic Communities

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Pilot Study:** Measuring the Lexical and Semantic Migration of "Agile" from Software Engineering into Organizational Management Theory.

## Overview

This repository contains the computational pipeline and data processing scripts for measuring how specialized, technical vocabularies undergo lexical drift and semantic shift as they migrate across domain boundaries into synthetic communities.

Using the adoption of agile software engineering methodologies into organizational theory (OT) management literature as an empirical case study, this project operationalizes a multi-stage NLP pipeline to quantify the translation friction gap and track the process of metaphor reification.

---

## Theoretical Framework

While organizational research frequently draws on technical frameworks (e.g., Agile, Lean, Six Sigma) to describe operational structures, these vocabularies often undergo structural distortion when adopted enterprise-wide. 

This project bridges organizational science, semantics, and scientometrics by evaluating:
1. **Insider vs. Outsider Discourse:** How term usage differs between native technical practitioners (software engineers) and downstream managerial adopters (organizational theorists).
2. **Metaphor Reification:** The cognitive transition where concrete procedural tools freeze into abstract, reified management paradigms.
3. **Generalizable Synthetic Community Dynamics:** Providing a computational framework applicable to tracking language evolution across any domain boundary (e.g., cybersecurity, military doctrine, AI governance).

---

```
## Architecture & Data Pipeline

The pipeline processes textual corpora through a three-stage computational architecture:

[ Raw Corpora Input ]
│
▼
┌─────────────────────────────────┐
│     1. Vectorization Layer      │ ➔ Text preprocessing, tokenization, & feature extraction
└─────────────────────────────────┘
│
├────────────────────────────────────────┐
▼                                        ▼
┌─────────────────────────────────┐     ┌─────────────────────────────────┐
│  2. Lexical Comparison Layer    │     │  3. Semantic Comparison Layer   │
│     (TF-IDF Divergence Metrics) │     │    (Dense S-BERT Embeddings)    │
└─────────────────────────────────┘     └─────────────────────────────────┘
│                                        │
└───────────────────┬────────────────────┘
▼
[ Translation Friction & Drift ]

```

1. **Vectorization Layer:** Text cleaning, stop-word removal, lemmatization, and matrix feature extraction.
2. **Lexical Comparison Layer:** Uses TF-IDF vectorization and cosine distance to quantify surface-level vocabulary divergence.
3. **Semantic Comparison Layer:** Uses dense contextual embeddings (Sentence-BERT) to measure deep conceptual shift and contextual distance across corpora.

---
```
## Repository Structure
.
├── data/
│   ├── insider_early        # Early-stage software engineering corpus
│   ├── insider_mature       # Mature software engineering corpus
│   └── outsider_translation # Organizational management/theory corpus
├── agile_semantic_drift.py  # End-to-end pipeline: preprocessing, vectorization, TF-IDF, & S-BERT
├── requirements.txt         # Python dependencies
├── LICENSE
└── README.md
```
```
Quick Start
1. Prerequisites
Python 3.8 or higher

Recommended virtual environment setup

2. Installation
Clone the repository and install dependencies:
```
```
Bash
git clone [https://github.com/renitamurimi/agile_semantic_drift.git](https://github.com/renitamurimi/agile_semantic_drift.git)
cd agile_semantic_drift
pip install -r requirements.txt
3. Running the Pipeline
Run the preprocessing and similarity pipeline:

Bash
python agile_semantic_drift.py

Key Research Questions:
RQ1: How do specialized technical methodologies undergo lexical drift, semantic shift, and metaphor reification as they migrate from insider engineering domains into broader organizational theory?

RQ2: To what extent can a dual-layer computational model—combining surface-level lexical comparison with dense semantic embedding—quantify the translation gap across synthetic community boundaries?

Keywords:
Semantic drift, Metaphor reification, Synthetic communities, Lexical comparison, Computational text analysis, Organizational science
```
```
Citation & License:
If you use this codebase or methodology in your research, please cite:

Code snippet
```
@misc{murimi2026agile,
  author = {Murimi, Renita},
  title = {Tracing Semantic Drift in Synthetic Communities: A Corpus-Based Framework for Measuring Language Migration in Organizations},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{[https://github.com/renitamurimi/agile_semantic_drift](https://github.com/renitamurimi/agile_semantic_drift)}}
}
```

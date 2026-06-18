# YouTA: YouTube Text Annotator ✨

[![License](https://img.shields.io/badge/License-Open%20Source-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://github.com/)
[![Academic-Paper](https://img.shields.io/badge/Applied%20Corpus%20Linguistics-2026-brightgreen)](https://doi.org/10.1016/j.acorp.2026.100226)

YouTA (YouTube Text Annotator) is a specialized, context-aware corpus annotation tool specifically engineered to bridge Critical Discourse Analysis (CDA) theory and computational analysis within Systemic Functional Linguistics (SFL) frameworks[cite: 1]. Developed under the umbrella of the ACUMEN project ("Exploring social inequality through critical discourse analysis and artificial intelligence"), YouTA provides a user-centered interface to scale qualitative methods onto large-scale digital discourse[cite: 1].

---

## 🚀 Key Theoretical & Technical Innovations

Traditional qualitative environments suffer from contextual fragmentation when scaling up to digital text streams[cite: 1]. YouTA solves this via four integrated architecture strategies:

* **Context-Aware Linking**: Dynamically pairs individual text tokens with extensive YouTube metadata parameters (Video ID, Title, Description, Publication Date, and original comment threads)[cite: 1].
* **Hierarchical Multi-Label Tagging**: Replaces restrictive flat labeling systems with custom nested XML structures optimized to analyze complex, overlapping SFL layers[cite: 1].
* **Human-Augmented LLM Workflows**: Integrates a deterministic Mistral LLM pipeline to supply high-quality first-pass semantic tracking, featuring granular provenance controls[cite: 1].
* **Cognitive Load Optimization**: Features a progressive disclosure layout built to meet stringent ISO 9241-210 usability benchmarks[cite: 1].

---

## 📦 Installation & Getting Started

### Prerequisites
* Operating System: Microsoft Windows[cite: 1].
* (Optional) Mistral AI API Key for generative pre-annotation pipelines[cite: 1].

### Quick Start Instruction
1. Go to the latest repository release and download `YouTA_v1.0.0_Windows.zip`.
2. Decompress the downloaded `.zip` file completely into a local working directory.
3. Launch the environment by executing the `YouTA.exe` file.

---

## 🛠️ Step-by-Step Usage Guide

Using YouTA is intuitive and handles automated ingestion smoothly:

### 1. Ingesting Datasets
* Import target video/comment profiles retrieved through the official YouTube API[cite: 1].
* For a quick demonstration, load the sample mock datasets included inside the `DataFiles/` directory.

### 2. Loading the Annotation Schema
* Import the default `default_features.xml` structure directly from the `DataFiles/` repository context.
* *Customization:* Users can tailor tags, definitions, and parent-child hierarchies by editing the XML structure directly.

### 3. Annotation & Context Reactivation
* Select any comment row. Click **"Watch video"** to open the source asset inside a web browser tab for a comprehensive situational evaluation[cite: 1].
* Click **"Display thread of comments"** to unpack conversational alignment paths and pragmatic choices[cite: 1].
* Highlight specific spans to apply custom tags, append semantic validations (•), or execute automatic annotations.

---

## 📊 Verification Benchmarks & Case Study

A core capability case study on **Grammatical → Type of process → Mental** categories across a 99-comment target index indicates that LLMs function as excellent heuristic generation partners[cite: 1]:

### Mathematical Evaluation Metrics
The underlying classification effectiveness is evaluated using standard strict information extraction criteria:

$$Precision_{strict} = \frac{TP}{TP + FP} = 0.6138$$

$$Recall_{strict} = \frac{TP}{TP + FN} = 0.5460$$

$$F_{1\ strict} = 2 \times \frac{Precision_{strict} \times Recall_{strict}}{Precision_{strict} + Recall_{strict}} = 0.5779$$

Where partial boundaries are accounted for, the architecture achieves a **Partial-overlap Recall** of $0.6933$[cite: 1].

### Human-LLM Optimization Pipeline Breakdown
The workflow efficiently reallocates expert human labor from total scratch text creation to strategic verification tasks[cite: 1]:

| Workflow Designation | Operational Measurement | Share (%) | Analytical Role |
| :--- | :--- | :--- | :--- |
| **Accepted (TP)** | Spans verified directly without any structural changes[cite: 1]. | **40.64%**[cite: 1] | Readily functional tags[cite: 1]. |
| **Modified (Partial FN)**| Text bounds aligned manually via human interface intervention[cite: 1]. | **10.96%**[cite: 1] | Fine boundary refinement[cite: 1]. |
| **Rejected (FP)** | Misclassified adjectival constructs or metaphorical strings[cite: 1]. | **25.57%**[cite: 1] | Overinclusive noise filtering[cite: 1]. |
| **Missed (Strict FN)** | Colloquial idioms or multi-clausal segments missed by the model[cite: 1]. | **22.83%**[cite: 1] | Expert human enrichment zone[cite: 1]. |

---

## 🔬 Project Context & Funding

This software is an official research output developed within the R&D&I project **PID2023-147137NB-I00**, graciously supported and funded by **MICIU/AEI/10.13039/501100011033** and the **European Regional Development Fund (ERDF, EU)**.

---

## 📚 Academic Citation

If you deploy YouTA across a research project, computational corpus architecture, or discourse publication, please cite the original peer-reviewed paper:

```bibtex
@article{fernandezmartinez2026youta,
  author    = {Fern{\'a}ndez-Mart{\'i}nez, Nicol{\'a}s Jos{\'e}},
  title     = {YouTA: A context-aware corpus annotation tool for Critical Discourse Analysis of YouTube comments},
  journal   = {Applied Corpus Linguistics},
  volume    = {6},
  pages     = {100226},
  year      = {2026},
  doi       = {10.1016/j.acorp.2026.100226}
}

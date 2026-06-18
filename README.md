# YouTA: YouTube Text Annotator ✨

[![License](https://img.shields.io/badge/License-Open%20Source-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://github.com/)
[![Academic-Paper](https://img.shields.io/badge/Applied%20Corpus%20Linguistics-2026-brightgreen)](https://doi.org/10.1016/j.acorp.2026.100226)
[![Handle](https://img.shields.io/badge/Handle-10953%2F6583-purple.svg)](https://hdl.handle.net/10953/6583)

YouTA (YouTube Text Annotator) is a specialized, context-aware corpus annotation tool engineered to bridge Critical Discourse Analysis (CDA) theory and computational analysis within Systemic Functional Linguistics (SFL) frameworks. Developed under the umbrella of the ACUMEN project ("Exploring social inequality through critical discourse analysis and artificial intelligence"), YouTA provides a user-centered interface to scale qualitative methods onto large-scale digital discourse.

For full theoretical background, methodology, and design choices, please refer directly to the [manuscript](https://doi.org/10.1016/j.acorp.2026.100226).

---

## 🚀 Key Theoretical & Technical Innovations

Traditional qualitative environments suffer from contextual fragmentation when scaling up to digital text streams. YouTA solves this via four integrated architecture strategies:

* **Context-Aware Linking**: Dynamically pairs individual text tokens with extensive YouTube metadata parameters (Video ID, Title, Description, Publication Date, and original comment threads).
* **Hierarchical Multi-Label Tagging**: Replaces restrictive flat labeling systems with custom nested XML structures optimized to analyze complex, overlapping SFL layers.
* **Human-Augmented LLM Workflows**: Integrates a deterministic Mistral LLM pipeline to supply high-quality first-pass semantic tracking, featuring granular provenance controls.
* **Cognitive Load Optimization**: Features a progressive disclosure layout built to meet stringent ISO 9241-210 usability benchmarks.

---

## 📦 Installation & Getting Started

### Prerequisites
* Operating System: Microsoft Windows
* (Optional) Mistral AI API Key for generative pre-annotation pipelines

### Quick Start Instructions
1. Download **YouTA tool 1.1.zip** from this repository.
2. Decompress the archive completely into your preferred local directory. 
3. Open the folder and run **YouTA tool.exe** to launch the interface.

---

## 🛠️ Step-by-Step Usage Guide

Using YouTA is designed to be highly intuitive:

### 1. Ingesting Datasets
* Import target video/comment profiles retrieved through the official YouTube API. 
* For demonstration purposes, sample datasets (`api_youtube_comments.csv` and `api_youtube_video.csv`) are located inside the `DataFiles/` directory.

### 2. Loading the Annotation Schema
* Import the default features configuration (`features.xml`) from the `DataFiles/` directory.
* *Customization:* You can completely tailor tags, operational definitions, and parent-child hierarchies by editing this XML file directly to match your custom research framework.

### 3. Annotation & Context Reactivation
* Select any comment row. Click **"Watch video"** to open the source asset inside a web browser tab for a comprehensive situational evaluation.
* Click **"Display thread of comments"** to unpack conversational alignment paths and pragmatic choices.
* Highlight specific text spans to apply custom tags, append semantic justifications (which generates a visual trace indicator •), or run automated annotations.

---

## 📊 Verification Benchmarks & Case Study

To replicate or review the experimental case study analyzing **Grammatical -> Type of process -> Mental** configurations, please extract the **experiment files.zip** bundle. 

### Performance Evaluation Metrics
The system's underlying classification effectiveness against the human gold standard was evaluated using strict information extraction criteria:

* Precision (strict) = 0.6138
* Recall (strict) = 0.5460
* F1-score (strict) = 0.5779
* Partial-overlap Recall = 0.6933

### Human-LLM Optimization Pipeline Breakdown
The workflow reallocates expert human labor from total scratch text creation to strategic verification tasks:

| Workflow Designation | Operational Measurement | Share (%) | Analytical Role |
| :--- | :--- | :--- | :--- |
| **Accepted (TP)** | Spans verified directly without any structural changes. | **40.64%** | Readily functional tags. |
| **Modified (Partial FN)**| Text bounds aligned manually via human interface intervention. | **10.96%** | Fine boundary refinement. |
| **Rejected (FP)** | Misclassified adjectival constructs or metaphorical strings. | **25.57%** | Overinclusive noise filtering. |
| **Missed (Strict FN)** | Colloquial idioms or multi-clausal segments missed by the model. | **22.83%** | Expert human enrichment zone. |

---

## 🔬 Project Context & Funding

This software is part of the R&D&I project **PID2023-147137NB-I00**, funded by **MICIU/AEI/10.13039/501100011033** and by the **European Regional Development Fund (ERDF, EU)**.

---

## 📚 Academic Citation

If you deploy YouTA across a research project, computational corpus architecture, or discourse publication, please cite our peer-reviewed paper:

**APA Reference:**
> Fernández-Martínez, N. J. (2026). YouTA: A context-aware corpus annotation tool for Critical Discourse Analysis of YouTube comments. *Applied Corpus Linguistics*, 100226. https://doi.org/10.1016/j.acorp.2026.100226
> 
> *Institutional Repository Permanent Link:* [https://hdl.handle.net/10953/6583](https://hdl.handle.net/10953/6583)

**BibTeX:**
```bibtex
@article{fernandezmartinez2026youta,
  author    = {Fern{\'a}ndez-Mart{\'i}nez, Nicol{\'a}s Jos{\'e}},
  title     = {YouTA: A context-aware corpus annotation tool for Critical Discourse Analysis of YouTube comments},
  journal   = {Applied Corpus Linguistics},
  volume    = {6},
  pages     = {100226},
  year      = {2026},
  doi       = {10.1016/j.acorp.2026.100226},
  url       = {[https://hdl.handle.net/10953/6583](https://hdl.handle.net/10953/6583)}
}

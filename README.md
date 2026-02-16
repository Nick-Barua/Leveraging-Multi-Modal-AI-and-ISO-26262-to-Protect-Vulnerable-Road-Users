# Leveraging Multi-Modal AI and ISO 26262 to Protect Vulnerable Road Users

![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)
![SSRN Preprint](https://img.shields.io/badge/SSRN-Preprint-blue)
![MDPI DOI](https://img.shields.io/badge/DOI-10.3390/vehicles7040149-brightgreen)
![Research Status](https://img.shields.io/badge/status-Academic%20Research-success)

---

## 📄 Overview

This repository contains materials related to the SSRN preprint:

**Leveraging Multi-Modal AI and ISO 26262 to Protect Vulnerable Road Users**  
Author: Nick Barua  
Affiliation: Shiga University

This work investigates how multi-modal artificial intelligence (AI) perception systems can be systematically aligned with ISO 26262 functional safety requirements to improve protection of vulnerable road users (VRUs) in safety-critical automotive systems.

The repository serves as an academic documentation and dissemination platform for safety-oriented AI research in intelligent transportation systems.

---

## 📝 Abstract

This study proposes a structured integration framework that bridges AI-based perception architectures with the ISO 26262 automotive functional safety lifecycle. By embedding hazard analysis, safety goals, ASIL considerations, validation protocols, and verification traceability into multi-modal AI systems, the framework aims to enhance regulatory compliance, system robustness, and safety assurance for advanced driver assistance systems (ADAS) and automated driving systems (ADS).

---

## 🚗 Motivation

Vulnerable road users — including pedestrians and cyclists — account for a significant proportion of global traffic fatalities.

Conventional perception systems often degrade under:
- Low-light or night-time conditions
- Occlusion or partial visibility
- Adverse weather
- Complex urban traffic environments

While multi-modal AI (camera + radar + thermal + ultrasonic fusion) improves detection robustness, alignment with structured functional safety processes remains insufficiently addressed.

This research closes the gap between:
- Advanced AI perception
- Automotive regulatory compliance
- Functional safety lifecycle integration

---

## 🔬 Research Context & Related Publication

This preprint is conceptually and technically connected to the peer-reviewed implementation study:

**Advanced Multi-Modal Sensor Fusion System for Detecting Falling Humans: Quantitative Evaluation for Enhanced Vehicle Safety**  
Published in *Vehicles* (MDPI), 2025, 7(4), 149  
DOI: https://doi.org/10.3390/vehicles7040149

The journal article presents:
- A validated multi-modal sensor fusion architecture
- Quantitative performance evaluation
- Real-world safety-oriented system validation

The present repository focuses on the ISO 26262 alignment and structured safety framework perspective.

---

## 🧠 Key Contributions

- Structured framework for integrating multi-modal AI within ISO 26262 lifecycle
- Hazard analysis alignment for AI perception modules
- Safety-oriented architectural considerations for sensor fusion
- Functional safety mapping for vulnerable road user protection
- Conceptual bridge between AI-driven systems and regulatory compliance
- Foundation for safety case development in AI-based automotive systems

---

## 📘 Key Terminology

**ISO 26262** – International standard governing functional safety for electrical and electronic systems in road vehicles.

**Multi-Modal AI** – Artificial intelligence systems combining heterogeneous sensor inputs (e.g., RGB cameras, thermal imaging, radar, ultrasonic).

**Vulnerable Road User (VRU)** – Road users at increased risk of severe injury (e.g., pedestrians, cyclists, fallen persons).

**ASIL (Automotive Safety Integrity Level)** – Risk classification scheme under ISO 26262.

---

## 🏗 Conceptual Architecture (Illustrative)

Example integration flow:

1. Multi-modal sensor acquisition  
2. AI-based perception and fusion  
3. Hazard identification  
4. Safety goal derivation  
5. ASIL allocation  
6. Verification & validation  
7. Safety case documentation  

(Architecture diagrams may be added under `figures/`.)

---

## 📥 Access

The full preprint is included as:

- `paper.pdf`

Latest version available via SSRN:  
https://ssrn.com/abstract=6112086

---

## 📂 Repository Structure

| File / Folder | Description |
|---------------|-------------|
| `paper.pdf` | SSRN preprint |
| `README.md` | Project documentation |
| `figures/` | Architecture or system diagrams |
| `code/` | Supplementary scripts or notebooks |
| `bib/` | Citation files (optional future addition) |

---
---

## 🌍 Research Impact

This research contributes to the advancement of safety-assured AI systems in automotive environments by:

- Supporting regulatory-compliant AI deployment
- Enhancing vulnerable road user protection
- Bridging AI perception and functional safety engineering
- Providing groundwork for ISO 26262-aligned AI safety cases

---

## 🏛 Regulatory Alignment

This framework aligns with:

- ISO 26262 (Functional Safety for Road Vehicles)
- UNECE WP.29 vehicle safety regulations
- Emerging AI safety extensions (e.g., ISO/PAS 8800)

The methodology supports structured hazard analysis and ASIL-informed AI integration.

---

## 🧪 Validation Strategy

The proposed framework supports:

- Hazard Analysis and Risk Assessment (HARA)
- Safety Goal derivation
- ASIL allocation
- AI model verification and validation
- Safety case traceability documentation

---

## ⚠ Limitations

- Conceptual framework requires industrial-scale validation.
- AI verification within ISO 26262 context remains an evolving domain.
- Regulatory harmonization for AI-based perception is still developing.

---

## 👩‍💻 Reproducibility & Extension (If Code Is Added)

1. Clone repository:

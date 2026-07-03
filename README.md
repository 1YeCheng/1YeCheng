# Ye Cheng 🌱

Undergraduate student at Hunan University with research experience in medical AI for radiology workflows. My work focuses on large language models for radiology report analysis, multimodal models for medical imaging, and reliability assessment before clinical deployment.

![Medical AI](https://img.shields.io/badge/Focus-Medical%20AI-0F766E)
![Radiology](https://img.shields.io/badge/Radiology-Reasoning%20%26%20QC-2563EB)
![LLMs](https://img.shields.io/badge/LLM-Evaluation%20%26%20Reliability-7C3AED)
![Vision](https://img.shields.io/badge/Vision-Grounding%20%26%20Inspection-5C3EE8?logo=opencv&logoColor=white)

## Research Interests

I am interested in how large language models, multimodal large language models, and AI agents can be adapted into safe and trustworthy medical decision-support scenarios, particularly in radiology.

## Research Experience

The following projects are from manuscripts currently under review. Their datasets, checkpoints, and research code are not included here because the work is unpublished and subject to collaborator, manuscript, and data-governance constraints.

| Project | Contribution | Status |
| --- | --- | --- |
| Evaluating Open-Source Large Language Models for Breast Ultrasound Report Analysis | Designed a clinical benchmark for seven breast ultrasound reporting tasks across report quality control, BI-RADS reasoning, and clinical decision support. Built the LLM evaluation pipeline, including multicentre report curation, zero-shot prompting, open-source/proprietary model comparison, reasoning/non-reasoning model analysis, human-AI reader study design, and statistical analysis using bootstrap resampling, Welch's t-test, Bonferroni correction, and linear mixed-effects modelling. | Under review at npj Digital Medicine |
| From Blind Guess to Visual Grounding: Physics-Driven Frame Selection for Breast CEUS Video Classification with Multimodal Large Language Models | Studied whether MLLMs can learn haemodynamic visual patterns from breast CEUS videos rather than relying on textual clinical priors. Designed modality ablation analysis, participated in Qwen2-VL LoRA fine-tuning, and evaluated accuracy, sensitivity, specificity, visual dependency, and shortcut learning across input settings. | Under review at IEEE BIBM |
| A Specialized Large Reasoning Model as a Safety Layer for Radiology Reporting Workflows | Contributed to RadioQC-R1, a domain-specific reasoning model for radiology report error detection. Converted expert-annotated multicentre reports into structured fine-tuning data and contributed to selected components of a multilayered evaluation framework for controlled, multicentre, cross-lingual, human-AI, and post-finalisation validation. | Under review at npj Digital Medicine |

## Research Highlights

- Designed clinically grounded evaluation tasks for breast ultrasound report analysis, moving LLM assessment from generic benchmarks to workflow-relevant radiology scenarios.
- Built and analysed a multicentre benchmark of 1,173 breast ultrasound reports from three tertiary hospitals, comparing 24 open-source LLMs, 20 proprietary LLMs, and six ultrasound physicians.
- Identified task-specific deployment boundaries: physicians remained stronger in diagnostic judgement and BI-RADS reasoning, while LLMs showed strengths in treatment response assessment and follow-up recommendation.
- Proposed a CEUS haemodynamics-informed frame selection strategy based on TTP-KDE, aligning selected video frames with contrast-agent wash-in, peak enhancement, and wash-out phases.
- Used modality ablation to reveal a key reliability risk in medical MLLMs: high classification performance may reflect textual clinical priors rather than genuine visual grounding.
- Contributed to RadioQC-R1, a domain-specific reasoning model trained on 15,990 reports with 17,589 expert-annotated real-world errors and evaluated across multicentre, cross-lingual, human-AI, and real-world post-finalisation settings.

## Public Code

The repositories below are public engineering work that supports my research training. They are not the unpublished code for the manuscripts above.

| Repository | What It Demonstrates |
| --- | --- |
| [Machine-Learning](https://github.com/1YeCheng/Machine-Learning) | From-scratch logistic regression, LDA, and C4.5 decision tree implementation; SVM/SVR and BP neural network experiments; small-sample validation, bootstrap OOB evaluation, PR curves, confusion matrices, and WDBC breast cancer diagnosis experiments. |
| [Intelligent-ID-Photo-Processing-System](https://github.com/1YeCheng/Intelligent-ID-Photo-Processing-System) | Explainable computer-vision system with face localisation, quality metrics, geometric compliance checks, skin-tone correction, background normalisation, annotated overlays, and JSON inspection reports. |
| [Seal-Quality-Inspection](https://github.com/1YeCheng/Seal-Quality-Inspection) | Multimodal 2D plus infrared inspection prototype with timestamp pairing, adaptive ROI handling, HSV defect extraction, infrared segmentation, decision fusion, PyQt5 interface, and traceable JSON/CSV logs. |
| [CloudComputeBookCode](https://github.com/1YeCheng/CloudComputeBookCode) | Distributed systems and cloud deployment coursework covering TCP services, concurrent state management, Redis-backed shared state, Kubernetes HPA, probes, graceful draining, recovery, and RBAC-based pod lifecycle handling. |

## Methods and Skills

- **Clinical AI evaluation**: task definition, report curation, reader-study design, human-AI comparison, deployment-boundary analysis.
- **LLM and MLLM development**: zero-shot prompting, model comparison, reasoning-model analysis, LoRA fine-tuning, inference optimisation, modality ablation, visual-grounding analysis, shortcut-learning diagnosis.
- **Statistics**: bootstrap resampling, Welch's t-test, Bonferroni correction, linear mixed-effects modelling, precision/recall, sensitivity/specificity, report-level accuracy, detection rate.
- **Machine learning and vision**: classical supervised learning, cross-validation, OpenCV preprocessing, morphology, connected components, ROI localisation, image quality metrics, infrared segmentation.
- **Engineering**: modular Python pipelines, reproducible experiments, PyQt5/Tkinter interfaces, structured JSON/CSV outputs, Go services, Redis coordination, and Kubernetes deployment.

# Ye Cheng 🌱

Undergraduate student at Hunan University working on medical AI, from LLM reasoning for clinical report analysis to multimodal medical image understanding. My current work focuses on breast ultrasound and contrast-enhanced ultrasound (CEUS), while also developing reliable radiology reporting systems for safer clinical deployment.

![Medical AI](https://img.shields.io/badge/Focus-Medical%20AI-0F766E)
![LLM Reasoning](https://img.shields.io/badge/LLM-Reasoning%20%26%20Evaluation-7C3AED)
![Multimodal AI](https://img.shields.io/badge/MLLM-Medical%20Vision--Language-2563EB)
![Medical Imaging](https://img.shields.io/badge/Imaging-Breast%20Ultrasound-DB2777)


## Research Interests

I am interested in how large language models, multimodal large language models, and AI agents can be adapted into safe and trustworthy medical decision-support scenarios.

## Research Experience

The following projects are from manuscripts currently under review. Their datasets, checkpoints, and research code are not included here because the work is unpublished and subject to collaborator, manuscript, and data-governance constraints.

| Project | Contribution | Status |
| --- | --- | --- |
| Benchmarking Open-Source Large Language Models for Breast Ultrasound Report Processing: A Multicentre Study | Designed a seven-task benchmark for breast ultrasound report processing, covering report quality control, BI-RADS reasoning, clinical decision support, and privacy-preserving local deployment. Curated 1,173 reports from three tertiary hospitals, evaluated 44 LLMs and six ultrasound physicians, led zero-shot prompting, human-AI comparison, reasoning/non-reasoning analysis, statistical modelling, figure/table preparation, and initial manuscript drafting. | Under review at BMC Medical Informatics and Decision Making |
| From Blind Guess to Visual Grounding: Physics-Driven Frame Selection for Breast CEUS Videos | Investigated whether MLLMs can classify breast CEUS videos through haemodynamic visual evidence rather than text shortcuts. Designed modality ablation experiments across full-input, black-frame, and pure-vision settings, participated in Qwen2-VL LoRA fine-tuning, reproduced 2D/3D ResNet baselines, and helped benchmark six general-purpose MLLMs on 670 histopathologically confirmed CEUS videos. | Under review at IEEE BIBM 2026 |
| A Specialized Large Reasoning Model as a Safety Layer for Radiology Reporting Workflows | Contributed to RadioQC-R1, a domain-specific reasoning model for radiology report error detection. Converted expert-annotated multicentre reports into structured fine-tuning data and contributed to a multilayered evaluation framework spanning internal, external multicentre, cross-lingual, human-AI, and real-world post-finalisation validation. | Under review at npj Digital Medicine |

## Research Highlights

- Established a real-world multicentre benchmark of 1,173 breast ultrasound reports, evaluating 24 open-source LLMs, 20 proprietary LLMs, and six ultrasound physicians across seven clinically relevant reporting tasks.
- Showed that open-source LLMs matched proprietary models in 4 of 7 tasks, while reasoning-capable open-source models outperformed non-reasoning models in 6 of 7 tasks.
- Identified task-specific human-AI boundaries: physicians remained stronger in diagnostic judgement and BI-RADS categorisation, while LLMs were stronger in longitudinal summarisation and recommendation drafting.
- Built an MLLM-based breast CEUS video classification framework using physics-driven frame selection, improving accuracy by 11.76 percentage points over traditional CNN baselines.
- Used modality ablation to expose text shortcut learning in medical MLLMs and showed that TTP-KDE preprocessing increased visual dependency by 2.5x.
- Contributed to RadioQC-R1, a domain-specific reasoning model trained on 15,990 reports with 17,589 expert-annotated errors, reducing radiologist review time by 10.86% and identifying 304 residual high-risk errors in 100,000 finalised reports.

## Public Code

The repositories below are public engineering work that supports my research training. They are not the unpublished code for the manuscripts above.

| Repository | What It Demonstrates |
| --- | --- |
| [hnu-digital-image-processing-project](https://github.com/1YeCheng/hnu-digital-image-processing-project) | Medical and general image-processing experiments covering lung CT preprocessing, lung parenchyma segmentation, juxtapleural nodule preservation, Fourier filtering, geometric transformation, classical morphology, connected components, and Segment Anything mask export. |
| [Machine-Learning](https://github.com/1YeCheng/Machine-Learning) | From-scratch logistic regression, LDA, and C4.5 decision tree implementation; SVM/SVR and BP neural network experiments; small-sample validation, bootstrap OOB evaluation, PR curves, confusion matrices, and WDBC breast cancer diagnosis experiments reaching 98.25% accuracy with a neural network. |
| [Intelligent-ID-Photo-Processing-System](https://github.com/1YeCheng/Intelligent-ID-Photo-Processing-System) | Explainable computer-vision system with face localisation, quality metrics, geometric compliance checks, skin-tone correction, background normalisation, annotated overlays, and JSON inspection reports. |
| [Seal-Quality-Inspection](https://github.com/1YeCheng/Seal-Quality-Inspection) | Multimodal 2D plus infrared inspection prototype with timestamp pairing, adaptive ROI handling, HSV defect extraction, infrared segmentation, decision fusion, PyQt5 interface, and traceable JSON/CSV logs. |
| [CloudComputeBookCode](https://github.com/1YeCheng/CloudComputeBookCode) | Distributed systems and cloud deployment coursework covering TCP services, concurrent state management, Redis-backed shared state, Kubernetes HPA, probes, graceful draining, recovery, and RBAC-based pod lifecycle handling. |

## Methods and Skills

- **Clinical AI evaluation**: task definition, multicentre report curation, reference-standard construction, reader-study design, human-AI comparison, deployment-boundary analysis.
- **LLM and MLLM development**: zero-shot prompting, model comparison, reasoning-model analysis, LoRA fine-tuning, modality ablation, visual-grounding analysis, shortcut-learning diagnosis.
- **Statistics**: non-parametric bootstrap resampling, case-level paired comparisons, Bonferroni correction, linear mixed-effects modelling, precision/recall, sensitivity/specificity, report-level accuracy, detection rate.
- **Medical image analysis**: lung CT preprocessing, ultrasound and CEUS analysis, thresholding, connected components, morphology, convex-hull repair, mask dilation, ROI localisation, contour analysis, HSV segmentation, Fourier filtering, Segment Anything mask export.
- **Engineering**: Python, NumPy, Pandas, OpenCV, scikit-image, scikit-learn, Matplotlib, Seaborn, Flask, PyQt5/Tkinter, structured JSON/CSV outputs, Linux, TCP networking, Docker/Kubernetes, HPA autoscaling.

## Additional Information

- **Languages**: CET-6 516/710.
- **Honors**: Outstanding Student, College Level, 2024.
- **Certification**: CCF CSP 240/500, top 12.9%, Sep 2024.
